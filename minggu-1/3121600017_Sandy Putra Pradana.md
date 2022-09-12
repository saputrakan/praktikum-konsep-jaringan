# Praktikum Jaringan Komputer

### 1. Dasar Teori

#### 1.1. Media Jaringan Komputer

Jaringan komputer _computer network_ adalah jaringan telekomunikasi yang memungkinkan antar komputer untuk saling berkomunikasi dengan bertukar data. Tujuan dari jaringan komputer adalah agar dapat mencapai tujuannya, setiap bagian dari jaringan komputer dapat meminta dan memberikan layanan _service_. Pihak yang meminta/menerima layanan disebut klien _client_ dan yang memberikan/mengirim layanan disebut peladen _server_. Desain ini disebut dengan sistem _client-server_, dan digunakan pada hampir seluruh aplikasi jaringan komputer.

1. Media Wireless

Jaringan nirkabel _wireless network_ adalah bidang disiplin yang berkaitan dengan komunikasi antar sistem komputer tanpa menggunakan kabel. Jaringan nirkabel ini sering dipakai untuk jaringan komputer baik pada jarak yang dekat (beberapa meter, memakai alat/pemancar bluetooth) maupun pada jarak jauh (lewat satelit). Bidang ini erat hubungannya dengan bidang telekomunikasi, teknologi informasi, dan teknik komputer. Jenis jaringan yang populer dalam kategori jaringan nirkabel ini meliputi: Jaringan kawasan lokal nirkabel (wireless LAN/WLAN) menggunakan Wi-Fi.

2. Serat Optik
   Serat optik adalah saluran transmisi atau sejenis kabel yang terbuat dari kaca atau plastik yang sangat halus dan lebih kecil dari sehelai rambut, dan dapat digunakan untuk mentransmisikan sinyal cahaya dari suatu tempat ke tempat lain. Sumber cahaya yang digunakan biasanya adalah laser atau LED. Kabel ini berdiameter kurang lebih 120 mikrometer. Cahaya yang ada di dalam serat optik tidak keluar karena indeks bias dari kaca lebih besar daripada indeks bias dari udara, karena laser mempunyai spektrum yang sangat sempit. Kecepatan transmisi serat optik sangat tinggi sehingga sangat bagus digunakan sebagai saluran komunikasi.

3. Media Kabel Tembaga

Kabel tembaga terbagi atas UTP (Unshielded Twisted Pair) dan STP (Shielded Twisted Pair). Perbedaan dari keduanya adalah adanya pelindung dan tidak adanya pelindung pada bagian inti konduktornya. Kabel UTP terdiri dari 4 pasang kabel dengan jalinan yang berbeda-beda tiap incinya.Semakin rapat jalinan tersebut, tingkat transimisi dan harganya semakin tinggi.Kabel UTP ini menggunakan konektor RJ-45 yang biasa digunakan untuk Eternet, ISDN, atau sambungan telepon.

#### 1.2. Standar Kabel UTP

Kabel UTP dikelompokan menggunakan istilah _Category_ atau biasa kita menyebutnya CAT. Kabel UTP dikategorikan berdasarkan kualitas transmisi data yang tersedia. Semakin tinggi kategorinya maka semakin cepat transmisi data yang dilakukan. Di antara semua kategori kabel UTP, kabel CAT5e dan CAT5 merupakan yang paling populer yang banyak digunakan pada jaringan Ethernet.

- Kategori 1 – CAT1

Kabel UTP dengan kategori 1 merupakan kabel dengan kualitas transmisi terendah yaitu sebesar 1 Mbps. Kabel dengan kategori ini hanya mendukung komunikasi suara analog saja sehingga kurang cocok untuk sistem modern saat ini. Kabel CAT1 dulunya digunakan pada tahun 1983 untuk menghubungkan telephone analog Plain Old Telephone Service (POTS).

- Kategori 2 – CAT2

Kabel UTP kategori 2 memiliki kecepatan transmisi data hingga 4 Mbps. Kabel dengan kategori ini telah mendukung data dan suara digital. Umumnya kabel ini digunakan pada jaringan dengan teknologi Token Ring oleh IBM, namun seiring perkembangan jaman kabel tipe ini sudah tidak cocok lagi digunakan pada sistem modern saat ini.

- Kategori 3 – CAT3

Kabel UTP kategori 3 memiliki kecepatan transmisi data hingga 10 Mbps dan mendukung komunikasi data dan suara digital. Bila ditinjau dari segi perkembangan teknologi Ethernet, kabel CAT3 memiliki kemampuan yang terendah, karena memang hanya mendukung jaringan 10BASE-T saja. Umumnya kabel jenis ini digunakan pada jaringan IBM Token Ring dengan kecepatan 4 Mbps sebagai pengganti CAT2

