# Ringkasan tugas penelitian

## PROMPT 1

Chapter172.pdfPDFmateri.pdfPDFBayangkan anda mahasiswa elektronika dan Instrumentasi universitas Gadjah Mada semester 5, hari ini anda akan berkuliah mata kuliah Research Trend Sistem Komputer & Jaringan. Hari ini dosen memberikan tugas untuk mengerjakan suatu tugas. Tugas ini dikerjakan individu. Instruksi tugas yaitu disuruh untuk meringkas isi paper tersebut dan mengkatikannya dengan materi data center yang tersedia dalam bentuk mind mapping pada gambar (notes.jpg) yang telah dilampirkan dan materi slide pdf pada file (materi.pdf). Paper telah dilampirkan pada file (Chapter172.pdf). Output tidak usah dalam bentuk presentasi, melainkan dalam teks penjelasan saja.
Lakukan pengerjaan tugas tersebut, pastikan tidak ada tulisan yang terlewat. Tidak perlu menggunakan kata kata kiasan dengan bahasa yang indah. Hindari struktur kalimat antitesis seperti 'ini bukan hanya X tapi Y'. Hindari juga penulisan awal kalimat 'ini adalah'.

## RESPONSE 1

Saya rangkum dulu isi bab “Sustainable Green Data Center Location Selection: Türkiye Case”, lalu saya kaitkan dengan mind map _Pusat Data_ (notes.jpg) dan materi slide _Pusat Data_ (materi.pdf).

___________

1\. Latar belakang umum dari paper dan materi kuliah
----------------------------------------------------

Slide awal menjelaskan bahwa volume data digital di dunia tumbuh sangat cepat, sampai orde ribuan exabyte, dengan sebagian besar berupa data tidak terstruktur. Grafik pada slide _Isu Teknologi_ menunjukkan kurva “information” yang naik jauh lebih cepat dibanding “available storage”, sehingga muncul _transient information_ dan gap kapasitas penyimpanan.

materi

Slide _Fakta tentang Data_ dan cabang mind map “data push → industrial standard” menekankan bahwa data menjadi aset organisasi yang harus disimpan dan dijaga dalam jangka panjang, misalnya: rekam medis sampai puluhan tahun, data keuangan 6–70 tahun, desain pesawat dan data minyak puluhan tahun.

materi

Hal ini tercermin di mind map dengan contoh: healthcare 75 tahun, farmasi 50–100 tahun, finance 30 tahun, aerospace 30 tahun, petroleum 50 tahun.

Mind map bagian “Layer infrastruktur” juga mengingatkan bahwa pusat data berada di “lapisan teknologi yang menjadi environment agar menyediakan resource dan menjalankan operasi dasar”, dengan tantangan kompleksitas, probabilitas/komputabilitas, _transient information_, dan fungsi sebagai _enabler_ layanan digital.

Paper kemudian masuk dari sisi lain: bagaimana semua kebutuhan data dan komputasi tersebut memunculkan beban energi dan dampak lingkungan pusat data, dan bagaimana memilih lokasi pusat data yang _green_ dan berkelanjutan.

Chapter172

___________

2\. Ringkasan sistematis isi paper “Sustainable Green Data Center Location Selection: Türkiye Case”
---------------------------------------------------------------------------------------------------

### 2.1. Konsep keberlanjutan dan kaitannya dengan transformasi digital

Bagian pendahuluan menjelaskan konsep _sustainability_ sebagai upaya menciptakan dan mempertahankan kondisi ko-eksistensi manusia dan lingkungan alam, untuk generasi sekarang dan mendatang. Terdapat tiga dimensi utama: lingkungan, sosial, dan ekonomi; UNESCO menambahkan dimensi budaya sebagai dimensi keempat.

Chapter172

Pembangunan berkelanjutan didefinisikan sebagai pemenuhan kebutuhan saat ini tanpa mengorbankan kemampuan generasi mendatang. Dalam konteks teknologi informasi (TI), keberlanjutan sering disederhanakan menjadi isu konsumsi daya dan energi terbarukan, padahal sebenarnya menyentuh dimensi ekologi dan sosio-ekonomi yang saling terkait.

Data center digambarkan sebagai fasilitas dengan intensitas penggunaan energi tinggi, yang menghasilkan panas internal dan membutuhkan pendinginan terus-menerus. Di sinilah pemilihan lokasi pusat data menjadi faktor krusial untuk efisiensi energi dan keberlanjutan.

Chapter172

### 2.2. Dasar-dasar pusat data (_Fundamentals of Data Centers_)

Bagian ini paralel dengan definisi di slide _Pusat Data_ dan cabang mind map “Fundamental function”.

*   Paper: pusat data adalah lingkungan terkontrol yang menampung server, storage, komponen keamanan, dan infrastruktur jaringan. Desainnya mencakup tata letak arsitektur, perencanaan ruang, infrastruktur elektrikal dan mekanikal, desain teknologi, dan komponen keamanan.
    
    Chapter172
    
*   Slide: pusat data digambarkan sebagai fasilitas yang memiliki kemampuan mengatur, mengelola, dan menyelenggarakan layanan TI dan komunikasi.
    
    materi
    
*   Mind map “Fundamental function” merinci fungsi dasar: menyediakan fasilitas pooling resources, mengatur ketersediaan dan cara penggunaan sumber daya, aksesibilitas, interoperabilitas, komputabilitas, keamanan, dan penyediaan akses ke layanan.
    

Paper membahas tahapan desain:

1.  **Pra-desain**: penentuan ukuran, topologi, lokasi, dan teknologi pendinginan berdasarkan kebutuhan masa depan.
    
2.  **Desain konseptual**: penguatan rencana untuk memenuhi standar instalasi, aspek ketahanan dan keamanan, serta target performa, efisiensi energi, dan _availability_.
    
3.  **Desain detail**: dokumentasi lengkap untuk konstruksi, pemenuhan kondisi lingkungan, dan persyaratan efisiensi energi.
    
    Chapter172
    

Infrastruktur listrik berfokus pada keandalan suplai daya, mencakup tegangan rendah/menengah, DC, UPS, dan genset cadangan. Harus scalable dan sesuai standar energi.

Chapter172

Cabang mind map “Manage resources” menguatkan aspek ini dengan daftar: _power/listrik, air cooling, cable, hardware resources, network resources, compute resources (CPU/GPU), memory, storage, backup, remote DRC_.

Infrastruktur teknologi berfokus pada jaringan telekomunikasi dengan kabel tembaga dan fiber, penempatan switch, dan desain berbagai jaringan sesuai kebutuhan. Untuk proteksi kebakaran digunakan detektor asap, tabung pemadam manual, serta sistem pencegah dan perlindungan kebakaran otomatis.

