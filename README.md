# Ndalem Toemino — Javanese Heritage Inn 🏡

A dynamic full-stack web app for **Ndalem Toemino** inn. Built with **Next.js 14** + **Supabase**.

## Features
- 🏡 Beautiful Javanese-themed landing page
- 🔐 User authentication (register / login / logout)
- 🛏️ Room browsing with image placeholders
- 📅 Private room reservations (auth-protected)
- 📋 My Reservations dashboard (view & cancel)
- 📱 Fully responsive design

---

## 1. Set Up Supabase

### A. Create a Supabase Project
1. Go to https://supabase.com and sign up / log in
2. Click **"New Project"**
3. Fill in project name, password, and region → click **Create Project**
4. Wait for the project to be ready (~1 min)

### B. Get Your API Keys
1. Go to **Settings → API** in your Supabase dashboard
2. Copy:
   - `Project URL` → this is your `NEXT_PUBLIC_SUPABASE_URL`
   - `anon public` key → this is your `NEXT_PUBLIC_SUPABASE_ANON_KEY`

### C. Run the Database Schema

Go to **SQL Editor** in your Supabase dashboard and run this SQL:

```sql
-- Create rooms table
CREATE TABLE rooms (
  id uuid DEFAULT gen_random_uuid() PRIMARY KEY,
  name text NOT NULL,
  description text,
  price_per_night numeric NOT NULL,
  capacity int NOT NULL DEFAULT 2,
  amenities text[] DEFAULT '{}',
  image_url text,
  created_at timestamptz DEFAULT now()
);

-- Create reservations table
CREATE TABLE reservations (
  id uuid DEFAULT gen_random_uuid() PRIMARY KEY,
  user_id uuid REFERENCES auth.users(id) ON DELETE CASCADE NOT NULL,
  room_id uuid REFERENCES rooms(id) ON DELETE CASCADE NOT NULL,
  check_in date NOT NULL,
  check_out date NOT NULL,
  guests int NOT NULL DEFAULT 1,
  special_requests text,
  status text NOT NULL DEFAULT 'pending' CHECK (status IN ('pending', 'confirmed', 'cancelled')),
  created_at timestamptz DEFAULT now()
);

-- Enable Row Level Security
ALTER TABLE rooms ENABLE ROW LEVEL SECURITY;
ALTER TABLE reservations ENABLE ROW LEVEL SECURITY;

-- Rooms: anyone can read
CREATE POLICY "Public rooms" ON rooms FOR SELECT USING (true);

-- Reservations: users can only CRUD their own
CREATE POLICY "Own reservations select" ON reservations FOR SELECT USING (auth.uid() = user_id);
CREATE POLICY "Own reservations insert" ON reservations FOR INSERT WITH CHECK (auth.uid() = user_id);
CREATE POLICY "Own reservations update" ON reservations FOR UPDATE USING (auth.uid() = user_id);
CREATE POLICY "Own reservations delete" ON reservations FOR DELETE USING (auth.uid() = user_id);

-- Seed sample rooms (optional)
INSERT INTO rooms (name, description, price_per_night, capacity, amenities) VALUES
  ('Kamar Melati', 'A serene room adorned with traditional Javanese batik, offering a peaceful garden view and a private veranda.', 350000, 2, ARRAY['WiFi', 'AC', 'Hot Water', 'Garden View']),
  ('Kamar Kenanga', 'Spacious suite with authentic teak furniture, a four-poster bed, and a luxurious private bathroom.', 550000, 3, ARRAY['WiFi', 'AC', 'Hot Water', 'Breakfast', 'TV']),
  ('Kamar Anggrek', 'Our premium family suite, featuring a separate living area, two bedrooms, and exclusive courtyard access.', 850000, 4, ARRAY['WiFi', 'AC', 'Hot Water', 'Breakfast', 'Parking', 'TV']);
```

---

## 2. Configure Environment Variables Locally

Edit `.env.local` and paste your keys:

```
NEXT_PUBLIC_SUPABASE_URL=https://your-project-ref.supabase.co
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-anon-key-here
```

---

## 3. Run Locally

```bash
npm install
npm run dev
```

Open http://localhost:3000

---

## 4. Deploy to Vercel

### A. Push to GitHub
1. Create a new GitHub repository
2. In your project folder, run:
```bash
git init
git add .
git commit -m "Initial commit: Ndalem Toemino website"
git remote add origin https://github.com/YOUR_USERNAME/ndalem-toemino.git
git push -u origin main
```

### B. Import to Vercel
1. Go to https://vercel.com and log in
2. Click **"Add New Project"**
3. Select your GitHub repository
4. Click **"Import"**

### C. Set Environment Variables in Vercel
Before clicking Deploy, add these under **"Environment Variables"**:

| Name | Value |
|---|---|
| `NEXT_PUBLIC_SUPABASE_URL` | Your Supabase Project URL |
| `NEXT_PUBLIC_SUPABASE_ANON_KEY` | Your Supabase anon key |

### D. Deploy
Click **"Deploy"** → Vercel will build and give you a `.vercel.app` URL in ~2 minutes!

---

## Adding Real Photos

Replace the placeholder images by:
1. Uploading photos to **Supabase Storage** (Storage → New bucket → upload)
2. Updating the `image_url` column in your `rooms` table with the public URL

Or simply replace the `<ImagePlaceholder>` components in the code with `<img>` or Next.js `<Image>` tags.