- Kategori 4 – CAT4

Kabel UTP kategori 4 memiliki kecepatan transmisi data hingga 16 Mbps dan mendukung komunikasi data dan suara digital. Umumnya kabel ini juga digunakan pada jaringan IBM Token Ring 16 Mbps dan juga didukung pada jaringan Ethernet 10BASE-T.

- Kategori 5 – CAT5

Kabel UTP kategori 5 memiliki kecepatan transmisi data hingga 100 Mbps dan mendukung komunikasi data dan suara digital. Kabel jenis CAT5 ini juga dapat berjalan pada kecepatan transmisi data hingga 1Gbps tetapi dengan syarat panjang kabel harus lebih pendek dari 100 meter. Umumnya, kabel jenis ini mendukung jaringan Token Ring, Ethernet (10BaseT) dan Fast Ethernet (100BaseT). Kabel kategori ini merupakan kabel yang paling populer yang banyak digunakan pada instalasi jaringan.

- Kategori 5e – CAT5e

Kabel UTP kategori 5e ini merupakan bentuk peningkatan dari kabel UTP CAT5 dengan kemampuan transmisi data hingga 1 Gbps atau pada kecepatan 10/100/1000Mbps. Kabel jenis ini direkomendasikan pada penggunaan jaringan Gigabit Ethernet, meskipun kabel UTP CAT 6 lebih direkomendasikan untuk kinerja yang maksimal.

- Kategori 6 – CAT6

Kabel UTP kategori 6 memiliki kecepatan transmisi data hingga 10 Gbps dengan frekuensi komunikasi 250Mhz dan mendukung komunikasi data dan suara digital. Umumnya kabel jenis ini digunakan pada jaringan Gigabit Ethernet dan 10G Ethernet dengan panjang hingga 55 meter.

- Kategori 6a – CAT6a

Kabel UTP kategori 6a ini merupakan bentuk peningkatan dari kabel UTP CAT6 dengan frekuensi komunikasi yang lebih besar yaitu sebesar 500 Mhz.

- Kategori 7 – CAT7

Kabel UTP kategori 7 memiliki kecepatan transmisi data hingga 10 Gbps dengan frekuensi komunikasi hingga 600 Mhz dan mendukung komunikasi data dan suara digital. Umumnya kabel jenis ini digunakan pada jaringan Gigabit Ethernet dan 10G Ethernet dengan panjang hingga 100 meter.

#### 1.3. Koneksi Dengan Kabel UTP

1. Straight
   Kabel straight adalah istilah untuk kabel yang menggunakan standar yang sama pada kedua ujung kabelnya, bisa EIA/TIA 568A atau EIA/TIA 568B pada kedua ujung kabel. Sederhananya, urutan warna pada kedua ujung kabel sama. Pada kabel straight, pin 1 di salah satu ujung kabel terhubung ke pin 1 pada ujung lainnya, pin 2 terhubung ke pin 2 di ujung lainnya, dan seterusnya. Jadi, ketika PC mengirim data pada pin 1 dan 2 lewat kabel straight ke Switch, Switch menerima data pada pin 1 dan 2. Nah, karena pin 1 dan 2 pada switch tidak akan digunakan untuk mengirim data sebagaimana halnya pin 1 dan 2 pada PC, maka Switch menggunakan pin 3 dan 6 untuk mengirim data ke PC, karena PC menerima data pada pin 3 dan 6.
   Penggunaan kabel straight :
1. Menghubungkan komputer ke port biasa di Switch.
1. Menghubungkan komputer ke port LAN modem cable/DSL.
1. Menghubungkan port WAN router ke port LAN modem cable/DSL.
1. Menghubungkan port LAN router ke port uplink di Switch.
1. Menghubungkan 2 HUB/Switch dengan salah satu HUB/Switch menggunakan port uplink dan yang lainnya menggunakan port biasa

1. Crossover
   Kabel crossover menggunakan EIA/TIA 568A pada salah satu ujung kabelnya dan EIA/TIA 568B pada ujung kabel lainnya. Untuk mengenali sebuah kabel apakah crossover ataupun straight adalah dengan hanya melihat salah satu ujung kabel. Jika urutan warna kabel pada pin 1 adalah Putih Hijau maka kabel tersebut adalah kabel crossover (padahal jika ujung yang satunya lagi juga memiliki urutan warna yang sama yaitu Putih Hijau sebagai pin 1, maka kabel tersebut adalah kabel Straight). Tapi untungnya, kebanyakan kabel menggunakan standar EIA/TIA 568B pada kedua ujung kabelnya.
   Penggunaan kabel crossover :