Chapter172

Keamanan fisik dan logis sangat ditekankan: kontrol akses berlapis (pagar perimeter, kartu, biometrik), pembatasan area tertentu, CCTV, dan petugas keamanan.

Chapter172

Di slide dan mind map, aspek ini muncul sebagai _Data Center Security Infrastruktur_, _Security challenge_, _Defense_, serta cabang karakteristik “Secure (secure by accident, secure by design)”.

materi

### 2.3. Dampak lingkungan pusat data (_Environmental Effects of Data Centers_)

Paper menjelaskan peran pusat data yang makin penting karena digitalisasi dan pandemi, misalnya untuk cloud computing dan telekomunikasi. Namun konsumsi energi pusat data meningkat tajam:

*   Perkiraan kontribusi sampai 3% dari konsumsi listrik global, dan bisa mencapai 4% pada 2030.
    
*   Hyperscale data center memiliki konsumsi energi tahunan setara pasokan listrik untuk 37.000 rumah tangga.
    
    Chapter172
    

Data center juga menyumbang sekitar 2% emisi karbon global; di AS sekitar 0,5% emisi gas rumah kaca nasional.

Chapter172

Tabel 1 pada halaman 6 menunjukkan permintaan energi global pusat data tahun 2014–2020:

*   Konsumsi energi server naik dari 86,4 ke 107,7 TWh, storage dari 14,3 ke 16,4 TWh, dan network dari 3,7 ke 4 TWh.
    
*   Infrastruktur pendukung turun dari 89,4 ke 72,1 TWh berkat peningkatan efisiensi.
    
*   Konsumsi di pusat data tradisional turun drastis (110,4 ke 44 TWh) sementara hyperscale naik kuat (25,2 ke 83,5 TWh) dan cloud data center juga naik.
    
    Chapter172
    

Paper menjelaskan bahwa pergeseran ke cloud dan hyperscale (Alibaba, Amazon, Google) membuat efisiensi energi keseluruhan meningkat karena skala besar memungkinkan optimasi konsumsi energi, pendinginan, dan utilisasi hardware.

Chapter172

Figur 1 pada halaman 6–7 menampilkan survei Uptime Institute tentang pelaporan data lingkungan:

*   Sekitar 85% operator melaporkan konsumsi daya pusat data dan 73% melaporkan PUE untuk alasan finansial.
    
*   Hanya 37% yang mengumpulkan data emisi karbon, dan persentase yang melaporkan Scope 1–2 dan Scope 1–3 jauh lebih kecil (17% dan 12%).
    
*   Hanya 39% yang melaporkan penggunaan air, turun 12 poin dari 2021; banyak yang merasa belum ada justifikasi bisnis untuk memantau pemakaian air.
    
    Chapter172
    

Paper menekankan bahwa regulasi kota/daerah yang mulai mensyaratkan konsumsi air minimal/nol akan memaksa desain fasilitas dan pemilihan perangkat pendingin yang lebih hemat air.

### 2.4. Kondisi pusat data di Türkiye

Bagian ini menjelaskan situasi nasional:

*   Terdapat 72 pusat data di 14 provinsi, dan lebih dari separuh berlokasi di Istanbul. Gambar peta pada halaman 8 menunjukkan sebarannya.
    
    Chapter172
    
*   Laporan Turkish Informatics Foundation (TBD) 2021 menyatakan bahwa karena posisi geo-politik Türkiye dan potensi risiko, solusi pusat data tidak boleh membuat ketergantungan produk/teknologi/vendor tertentu.
    
*   Rekomendasi utama terkait lokasi:
    
    *   Menetapkan kriteria performa yang konsisten dan diakui global.
        
    *   Mengidentifikasi faktor dan risiko lokal/nasional/regional.
        
    *   Menyusun spesifikasi yang sejajar dengan norma internasional.
        
    *   Mengembangkan SDM terlatih dan pengetahuan teknis jangka panjang.
        
    *   Mendefinisikan perilaku yang mendorong efisiensi energi dan memberi insentif.
        
    *   Kolaborasi dengan pemerintah terkait informasi tata ruang, risiko gempa, dan risiko meteorologis.
        
    *   Mendorong penggunaan energi terbarukan dan pengurangan jejak karbon.
        
        Chapter172
        

Telkoder (2015) menganalisis kompleksitas pemilihan lokasi dan mengusulkan tujuh kriteria: efisiensi energi, faktor pajak, ketersediaan jaringan fiber, kerangka hukum yang mendukung, kerentanan bencana alam, atribut geografis, dan ketersediaan tenaga kerja terampil.

Chapter172

Penelitian Yuna dkk. (2020) menggunakan lima indeks (bencana alam, iklim, energi, aksesibilitas, dan HCQL) untuk semua kota di Türkiye, dan menemukan bahwa Istanbul muncul sebagai lokasi optimal. Namun paper mengingatkan bahwa dengan populasi besar, iklim hangat, dan risiko gempa, Istanbul belum tentu pilihan terbaik jika kriteria diperluas. Karena itu disarankan penggunaan parameter, dimensi, dan kriteria penilaian yang lebih beragam.

Chapter172

### 2.5. Proses dan kriteria pemilihan lokasi pusat data (_Location Selection_)

Niles (2004) menyatakan bahwa pemilihan lokasi pusat data adalah proses kompleks yang melibatkan evaluasi finansial dan risiko:

*   Evaluasi finansial fokus pada biaya energi dan insentif pajak; tarif listrik dan efisiensi energi menjadi faktor utama, terutama di wilayah yang menerapkan pajak karbon.
    
*   Kolaborasi dengan pemerintah daerah/agensi pengembangan ekonomi membantu dalam proses pemilihan.
    
    Chapter172
    

Risiko lokasi dibagi menjadi tiga kelompok:

1.  **Risiko geografis**
    
    *   Meliputi bencana alam dan ancaman buatan manusia: gempa, badai, banjir, badai salju, petir, dan insiden lain.
        
    *   Diperlukan desain data center yang memitigasi risiko, misalnya rencana komunikasi darurat, genset cadangan dengan cadangan bahan bakar, jalur suplai listrik ganda, kepatuhan regulasi, dan mekanisme backup data yang mudah diakses.
        
        Chapter172
        
2.  **Risiko lokal**
    
    *   Berkaitan dengan distribusi daya lokal, suplai air, dan sumber bahan bakar cadangan.
        
    *   Jaringan listrik lokal harus mampu memenuhi kebutuhan sekarang dan masa depan, dengan kualitas daya yang baik.
        
    *   Ketersediaan air penting untuk pendinginan dan pemadaman kebakaran.
        
    *   Harus ada pemasok bahan bakar yang handal untuk genset.
        
    *   Aspek lain: aksesibilitas ke lokasi, jalur evakuasi bencana, jarak ke layanan penting (pemadam kebakaran, polisi), dan izin regulasi terkait kelistrikan, bangunan, keselamatan, efisiensi energi, emisi, dan lingkungan.
        
        Chapter172
        
