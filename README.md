# Nama : Aqil Munif Indyana
# NIM : 20220801525
# UTS JARINGAN KOMPUTER

# 1.	Jelaskan Menurut anda apa itu jaringan computer
 ## Jaringan komputer adalah kumpulan dua atau lebih perangkat komputer yang saling terhubung untuk berbagi data dan sumber daya, seperti file, printer, atau koneksi internet. Jaringan ini memungkinkan komunikasi antar perangkat dalam area yang sama (seperti jaringan lokal atau LAN) maupun jarak jauh (seperti jaringan luas atau WAN).

# 2.	Sebutkan Komponen OSI Layer dan Jelaskan apa itu OSI Layer
 ## OSI Layer (Open Systems Interconnection Layer) adalah model konseptual yang menguraikan bagaimana data dapat ditransfer dari satu perangkat ke perangkat lain dalam jaringan melalui lapisan-lapisan tertentu. OSI Layer terdiri dari 7 lapisan yang masing-masing memiliki fungsi tertentu untuk memudahkan komunikasi dan interoperabilitas antar perangkat dari berbagai vendor dan platform.
 ## Berikut adalah tujuh komponen OSI Layer :
 ## •	Physical Layer (Lapisan Fisik)
 ## •	Data Link Layer (Lapisan Data Link)
 ## •	Network Layer (Lapisan Jaringan)
 ## •	Transport Layer (Lapisan Transportasi)
 ## •	Session Layer (Lapisan Sesi)
 ## •	Presentation Layer (Lapisan Presentasi)
 ## •	Application Layer (Lapisan Aplikasi)

# 3.	Jelaskan Menurut anda apa itu DHCP Server?
  ## DHCP Server (Dynamic Host Configuration Protocol Server) adalah sebuah server yang bertugas secara otomatis memberikan alamat IP dan informasi konfigurasi jaringan lainnya kepada perangkat (client) yang terhubung ke jaringan. Dengan adanya DHCP server, administrator jaringan tidak perlu mengatur IP secara manual untuk setiap perangkat karena server ini akan mendistribusikannya secara dinamis.

# 4.	Jelaskan Menurut anda ap aitu DHCP Client?
 ## DHCP Client adalah perangkat dalam jaringan yang meminta alamat IP dan informasi konfigurasi jaringan lainnya dari DHCP Server secara otomatis. DHCP Client bisa berupa komputer, smartphone, printer, atau perangkat jaringan lainnya yang memerlukan alamat IP agar dapat terhubung ke jaringan dan berkomunikasi dengan perangkat lain.

# 5.	Jelaskan Menurut anda apa itu IP Class A, IP Class B dan IP Class C?
 ## • IP Class A:
   ## a. Digunakan untuk jaringan yang sangat besar, seperti penyedia layanan internet (ISP) atau perusahaan multinasional.
   ## b. Alamat dimulai dari 1.0.0.0 hingga 126.0.0.0.
   ## c. Di Class A, 8 bit pertama (oktet pertama) adalah bagian network (identitas jaringan), sementara 24 bit sisanya adalah bagian host.
   ## d. Mendukung sekitar 16 juta host (2^24 - 2 host) per jaringan.
   ## e. Contoh: 10.0.0.1 adalah IP dalam Class A.
 
 ## • IP Class B:
   ## a. Digunakan untuk jaringan menengah hingga besar, seperti kampus atau organisasi besar.
   ## b. Alamat dimulai dari 128.0.0.0 hingga 191.255.0.0.
   ## c. Di Class B, 16 bit pertama adalah bagian network, sementara 16 bit sisanya adalah bagian host.
   ## d. Mendukung sekitar 65.000 host (2^16 - 2 host) per jaringan.
   ## e. Contoh: 172.16.0.1 adalah IP dalam Class B.	

 ## • IP Class C:
   ## a. Digunakan untuk jaringan kecil, seperti jaringan kantor kecil atau jaringan rumah.
   ## b. Alamat dimulai dari 192.0.0.0 hingga 223.255.255.0.
   ## c. Di Class C, 24 bit pertama adalah bagian network, dan hanya 8 bit sisanya yang menjadi bagian host.
   ## d. Mendukung hingga 254 host (2^8 - 2 host) per jaringan.
   ## e. Contoh: 192.168.0.1 adalah IP dalam Class C.