1. Menghubungkan 2 buah komputer secara langsung.
1. Menghubungkan 2 buah HUB / Switch menggunakan port biasa diantara kedua HUB / Switch.
1. Menghubungkan komputer ke port uplink Switch.
1. Menghubungkan port LAN router ke port biasa di HUB/Switch.

### 2. Pembuatan Kabel UTP

#### 2.1 Alat Yang Dipersiapkan Dan Kegunaannya

1. Tang Crimping
   Tang Crimping adalah alat untuk memotong kabel UTP dan untuk menjepit ujung konektor,alat ini bentuknya hampir sama dengan Tang biasa yang sering kita lihat atau temui.
2. Kabel UTP
   Kabel UTP kita gunakan untuk saling menghubungkan jaringan internet dan di dalam kabel UTP ini terdapat 8 helai kabel kecil yang berwarna-warni.
3. Konektor RJ-45
   Konektor adalah alat yang kita pasang pada ujung kabel UTP tujuanya agar kabel dapat kita pasang pada port LAN. Konektor RJ-45 harus dipasangkan pada ujung kabel UTP apabila tidak maka Kabel UTP tidak akan berguna.

#### 2.2 Langkah Pembuatan Kabel Tipe Straight

1. Kupas bagian ujung kabel UTP, kira-kira 2 cm.
2. Buka pilinan kabel, luruskan dan urutankan kabel sesuai standar kabel tipe straight.
3. Setelah urutannya sesuai standar, potong dan ratakan ujung kabel,
4. Masukan kabel yang sudah lurus dan sejajar tersebut ke dalam konektor RJ-45, dan
5. Pastikan semua kabel posisinya sudah benar dengan posisi sebagai berikut:
   - Orange Putih pada Pin 1.
   - Orange pada Pin 2.
   - Hijau Putih pada Pin 3.
   - Biru pada Pin 4.
   - Biru Putih pada Pin 5.
   - Hijau pada Pin 6.
   - Coklat Putih pada Pin 7.
   - Coklat pada Pin 8.
6. Masukkan konektor RJ-45 yang sudah terpasang dengan kabel tang crimping lalu tekan tang crimping dan pastikan semua pin (kuningan) pada konektor RJ-45 sudah _menggigit_ tiap-tiap kabel. biasanya akan terdengar suara _klik_, lakukan pada sisi yang lain.

#### 2.3 Langkah Pembuatan Kabel Tipe Crossover

1. Kupas bagian ujung kabel UTP, kira-kira 2 cm.
2. Buka pilinan kabel, luruskan dan urutankan kabel sesuai standar kabel tipe crossover.
3. Setelah urutannya sesuai standar, potong dan ratakan ujung kabel,
4. Masukan kabel yang sudah lurus dan sejajar tersebut ke dalam konektor RJ-45, dan
5. Pastikan semua kabel posisinya sudah benar dengan posisi sebagai berikut:
   Sisi Pertama
   - Orange Putih pada Pin 1.
   - Orange pada Pin 2.
   - Hijau Putih pada Pin 3.
   - Biru pada Pin 4.
   - Biru Putih pada Pin 5.
   - Hijau pada Pin 6.
   - Coklat Putih pada Pin 7.
   - Coklat pada Pin 8.
     Sisi Kedua
   - Hijau Putih pada Pin 1.
   - Hijau pada Pin 2.
   - Orange Putih pada Pin 3.
   - Biru pada Pin 4.
   - Biru Putih pada Pin 5.
   - Orange pada Pin 6.
   - Coklat Putih pada Pin 7.
   - Coklat pada Pin 8.
6. Masukkan konektor RJ-45 yang sudah terpasang dengan kabel tang crimping lalu tekan tang crimping dan pastikan semua pin (kuningan) pada konektor RJ-45 sudah _menggigit_ tiap-tiap kabel. biasanya akan terdengar suara _klik_, lakukan pada sisi yang lain.

### 3. Pengetesan Kabel UTP

#### 3.1 Alat Pengetesan

1. Cable Tester
   Cable Tester adalah alat untuk menguji hasil crimpingan kabel kita, kalau krimpingan kita salah maka lampu di Cable Tester ini tidak akan menyala dan kalau hasil crimpingan kita sudah benar maka lampu di Cable Tester akan menyala dengan otomatis.

#### 3.2 Cara Pengetesan Kabel

- Tipe Straight
  Masukan masing-masing ujung kabel (konektor RJ-45) ke masing2 port yang tersedia pada cable tester, nyalakan dan pastikan semua lampu LED menyala sesuai dengan urutan kabel yang kita buat.
- Tipe Crossover
  Masukan masing-masing ujung kabel (konektor RJ-45) ke masing2 port yang tersedia pada cable tester, nyalakan dan pastikan semua lampu LED menyala semua meskipun ada yang lompat-lompat.