3.  **Risiko bangunan**
    
    *   Mencakup lokasi fisik pusat data di dalam bangunan, penempatan peralatan berat, dan integritas struktural.
        
    *   Harus memperhatikan aktivitas penyewa lain jika fasilitas berbagi gedung.
        
    *   Service Level Agreements (SLA) perlu selaras dengan tujuan bisnis dan tingkat toleransi gangguan infrastruktur.
        
        Chapter172
        

Paper menegaskan kembali bahwa energi merupakan faktor pertama yang diprioritaskan organisasi karena porsi biaya operasional paling besar berasal dari energi.

Selain Telkoder (2015), beberapa pendekatan lain dibahas:

*   Covas dkk. (2013) mengusulkan dimensi evaluasi alternatif untuk lokasi pusat data berkelanjutan.
    
*   Turek dan Radgen (2021) membuat model matematis untuk penentuan lokasi optimal berbasis konsumsi energi pada konteks Jerman.
    
*   Kheybari dkk. (2020) mensintesis faktor penilaian sosial, ekonomi, dan lingkungan dari literatur.
    
*   Zhang dan Yang (2021) mengusulkan indeks keberlanjutan pusat data besar berdasarkan sistem refrigerasi, layout dan ventilasi, lokasi pusat data, volume data, dan daya server.
    
    Chapter172
    

### 2.6. Kerangka empat dimensi penilaian lokasi (Tabel 2)

Paper merangkum berbagai studi dan menyusun kerangka empat dimensi: _Evaluation of Risks, Social Evaluation, Economic Evaluation, Environmental Evaluation_. Tabel 2 berisi:

Chapter172

1.  **Evaluation of Risks**
    
    *   Ancaman lingkungan: banjir, aktivitas seismik, bahaya lain seperti kebakaran hutan, longsor.
        
    *   Bahaya yang disebabkan manusia: kebakaran, ledakan.
        
    *   Keamanan fasilitas: tingkat kriminalitas terhadap orang maupun properti.
        
2.  **Social Evaluation**
    
    *   Daya tarik bagi pekerja (fasilitas rekreasi, institusi pendidikan).
        
    *   Kualitas hidup.
        
    *   Akses dan kemudahan transportasi publik.
        
    *   Biaya hidup.
        
    *   Keamanan (tingkat kejahatan).
        
    *   Akses ke tenaga kerja terampil.
        
    *   Ketersediaan penyedia layanan pendukung yang kompeten.
        
    *   Ketersediaan dan kedekatan layanan darurat.
        
3.  **Economic Evaluation**
    
    *   Belanja modal (CapEx).
        
    *   Belanja operasional (OpEx):
        
        *   Biaya energi.
            
        *   Potensi penghematan energi (pengurangan panas buang, penggunaan energi terbarukan).
            
        *   Biaya komunikasi jaringan.
            
        *   Kebutuhan tenaga kerja.
            
    *   Skalabilitas.
        
    *   Daya tarik bagi pelanggan (kedekatan lokasi pusat data dengan pelanggan).
        
4.  **Environmental Evaluation**
    
    *   Polusi lingkungan lokal (penggunaan air untuk pendinginan, kualitas udara).
        
    *   Dampak pada lingkungan sekitar (kebisingan, pembuangan residu, perubahan temperatur).
        
    *   Pengurangan emisi CO₂ (melalui penghematan energi, _free cooling_, dsb.).
        
    *   Pemanfaatan energi terbarukan (matahari, angin).
        
    *   Dampak terhadap kawasan konservasi (cagar alam, situs arkeologi, dsb.).
        

Untuk konteks Türkiye, penulis merekomendasikan penilaian menggunakan nilai aktual tingkat provinsi/region berdasarkan data pemerintah pusat/daerah dan organisasi masyarakat sipil, bukan sekadar skala penilaian subjektif ahli. Ini untuk mengurangi bias dan meningkatkan objektivitas.

Chapter172

### 2.7. Diskusi dan kesimpulan

Bagian akhir mengulas kembali bahwa:

*   Kerangka empat dimensi (risiko, sosial, lingkungan, ekonomi) sejalan dengan prinsip keberlanjutan yang menuntut harmonisasi aspek ekologi, sosial, dan ekonomi dalam pemilihan lokasi pusat data.
    
    Chapter172
    
*   Banyak metodologi menggunakan teknik _multi-criteria decision making_ (MCDM). Namun ada kelemahan pada subjektivitas penilaian, terutama di dimensi sosial dan lingkungan, karena mengandalkan judgement pakar atau skala kepatuhan yang disusun peneliti.
    
*   Subjektivitas tersebut dapat menimbulkan bias, mengurangi replikasi hasil, dan menyulitkan penerapan di konteks lain. Diperlukan upaya penelitian lanjutan untuk meningkatkan objektivitas, misalnya dengan kriteria yang lebih terukur dan proses penilaian yang lebih baku.
    
*   Energi menjadi faktor paling kritis karena berpengaruh langsung pada biaya operasional dan target keberlanjutan. Efisiensi energi perlu menjadi fokus utama strategi pusat data.
    

Paper juga mengaitkan dengan laporan _2023 Global Data Center Market Comparison_ (Cushman & Wakefield) yang menilai 63 pasar pusat data di dunia berdasarkan 13 kategori: market size, fiber connectivity, cloud availability, biaya listrik, insentif, pajak, stabilitas politik, tingkat kekosongan, potensi pengembangan, inisiatif keberlanjutan, integrasi _smart city_, serta faktor biaya lahan dan risiko lingkungan.

Chapter172

Türkiye, khususnya Istanbul, belum termasuk dalam peringkat tersebut, tetapi dikategorikan sebagai “market to watch”. Penulis menekankan bahwa penelitian tentang pemilihan lokasi pusat data berkelanjutan di Türkiye penting untuk meningkatkan daya saing dan mendorong masuk ke perbandingan global di masa depan.

Kesimpulan besar: keberlanjutan, pemilihan lokasi, dan efisiensi energi saling terkait erat dalam pengelolaan pusat data; pendekatan komprehensif diperlukan agar dampak lingkungan dan ekonomi dapat dikendalikan.

Chapter172

___________

3\. Pengaitan dengan mind map _Pusat Data_ dan materi kuliah
------------------------------------------------------------

### 3.1. Layer Infrastruktur dan isu keberlanjutan