# 6.	Jelaskan Menurut anda apa itu Firewall ?
 ## Firewall adalah sistem keamanan jaringan yang berfungsi sebagai penghalang atau penjaga yang mengontrol lalu lintas data antara jaringan internal (seperti jaringan kantor atau rumah) dan jaringan eksternal (seperti internet). Firewall memantau dan memfilter paket data yang masuk dan keluar berdasarkan aturan keamanan yang telah ditentukan, sehingga hanya lalu lintas yang diizinkan yang dapat melewati jaringan.

# 7.	Jelaskan Menurut anda apa itu NAT?
 ## NAT (Network Address Translation) adalah teknik yang digunakan dalam jaringan komputer untuk mengubah alamat IP sumber atau tujuan dalam paket data yang lewat melalui perangkat jaringan seperti router atau firewall. Tujuan utama NAT adalah untuk mengatasi kekurangan alamat IP publik yang tersedia dan memungkinkan banyak perangkat dalam jaringan lokal (LAN) untuk berbagi satu alamat IP publik ketika mengakses internet.

# 8.	Jelaskan Menurut anda apa itu Routing?
 ## Routing adalah proses pengiriman data dari satu titik ke titik lainnya dalam jaringan komputer. Proses ini melibatkan pemilihan jalur terbaik untuk paket data agar dapat mencapai tujuan mereka. Routing dilakukan oleh perangkat yang disebut router, yang bertugas untuk memeriksa alamat tujuan pada setiap paket data dan memutuskan jalur yang akan digunakan berdasarkan informasi yang ada dalam routing table

# 9.	Studi Kasus
 ## a.	Siapkan Peralatan yang Diperlukan:
   ## - Sebuah router
   ## - Kabel Ethernet
   ## - Sebuah laptop
   ## - Koneksi internet

 ## b.	Sambungkan Router ke Internet:
   ## - Colokkan kabel Ethernet dari sumber internet Anda (modem atau stopkontak dinding) ke port WAN (wide area network) pada router. Koneksi ini memungkinkan router untuk mengakses internet.
 
 ## c.	Atur Router:
   ## - Nyalakan router dan sambungkan ke sumber listrik.
   ## - Gunakan kabel Ethernet lainnya untuk menghubungkan laptop Anda ke salah satu port LAN (local area network) pada router.

 ## d.	Konfigurasi Pengaturan Router:
   ## - Buka browser web di laptop Anda dan masukkan alamat IP router di bilah alamat (umumnya 192.168.1.1 atau 192.168.0.1).
   ## - Masuk menggunakan nama pengguna dan kata sandi default yang diberikan bersama router (sering kali ditemukan pada stiker di router).
   ## - Ikuti panduan pengaturan router untuk mengonfigurasi koneksi internet. Anda mungkin perlu memasukkan detail seperti pengaturan ISP (Internet Service Provider) Anda.

 ## e.	Uji Koneksi:
   ## - Setelah router terkonfigurasi, uji koneksi internet di laptop Anda dengan membuka browser dan mengakses situs web apa pun.
   ## - Jika koneksi berhasil, berarti router telah berhasil terhubung ke internet dan laptop Anda terhubung ke router.

 ## f.	Atur Koneksi Nirkabel (Opsional):
   ## - Jika Anda ingin menghubungkan perangkat lain secara nirkabel, buka halaman pengaturan nirkabel router.
   ## - Atur nama jaringan Wi-Fi (SSID) dan kata sandi yang aman.
   ## - Simpan pengaturan dan hubungkan perangkat nirkabel Anda ke jaringan Wi-Fi yang baru.

 ## g.	Amankan Jaringan Anda:
  ## - Ubah kredensial login router default dengan sesuatu yang lebih aman.
  ## - Aktifkan enkripsi WPA3 (jika tersedia) untuk jaringan Wi-Fi Anda guna memastikan keamanan komunikasi nirkabel.
