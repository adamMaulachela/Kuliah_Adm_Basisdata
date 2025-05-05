# Modul Pre-Praktikum

Modul ini disajikan sebagai penyegaran kepada mahasiswa agar lebih mudah mengenal tools pendukung SQL yang akan digunakan pada mata kuliah ini. Khususnya pada pengenalan MySQL dan MySQL Workbench sebagai editor. 

## Pengenalan MySQL
MySQL yang sering disebut sebagai 'MY-ES-KYOO-EL' merupakan manajemen basis data khususnya pada data terstruktur. Bersifat *open-source* dan menggunakan bahasa pemrograman berupa SQL (sikuel) *Structure Query Language*. 

### Fungsi, cara Kerja, Kelebihan, dan Kekurangan MySQL
Fungsi utama dari MySQL adalah manajemen data dalam database agar menghasilkan informasi yang bermanfaat, menggunakan bahasa SQL. Selain itu berikut ini adalah beberapa fungsi lainnya yang dimiliki oleh MySQL, yaitu : 
1. **Penyimpanan data relasional**
   
    Database MySQL menggunakan model relasional untuk menyimpan data, yang memungkinkan pengorganisasian informasi berdasarkan tabel. Sistem memungkinkan data tersimpan secara sistematis sehingga lebih mudah untuk diakses dan dicari.
2. **Manajemen Database**

    MySQL menawarkan fitur beragam untuk manajemen basis data, seperti pembuatan, pengubahan, dan penghapusan database serta tabel. Hal ini memberikan fleksibilitas dalam mengatur dan menyesuaikan struktur data sesuai kebutuhan.
3. **Manipulasi Data**

    Kemampuan mengubah data berdasarkan instruksi tertentu menjadi kelebihan MySQL. Tampilan tabel dan informasi dalam basis data dapat diperbarui, dihapus, atau ditambahkan menggunakan perintah SQL.

4. **Replikasi Data**

    MySQL mendukung replikasi data yang memungkinkan sinkronisasi satu salinan basis data ke server lain. Fungsi ini ideal dalam membangun sistem yang membutuhkan redundansi dan ketersediaan tinggi.

5. **Backup dan Restore**

    MySQL menawarkan fitur backup dan pemulihan, yang memastikan data dapat dikembalikan ke keadaan awal jika terjadi kesalahan atau kehilangan. Hal ini memberikan jaminan keamanan tambahan bagi pengguna.
6. **Penyimpanan dan Pencarian Teks**

    Penyimpanan dan pencarian teks di database MySQL menjadi lebih mudah karena adanya dukungan fungsi text search. Pengguna dapat mengimplementasikan fitur pencarian yang efisien dalam aplikasi mereka.

MySQL **bekerja dengan menerima dan mengeksekusi perintah SQL dari pengguna**. Ketika sebuah permintaan diajukan, sistem akan memproses kueri tersebut dan mengakses data yang diperlukan dari basis data. Selanjutnya data akan ditampilkan ke layar penggunßa.