Mind map bagian “Layer infrastruktur” berisi:

*   Deskripsi lapisan teknologi sebagai environment dasar bagi operasi.
    
*   _Kompleksitas_: terdapat node _resources, operasional dasar, demand vs supply, process complex_.
    
*   _Probabilitas → komputabilitas_: performa layanan bisa naik turun, banyak kemungkinan, kebutuhan simulasi.
    
*   _Transient information_ versus _information production vs available storage_.
    
*   _Data push → industrial standard_: data diperlakukan sebagai aset organisasi yang disimpan dan dijaga dalam jangka waktu tertentu, dengan contoh umur simpan sektor kesehatan, farmasi, keuangan, kedirgantaraan, dan minyak.
    

Bagian ini selaras dengan pendahuluan dan slide _Isu Teknologi_ dan _Fakta tentang Data_ yang menjelaskan ledakan informasi, dominasi informasi tidak terstruktur, serta kebutuhan menyimpan data dalam jangka panjang.

materi

Dari sudut pandang paper, ledakan data memicu peningkatan kapasitas pusat data dan konsumsi energi. Keterbatasan _available storage_ dan tuntutan _business continuity_ mendorong pembangunan fasilitas besar (hyperscale), sehingga pemilihan lokasi yang efisien energi menjadi krusial.

Chapter172

### 3.2. Fundamental function dan empat dimensi penilaian

Di mind map, “Fundamental function” memuat:

*   **Fasilitas** → pooling resources.
    
*   **Mengatur** → ketersediaan sumber daya, cara penggunaan, aksesibilitas, interoperabilitas, komputabilitas, keamanan.
    
*   **Mengelola**.
    
*   **Services/layanan** → menyediakan akses ke layanan.
    

Dimensi ini dapat disejajarkan dengan empat dimensi penilaian lokasi di Tabel 2:

*   _Evaluation of Risks_ berkaitan dengan kemampuan fasilitas menahan bencana dan mengamankan aset.
    
*   _Social Evaluation_ terkait akses ke tenaga kerja, keamanan, dan kualitas hidup yang memengaruhi pengelolaan dan operasi harian.
    
*   _Economic Evaluation_ berhubungan dengan pooling resources, biaya energi, jaringan, dan tenaga kerja.
    
*   _Environmental Evaluation_ berhubungan dengan strategi pengelolaan yang minim polusi dan hemat energi.
    
    Chapter172
    

Dengan kata lain, fungsi dasar pusat data yang diajarkan di kelas perlu dipandang lewat “kaca mata” keberlanjutan ketika memilih lokasi.

### 3.3. Fungsi utama: manajemen sumber daya, manajemen, konektivitas, pengelolaan, DRC/backup

Mind map dan slide menjelaskan fungsi utama pusat data sebagai berikut:

materi

1.  **Manage resources**
    
    *   Mengelola sumber daya: listrik, pendingin, kabel, perangkat keras, sumber daya jaringan, CPU/GPU, memori, storage, backup, dan _remote DRC_.
        
    *   Paper menunjukkan bahwa sebagian besar biaya operasional berasal dari energi; lokasi dengan tarif listrik murah, potensi energi terbarukan, dan iklim yang menguntungkan untuk pendinginan akan mengurangi beban ini.
        
        Chapter172
        
2.  **Manajemen**
    
    *   Di mind map: user, akses, utilities, remote akses, privilege dan right management.
        
    *   Aspek ini berkaitan dengan dimensi sosial (perlu tenaga kerja terampil) dan risiko lokal (ketersediaan layanan utilitas, regulasi, dan keamanan).
        
        Chapter172
        
3.  **Konektivitas / Network Operating Center**
    
    *   Materi slide menampilkan diagram NOC dan berbagai _tools_ untuk monitoring performa, change management, net management.
        
        materi
        
    *   Mind map menulis: _Network operating center, Monitoring operation center, Data monitoring/analytic center, Security operating center_.
        
    *   Dalam kerangka Telkoder dan laporan Cushman & Wakefield, ketersediaan konektivitas fiber dan kualitas jaringan menjadi kriteria utama lokasi pusat data.
        
        Chapter172
        
4.  **Pengelolaan (operasi dan penempatan)**
    
    *   Opsi: _on premise, co-location, on cloud_, ditambah aspek topologi jaringan, manageable network, zonasi jaringan, multilayer switch, firewall, router, hingga konsep cloud-to-cloud, scanning network, dynamic routing, VPN, CDN/NDN.
        
    *   Paper menjelaskan tren pergeseran ke cloud dan hyperscale; hal ini selaras dengan cabang “Teknologi inti” yang menampilkan model layanan NIST (SaaS, PaaS, IaaS) dan elemen fondasional seperti virtualisasi, distributed computing, dan utility computing.
        
        materi
        
5.  **DRC/backup**
    
    *   Mind map: DRC/backup harus sama dengan operasional.
        
    *   Slide fungsi menyebut _Business Continuance Infrastructured_, dengan kriteria pemilihan lokasi, kuantitas ruang, layout, instalasi, kebutuhan listrik, dan jaringan infrastruktur yang scalable.
        
        materi
        
    *   Di paper, unsur ini terkait dengan dimensi risiko geografis dan lokal: pusat data utama dan DRC sebaiknya berada di wilayah dengan profil risiko berbeda, namun masih memenuhi syarat sosial, ekonomi, dan lingkungan tertentu.
        
        Chapter172
        

### 3.4. Karakteristik pusat data dan kaitannya dengan lokasi yang berkelanjutan

Slide dan mind map pada bagian “Karakteristik” menyebut: availability 24×7×365, quality of services, scalability dan flexibility (scale up, scale out), secure (secure by design/accident), continuous performance, aplikasi yang berjalan di DC, IP infrastructure (layer 2/3), dan storage (SAN, fibre channel switching, replication, backup, archival).

materi

Untuk memenuhi karakteristik tersebut, lokasi pusat data harus:

*   Memiliki risiko bencana relatif rendah atau bisa dimitigasi desain (dimensi _Evaluation of Risks_).
    
    Chapter172
    
*   Memiliki akses ke tenaga kerja dan penyedia layanan pendukung yang mampu memastikan operasi 24×7 (dimensi sosial).
    
*   Memberi biaya energi dan infrastruktur yang kompetitif agar ekspansi kapasitas (scale up/out) tetap ekonomis (dimensi ekonomi).
    
*   Mendukung pemakaian teknologi pendinginan yang efisien dan pemanfaatan energi terbarukan (dimensi lingkungan).
    

PUE dan pelaporan emisi yang disorot di Figur 1 menjadi indikator apakah karakteristik operasional tersebut dicapai dengan cara yang berkelanjutan atau tidak.

Chapter172

### 3.5. Teknologi inti dan contoh implementasi (GEOSS, CERN, GamaBox, GamaCloud)

Slide bagian akhir menampilkan beberapa contoh penggunaan pusat data berskala besar:

materi

*   **GEOSS Clearinghouse**: berbagi data observasi bumi dari >140 negara untuk penanggulangan bencana dan respons darurat, menggunakan cloud computing (EC2, Azure), database cloud skala besar, dan WebGIS/5D visualization.
    
*   **CERN**: contoh pusat data dengan komputasi intensif untuk eksperimen fisika energi tinggi.
    
*   **GamaBox / GamaCloud** dari UGM:
    
    *   Roadmap dari hardware bekas → cluster → grid → cloud, dengan implementasi prototipe superkomputer Raspberry Pi, perbandingan FLOPS dengan cluster lain, dan konsolidasi berbagai layanan (email, web hosting, file management, e-learning, akademik, multimedia) dalam satu _box_ berbasis cloud.
        

Beban komputasi tinggi pada kasus-kasus tersebut memperjelas mengapa efisiensi energi dan pemilihan lokasi sangat penting. Hiperskala dan cloud yang dideskripsikan di paper menjadi fondasi bagi layanan seperti GEOSS dan CERN, sementara inisiatif seperti GamaBox menunjukkan pendekatan lokal memanfaatkan hardware sederhana untuk membangun “mini data center” yang lebih hemat.

___________

4\. Penutup: keterkaitan paper dan materi kuliah bagi mahasiswa SKJ
-------------------------------------------------------------------

Dari sudut pandang mahasiswa Elektronika dan Instrumentasi UGM yang belajar _Research Trend Sistem Komputer & Jaringan_, beberapa poin penting yang bisa ditarik:

1.  Materi kuliah dan mind map menggambarkan struktur internal dan fungsi operasional pusat data: layer infrastruktur, manajemen sumber daya, karakteristik (availability, scalability, security), arsitektur, serta teknologi cloud.
    
    materi
    
2.  Paper menambahkan dimensi baru, yaitu bagaimana aspek-aspek teknis tersebut diterjemahkan ke dalam keputusan lokasi yang memperhatikan risiko, faktor sosial, pertimbangan ekonomi, dan dampak lingkungan.
    
    Chapter172
    
3.  Pertumbuhan data, tuntutan penyimpanan jangka panjang, dan dominasi aplikasi berbasis cloud menjadikan pusat data objek penting dalam diskusi keberlanjutan energi dan emisi karbon.
    
4.  Pendekatan penelitian yang digunakan saat ini masih memiliki kelemahan pada subjektivitas penilaian; peluang riset terbuka lebar untuk mengembangkan metode yang lebih objektif, misalnya dengan data spasial, data energi aktual, dan model matematis yang lebih kuat.
    
    Chapter172
    

Tugas kuliah mengenai pusat data jadi tidak hanya berbicara tentang desain jaringan, server, dan storage, tetapi juga mengenai bagaimana pusat data ditempatkan di dunia nyata agar layanan tetap tersedia, aman, ekonomis, dan ramah lingkungan.

## PROMPT 2

apakah anda bisa membaca file .tex

## RESPONSE 2

Bisa 🙂

Kalau kamu upload file `.tex`\-nya, aku bisa:

*   Membaca isinya (teks, struktur LaTeX, dll.)
    
*   Menjelaskan atau meringkas isi dokumen
    
*   Membantu memperbaiki error LaTeX
    
*   Mengubahnya ke format lain (misalnya jadi artikel biasa, laporan, atau slide outline)
    

Silakan upload file `.tex` yang dimaksud, lalu beritahu kamu mau dibantu apa: diperbaiki, diringkas, atau diubah formatnya.

## PROMPT 3

main.texFileMasukkan tulisan tulisan tersebut kedalam LaTex Beamer sesuai dengan tema Beamer yang telah saya tulis tersebut, pada template tersebut telah tersedia petunjuk untuk menerapkan numbering, membuat tabel dan lain lain, pastikan yang anda masukkan kedalam presentasi adalah yang benar benar layak untuk dimasukkan.

## RESPONSE 3

Berikut versi `main.tex` yang sudah saya isi dengan materi ringkasan paper dan pengaitan dengan mind map + slide pusat data. Silakan ganti nama, NIM, atau detail kecil lain kalau perlu.