![Cara Kerja MySQL](https://dwblog-ecdf.kxcdn.com/wp-content/uploads/2021/04/cara-kerja-MySQL.jpg)

sumber : [dewaweb.com](https://dewaweb.com)

MySQL memanfaatkan sistem manajemen transaksional untuk menjaga keakuratan data, serta memastikan bahwa setiap perubahan memenuhi standar konsistensi dan integritas data.

**Kelebihan MySQL**

* **Open source**: MySQL tersedia secara gratis dan dapat diubah sesuai kebutuhan pengguna.
* **Komunitas besar**: Memiliki dukungan komunitas yang luas yang memudahkan pengguna saat mencari solusi bagi permasalahan teknis.
* **Portabilitas** : Dapat berjalan di berbagai platform dan sistem operasi.
* **Keamanan data** : Memiliki fitur keamanan tingkat tinggi yang melindungi data sensitif.
* **Performa tinggi** : MySQL berperforma tinggi dan dapat menangani volume data besa. Saat data diakses secara bersamaan juga tidak ada penurunan performa yang signifikan.


**Kekurangan MySQL**

* **Fitur terbatas pada versi gratis** : Tidak semua fitur canggih tersedia dalam versi gratis, kamu harus melakukan upgrade untuk bisa menikmatinya.
* **Transaksi data besar** : Memerlukan pengaturan lebih kompleks untuk mengelola transaksi data yang sangat besar.
* **Kurangnya standardisasi penuh** : Beberapa fitur hanya tersedia secara eksklusif di MySQL dan bukan merupakan standar SQL.


## Pengenalan MySQL Workbench
MySQL Workbench adalah **perangkat lunak visual yang berfungsi sebagai GUI (*Graphical User Interface*) untuk mengelola database MySQL**. Ini menyediakan alat yang lengkap untuk pengembangan SQL, pemodelan data, dan administrasi server, termasuk konfigurasi, manajemen pengguna, dan pencadangan

Fungsi dari MySQL Workbench adalah sebagai berikut : 

* **Pengembangan SQL** : Fungsionalitas ini menyediakan kemampuan untuk mengeksekusi kueri SQL, membuat dan mengelola koneksi ke server basis data menggunakan Editor SQL bawaan.
* **Pemodelan Data (Desain)** : Fungsionalitas ini memungkinkan Anda membuat model skema basis data secara grafis, melakukan rekayasa balik dan maju antara skema dan basis data langsung, serta mengedit semua aspek basis data Anda menggunakan Editor Tabel yang komprehensif.
* **Administrasi Server** : Fungsionalitas ini memungkinkan Anda untuk mengelola instans server MySQL dengan mengelola pengguna, melakukan pencadangan dan pemulihan, memeriksa data audit, melihat kesehatan basis data, dan memantau kinerja server MySQL.
* **Migrasi Data** : Fungsionalitas ini memungkinkan Anda melakukan migrasi dari Microsoft SQL Server, Microsoft Access, dan tabel, objek, serta data RDBMS lainnya ke MySQL.
* **Dukungan MySQL Enterprise** : Fungsionalitas ini menyediakan dukungan untuk produk Enterprise seperti MySQL Enterprise Backup, MySQL Firewall, dan MySQL Audit.


Lembar kerja utamna dari aplikasi MySQL Workbench tersaji pada gambar dibawah ini : 

![Aplikasi MySQL Workbench](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/10/m5.png)

Terdapat empat panel utama yaitu : 
1. **Navigation Pane** : Panel Navigasi (Navigation Pane) pada MySQL Workbench berfungsi sebagai jendela utama untuk menjelajahi dan mengakses semua objek database, seperti tabel, tampilan, prosedur, dan lain-lain. Panel ini ditampilkan di sisi kiri jendela Workbench dan memungkinkan pengguna untuk mengelola dan memodifikasi database dengan mudah
2. **Query Pane** : Query pane pada MySQL Workbench adalah area di mana Anda mengetik dan mengeksekusi query SQL
3. **Output and Action Output Pane** : "Output Pane" adalah area di bagian bawah jendela yang menampilkan berbagai jenis output, termasuk keluaran dari kueri SQL, hasil dari eksekusi script, dan pesan kesalahan. "Action Output" adalah salah satu bagian dari "Output Pane" yang khusus menampilkan teks yang muncul di dalam blok kode, seperti keluaran kesalahan, hasil eksekusi kode, atau informasi status perintah
4. **SQL Additions Pane** : SQL Additions pane pada MySQL Workbench digunakan untuk memberikan berbagai fungsi dan fitur tambahan terkait SQL untuk memudahkan pengguna dalam membuat dan mengelola kueri SQL. Pane ini berisi berbagai fungsi seperti `SUM()`, `AVG()`, `COUNT()`, `MAX()`, `MIN()` yang dapat digunakan untuk melakukan perhitungan dan analisis data


## Memulai MySQL
Untuk memulai menggunakan MySQL, terlebih dahulu kita harus memastikan bahwa service MySQL tersedia dalam komputer. Service MySQL ini dapat menggunakan sebuah perangkat lunak seperti XAMPP yang menyediakan web server open source dan juga service MySQL. XAMPP sendiri merupakan akronim X (lintas pltform), A (Apache web server), M (MySQL/MariaDB), P (PHP), P (Perl). Setelah melakukan instalasi XAMPP selanjutnya kita dapat membuka XAMPP Control Panel, untuk menjalankan service MySQL seperti pada gambar dibawah ini
![XAMPP Control Panel](https://phpgurukul.com/wp-content/uploads/2023/02/xampp-control-panel-1.png)

Jika service MySQL sudah dalam status `running`, maka selanjutnya untuk menggunakannya kita dapat memanfaatkan dua cara yaitu melalui terminal atau MySQL Workbench. Untuk yang pertama melalui terminal atau CMD (Windows). 

### Akses MySQL Melalui Terminal
Langkah pertama kita adalah dengan membuka terminal atau CMD jika Operating System anda adalah Windows seperti yang tersaji pada gambar dibawah ini:

![CMD](https://upload.wikimedia.org/wikipedia/commons/b/b3/Command_Prompt_on_Windows_10_RTM.png)



### Akses MySQL Melalui MySQL Workbench