```tex
%----------------------------------------------------------------------------------------
%	PACKAGES AND THEMES
%----------------------------------------------------------------------------------------
\documentclass[aspectratio=169,xcolor=dvipsnames, t]{beamer}
\usepackage{fontspec} % Allows using custom font. MUST be before loading the theme!
\usetheme{UGMBeamer}
\usepackage{hyperref}
\usepackage{graphicx} % Allows including images
\usepackage{booktabs} % Allows the use of \toprule, \midrule and  \bottomrule in tables
\usepackage{svg} %allows using svg figures
\usepackage{tikz}
\usepackage{makecell}
\usepackage{wrapfig}
% ADD YOUR PACKAGES BELOW

%----------------------------------------------------------------------------------------
%	TITLE PAGE CONFIGURATION
%----------------------------------------------------------------------------------------

\title[Green Data Center Location]{Sustainable Green Data Center Location\\Selection: Türkiye Case}
% Short title in [], long title in {}

\subtitle{Ringkasan Paper dan Kaitan dengan Materi Pusat Data}

\author[Akhi]{Akhi}
% Optionally add NIM, e.g.:
% \author[Akhi]{Akhi\\NIM: XX/XXXXXX/PA/XXXXX}

\institute[Universitas Gadjah Mada]{Departemen Elektronika dan Instrumentasi\\
Fakultas MIPA\\
Universitas Gadjah Mada}
% Short institute in [], full version in {}

\date{\today} % Date, can be changed to a custom date

%----------------------------------------------------------------------------------------
%	PRESENTATION SLIDES
%----------------------------------------------------------------------------------------

\begin{document}

\maketitlepage

%------------------------------------------------
\begin{frame}[t]{Overview}
    % Daftar isi akan terisi otomatis dari \makesection
    \tableofcontents
\end{frame}

%================================================
% 1. LATAR BELAKANG
%================================================
\makesection{Latar Belakang}

%------------------------------------------------
\begin{frame}{Konteks Tugas}
    \begin{itemize}
        \item Mata kuliah: Research Trend Sistem Komputer \& Jaringan.
        \item Tugas individu: meringkas isi bab \emph{``Sustainable Green Data Center Location Selection: Türkiye Case''} dan menghubungkannya dengan:
        \begin{itemize}
            \item Mind map materi pusat data (notes.jpg).
            \item Slide materi pusat data (materi.pdf).
        \end{itemize}
        \item Fokus presentasi:
        \begin{itemize}
            \item Konsep utama pusat data dari materi kuliah.
            \item Ringkasan isi paper.
            \item Keterkaitan antara keduanya dan poin riset yang muncul.
        \end{itemize}
    \end{itemize}
\end{frame}

%------------------------------------------------
\begin{frame}{Ledakan Data dan Kebutuhan Pusat Data}
    \begin{itemize}
        \item Volume data digital dunia tumbuh sangat cepat, mayoritas berupa data tidak terstruktur.
        \item Slide ``Isu Teknologi'' menunjukkan produksi informasi yang naik lebih cepat daripada kapasitas penyimpanan yang tersedia (gap ``information vs available storage'').
        \item Mind map ``data push $\rightarrow$ industrial standard'' menekankan:
        \begin{itemize}
            \item Data menjadi aset organisasi.
            \item Data perlu disimpan dalam jangka panjang (misal: rekam medis, data keuangan, desain pesawat, data minyak).
        \end{itemize}
        \item Pertumbuhan data dan kebutuhan retensi jangka panjang mendorong pembangunan pusat data berskala besar.
    \end{itemize}
\end{frame}

%================================================
% 2. FUNDAMENTAL PUSAT DATA (DARI MATERI)
%================================================
\makesection{Fundamental Pusat Data}

%------------------------------------------------
\begin{frame}{Definisi dan Fungsi Dasar}
    \begin{itemize}
        \item Pusat data adalah fasilitas dengan lingkungan terkontrol yang menampung:
        \begin{itemize}
            \item Server dan perangkat storage.
            \item Infrastruktur jaringan.
            \item Sistem kelistrikan dan pendinginan.
            \item Sistem keamanan fisik dan logis.
        \end{itemize}
        \item Mind map ``Fundamental function'':
        \begin{itemize}
            \item Menyediakan fasilitas pooling resources.
            \item Mengatur ketersediaan, cara penggunaan, aksesibilitas, interoperabilitas, komputabilitas, keamanan.
            \item Mengelola resource dan menyediakan layanan ke pengguna.
        \end{itemize}
    \end{itemize}
\end{frame}

%------------------------------------------------
\begin{frame}{Layer Infrastruktur dan Isu}
    \begin{itemize}
        \item Layer infrastruktur sebagai environment teknis tempat resource dijalankan.
        \item Isu yang muncul di mind map:
        \begin{itemize}
            \item Kompleksitas: banyak komponen dan proses yang saling bergantung.
            \item Probabilitas $\rightarrow$ komputabilitas: performa layanan naik turun, banyak kemungkinan yang perlu diprediksi/simulasikan.
            \item Transient information: tidak semua informasi dapat disimpan permanen.
            \item Kesenjangan antara produksi informasi dan kapasitas penyimpanan.
        \end{itemize}
        \item Manajemen infrastruktur perlu memperhitungkan kinerja, skalabilitas, dan efisiensi energi.
    \end{itemize}
\end{frame}

%------------------------------------------------
\begin{frame}{Fungsi Utama: Manage Resources}
    \begin{itemize}
        \item Mind map ``Manage resources'':
        \begin{itemize}
            \item Power/listrik.
            \item Air cooling dan sistem pendingin lain.
            \item Kabel dan konektivitas fisik.
            \item Hardware resources (server, switch, storage).
            \item Network resources.
            \item Compute resources (CPU, GPU).
            \item Memory dan media penyimpanan.
            \item Backup dan remote DRC.
        \end{itemize}
        \item Semua resource tersebut berkontribusi pada konsumsi energi dan biaya operasional.
    \end{itemize}
\end{frame}

%------------------------------------------------
\begin{frame}{Fungsi Utama Lain}
    \begin{itemize}
        \item \textbf{Manajemen}
        \begin{itemize}
            \item Pengelolaan user, akses, dan hak istimewa.
            \item Remote access dan utilities pendukung operasi.
        \end{itemize}
        \item \textbf{Konektivitas}
        \begin{itemize}
            \item Network Operating Center, Monitoring Operation Center.
            \item Data monitoring/analytic center dan Security Operation Center.
        \end{itemize}
        \item \textbf{Pengelolaan penempatan layanan}
        \begin{itemize}
            \item On-premise, co-location, dan on-cloud.
            \item Topologi jaringan, multilayer switch, firewall, router.
            \item Integrasi dengan VPN, CDN/NDN, dan cloud-to-cloud.
        \end{itemize}
        \item \textbf{DRC/Backup}
        \begin{itemize}
            \item DRC/backup dirancang selaras dengan sistem operasional.
        \end{itemize}
    \end{itemize}
\end{frame}

%------------------------------------------------
\begin{frame}{Karakteristik Operasional Pusat Data}
    \begin{itemize}
        \item Ketersediaan layanan 24/7/365.
        \item Quality of Service sesuai kebutuhan pengguna.
        \item Skalabilitas dan fleksibilitas:
        \begin{itemize}
            \item Scale up dan scale out.
        \end{itemize}
        \item Keamanan:
        \begin{itemize}
            \item Secure by design dan penguatan berlapis.
        \end{itemize}
        \item Continuous performance dengan dukungan:
        \begin{itemize}
            \item IP infrastructure (layer 2, layer 3).
            \item Storage: SAN, fibre channel switching, replication, backup, archival.
        \end{itemize}
    \end{itemize}
\end{frame}

%================================================
% 3. RINGKASAN PAPER
%================================================
\makesection{Ringkasan Paper}

%------------------------------------------------
\begin{frame}{Konsep Keberlanjutan dan Pusat Data}
    \begin{itemize}
        \item Keberlanjutan: pemenuhan kebutuhan generasi sekarang tanpa mengurangi kemampuan generasi mendatang.
        \item Dimensi utama:
        \begin{itemize}
            \item Lingkungan, sosial, dan ekonomi.
            \item UNESCO menambah dimensi budaya.
        \end{itemize}
        \item Pusat data:
        \begin{itemize}
            \item Fasilitas dengan intensitas penggunaan energi tinggi.
            \item Menghasilkan panas dan membutuhkan pendinginan terus-menerus.
        \end{itemize}
        \item Pemilihan lokasi pusat data menjadi faktor penting untuk efisiensi energi dan keberlanjutan.
    \end{itemize}
\end{frame}

%------------------------------------------------
\begin{frame}{Dampak Energi dan Lingkungan Pusat Data}
    \begin{itemize}
        \item Konsumsi energi pusat data diperkirakan mencapai sekitar 3\% dari konsumsi listrik global dan dapat naik menjadi sekitar 4\% pada 2030.
        \item Kontribusi emisi karbon global pusat data berada di kisaran 2\%, dengan kontribusi sekitar 0{,}5\% dari emisi gas rumah kaca di Amerika Serikat.
        \item Tabel tren konsumsi energi 2014--2020:
        \begin{itemize}
            \item Konsumsi server, storage, dan network meningkat.
            \item Konsumsi infrastruktur pendukung turun karena efisiensi.
            \item Pusat data tradisional menurun, hyperscale dan cloud meningkat.
        \end{itemize}
        \item Perpindahan ke cloud dan hyperscale memberi peluang optimasi energi skala besar.
    \end{itemize}
\end{frame}

%------------------------------------------------
\begin{frame}{Pelaporan Lingkungan oleh Operator}
    \begin{itemize}
        \item Survei Uptime Institute (Figur pada paper):
        \begin{itemize}
            \item Sekitar 85\% operator mengumpulkan data konsumsi daya pusat data.
            \item Sekitar 73\% melaporkan PUE, terutama untuk kepentingan finansial.
            \item Hanya sekitar 37\% yang mengumpulkan data emisi karbon.
            \item Pelaporan Scope 1--2 dan Scope 1--3 lebih sedikit lagi.
            \item Sekitar 39\% yang melaporkan penggunaan air, cenderung menurun.
        \end{itemize}
        \item Regulasi yang membatasi pemakaian air akan mendorong desain pendinginan yang lebih hemat air.
    \end{itemize}
\end{frame}

%------------------------------------------------
\begin{frame}{Kondisi Pusat Data di Türkiye}
    \begin{itemize}
        \item Terdapat sekitar 72 pusat data di 14 provinsi.
        \item Lebih dari separuh berlokasi di Istanbul.
        \item Laporan Turkish Informatics Foundation (TBD) menekankan:
        \begin{itemize}
            \item Solusi pusat data perlu menghindari ketergantungan pada produk/teknologi/vendor tunggal.
            \item Perlu kriteria performa yang konsisten dan diakui global.
            \item Perlu identifikasi faktor dan risiko lokal, nasional, dan regional.
        \end{itemize}
        \item Telkoder (2015) mengusulkan tujuh kriteria pemilihan lokasi:
        \begin{itemize}
            \item Efisiensi energi, faktor pajak, ketersediaan jaringan fiber.
            \item Kerangka hukum, risiko bencana alam, atribut geografis.
            \item Ketersediaan tenaga kerja terampil.
        \end{itemize}
    \end{itemize}
\end{frame}

%================================================
% 4. PEMILIHAN LOKASI GREEN DATA CENTER
%================================================
\makesection{Pemilihan Lokasi Green DC}

%------------------------------------------------
\begin{frame}{Energi dan Pertimbangan Finansial}
    \begin{itemize}
        \item Menurut Niles (2004), pemilihan lokasi pusat data adalah proses kompleks yang menggabungkan:
        \begin{itemize}
            \item Evaluasi finansial (biaya energi, tarif listrik, insentif pajak).
            \item Evaluasi risiko lokasi.
        \end{itemize}
        \item Energi menjadi faktor pertama yang dipertimbangkan:
        \begin{itemize}
            \item Porsi terbesar biaya operasional berasal dari energi.
            \item Lokasi dengan tarif listrik rendah dan potensi energi terbarukan lebih menarik.
        \end{itemize}
        \item Kolaborasi dengan pemerintah daerah dan lembaga pengembangan ekonomi membantu mengakses data dan insentif.
    \end{itemize}
\end{frame}

%------------------------------------------------
\begin{frame}{Kategori Risiko Lokasi}
    \begin{enumerate}
        \item \textbf{Risiko Geografis}
        \begin{itemize}
            \item Bencana alam: gempa, badai, banjir, badai salju, petir.
            \item Risiko lain: kebakaran hutan, tanah longsor.
        \end{itemize}
        \item \textbf{Risiko Lokal}
        \begin{itemize}
            \item Kualitas dan kapasitas jaringan listrik lokal.
            \item Ketersediaan air untuk pendinginan dan sistem kebakaran.
            \item Ketersediaan pemasok bahan bakar untuk genset.
            \item Aksesibilitas lokasi dan kedekatan dengan layanan penting.
        \end{itemize}
        \item \textbf{Risiko Bangunan}
        \begin{itemize}
            \item Integritas struktural dan lokasi ruang pusat data di dalam gedung.
            \item Aktivitas penyewa lain jika gedung digunakan bersama.
        \end{itemize}
    \end{enumerate}
\end{frame}

%------------------------------------------------
\begin{frame}{Pendekatan Penelitian Terdahulu}
    \begin{itemize}
        \item Yuna dkk. (2020):
        \begin{itemize}
            \item Menggunakan indeks bencana alam, iklim, energi, aksesibilitas, dan HCQL.
            \item Menemukan Istanbul sebagai lokasi optimal, namun perlu peninjauan ulang karena faktor populasi, iklim hangat, dan risiko gempa.
        \end{itemize}
        \item Studi lain yang dibahas:
        \begin{itemize}
            \item Covas dkk. (2013): dimensi alternatif untuk lokasi pusat data berkelanjutan.
            \item Turek \& Radgen (2021): model matematis untuk pemilihan lokasi berbasis konsumsi energi.
            \item Kheybari dkk. (2020): sintesis faktor sosial, ekonomi, dan lingkungan.
            \item Zhang \& Yang (2021): indeks keberlanjutan pusat data besar.
        \end{itemize}
        \item Laporan \emph{2023 Global Data Center Market Comparison} menempatkan Türkiye sebagai ``market to watch''.
    \end{itemize}
\end{frame}

%================================================
% 5. KERANGKA EMPAT DIMENSI PENILAIAN
%================================================
\makesection{Kerangka Empat Dimensi}

%------------------------------------------------
\begin{frame}{Empat Dimensi Penilaian Lokasi}
    \begin{itemize}
        \item Paper menyusun kerangka empat dimensi:
    \end{itemize}
    \begin{table}[h]
        \centering
        \footnotesize
        \begin{tabular}{@{}p{2.5cm}p{8cm}@{}}
            \toprule
            \textbf{Dimensi} & \textbf{Contoh Kriteria} \\
            \midrule
            Evaluation of Risks & Banjir, aktivitas seismik, bahaya lain; risiko kebakaran dan ledakan; tingkat kriminalitas terhadap orang dan properti. \\
            \addlinespace
            Social Evaluation & Daya tarik bagi pekerja, kualitas hidup, akses transportasi publik, biaya hidup, keamanan, ketersediaan tenaga kerja terampil, layanan pendukung, layanan darurat. \\
            \addlinespace
            Economic Evaluation & Belanja modal dan operasional, biaya energi, potensi penghematan energi, biaya komunikasi jaringan, kebutuhan tenaga kerja, skalabilitas, daya tarik lokasi bagi pelanggan. \\
            \addlinespace
            Environmental Evaluation & Pemakaian air untuk pendinginan, polusi lokal, pengurangan emisi CO\textsubscript{2}, pemanfaatan energi terbarukan, dampak pada kawasan konservasi. \\
            \bottomrule
        \end{tabular}
    \end{table}
\end{frame}

%------------------------------------------------
\begin{frame}{Rekomendasi Penilaian untuk Türkiye}
    \begin{itemize}
        \item Penilaian lokasi pusat data sebaiknya menggunakan:
        \begin{itemize}
            \item Nilai aktual per provinsi/region untuk indikator risiko, sosial, ekonomi, dan lingkungan.
            \item Data dari pemerintah pusat/daerah dan organisasi masyarakat sipil.
        \end{itemize}
        \item Tujuan:
        \begin{itemize}
            \item Mengurangi subjektivitas penilaian ahli.
            \item Meningkatkan objektivitas dan replikabilitas hasil.
            \item Memudahkan penerapan kerangka di konteks lain.
        \end{itemize}
        \item Energi tetap menjadi komponen paling kritis karena memengaruhi biaya operasional dan target keberlanjutan.
    \end{itemize}
\end{frame}

%================================================
% 6. KAITAN DENGAN MATERI PUSAT DATA
%================================================
\makesection{Kaitan dengan Materi Pusat Data}

%------------------------------------------------
\begin{frame}{Hubungan dengan Layer Infrastruktur dan Fungsi}
    \begin{itemize}
        \item Layer infrastruktur dalam mind map menggambarkan:
        \begin{itemize}
            \item Kompleksitas sistem.
            \item Keterbatasan kapasitas storage.
            \item Peran data sebagai aset jangka panjang.
        \end{itemize}
        \item Paper menambahkan:
        \begin{itemize}
            \item Dampak lingkungan dan konsumsi energi dari infrastruktur tersebut.
            \item Kebutuhan pemilihan lokasi yang mempertimbangkan risiko, faktor sosial, ekonomi, dan lingkungan.
        \end{itemize}
        \item Fungsi utama pusat data (manage resources, manajemen, konektivitas, DRC) harus disejajarkan dengan:
        \begin{itemize}
            \item Efisiensi energi.
            \item Keberlanjutan jangka panjang.
        \end{itemize}
    \end{itemize}
\end{frame}

%------------------------------------------------
\begin{frame}{Implikasi bagi Desain dan Operasi}
    \begin{itemize}
        \item Desain pusat data perlu memasukkan:
        \begin{itemize}
            \item Strategi efisiensi energi (desain pendinginan, pemanfaatan energi terbarukan).
            \item Strategi keberlanjutan air dan pengelolaan limbah.
        \end{itemize}
        \item Pengelolaan harian:
        \begin{itemize}
            \item Monitoring PUE, emisi, dan konsumsi air sebagai bagian dari operasi rutin.
            \item Integrasi dengan kebijakan perusahaan dan regulasi pemerintah.
        \end{itemize}
        \item Perspektif riset:
        \begin{itemize}
            \item Pengembangan metode penilaian lokasi yang lebih objektif.
            \item Pemanfaatan data spasial dan data energi aktual.
        \end{itemize}
    \end{itemize}
\end{frame}

%================================================
% 7. KESIMPULAN
%================================================
\makesection{Kesimpulan}

%------------------------------------------------
\begin{frame}{Kesimpulan dan Insight}
    \begin{itemize}
        \item Materi kuliah dan mind map menjelaskan struktur internal dan fungsi operasional pusat data: layer infrastruktur, manajemen resource, karakteristik availability dan security, serta teknologi cloud.
        \item Paper menekankan bahwa:
        \begin{itemize}
            \item Pusat data memiliki dampak signifikan terhadap konsumsi energi dan emisi.
            \item Pemilihan lokasi perlu mempertimbangkan empat dimensi: risiko, sosial, ekonomi, dan lingkungan.
        \end{itemize}
        \item Banyak metodologi yang bergantung pada penilaian subjektif sehingga masih terbuka peluang riset untuk:
        \begin{itemize}
            \item Menggunakan indikator yang lebih terukur dan data resmi.
            \item Mengurangi bias dalam penilaian sosial dan lingkungan.
        \end{itemize}
        \item Bagi mahasiswa SKJ, pusat data menjadi objek yang tidak hanya terkait desain sistem dan jaringan, tetapi juga terkait kebijakan energi dan keberlanjutan.
    \end{itemize}
\end{frame}

%================================================
% 8. REFERENSI
%================================================
\makesection{Citations and References}

%------------------------------------------------
\begin{frame}{Citations}
    \begin{itemize}
        \item T. Tuncalı Yaman, ``Sustainable Green Data Center Location Selection: Türkiye Case'', dalam \emph{Sustainable and Green Energy Policies}, Nova Science Publishers, 2024.
        \item Materi kuliah Pusat Data, Program Studi Elektronika dan Instrumentasi, Universitas Gadjah Mada.
        \item Mind map Pusat Data (notes.jpg).
    \end{itemize}
\end{frame}

%------------------------------------------------
\begin{frame}{References}
    % Beamer tidak menggunakan BibTeX di template ini, sehingga referensi dimasukkan manual
    \footnotesize{
        \begin{thebibliography}{99}
            \bibitem{yaman2024}
            T.~Tuncalı Yaman.
            \newblock Sustainable Green Data Center Location Selection: Türkiye Case.
            \newblock In {\em Sustainable and Green Energy Policies}. Nova Science Publishers, 2024.

            \bibitem{materiDC}
            Departemen Elektronika dan Instrumentasi.
            \newblock Materi Kuliah Pusat Data.
            \newblock Universitas Gadjah Mada.

            \bibitem{mindmap}
            Akhi.
            \newblock Mind Map Pusat Data.
            \newblock Tugas mata kuliah Research Trend Sistem Komputer \& Jaringan, 2024.
        \end{thebibliography}
    }
\end{frame}

%----------------------------------------------------------------------------------------
% Final PAGE
%----------------------------------------------------------------------------------------
\finalpagetext{Terima kasih atas perhatiannya}
\makefinalpage

\end{document}
```

Kalau mau, kamu bisa menyesuaikan:

*   `\author[...]` dan `\institute[...]` dengan nama program yang paling sesuai.
    
*   `\date{...}` dengan tanggal presentasi sebenarnya.
    
*   Menambah gambar mind map atau ilustrasi lain dengan `\includegraphics` di frame tertentu.

