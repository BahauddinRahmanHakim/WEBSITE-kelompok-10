# UTS Pemrograman Web

Selamat datang di proyek `UTS Pemrograman Web'. Proyek ini merupakan tugas mata kuliah pemrograman web. Pada web kami anda akan menemukan fitur-fitur yang menarik dan responsive.

# Struktur HTML
Pada proyek ini kami susun dengan rapi sehingga memudahkan aksesbilitas pengguna, berikut merupakan penjelasan lebih lanjut dari struktur html nya:

1. Deklarasi Dokumen: Menggunakan <!DOCTYPE html> untuk menetapkan dokumen sebagai HTML5, memberikan panduan kepada browser untuk menampilkan konten dengan benar.
2. Elemen <html>: Menandakan awal dokumen, dengan atribut lang="en" yang menunjukkan bahwa bahasa konten adalah bahasa Inggris.
3. Bagian <head>:
  -Pengaturan Karakter: <meta charset="UTF-8"> memastikan dukungan karakter internasional.
  -Responsif: <meta name="viewport" content="width=device-width, initial-scale=1"> mengatur tampilan responsif di perangkat mobile.
  -Judul Halaman: Elemen <title> menentukan nama halaman yang muncul di tab browser.
  -Tautan CSS: <link rel="stylesheet" href="./style.css"> menghubungkan halaman dengan file CSS untuk styling.
4. Bagian <body>: Menyimpan konten yang terlihat oleh pengguna.
5. Header:
  -Navigasi: Terdiri dari elemen <nav> dan daftar terurut (<ul>), memuat link untuk mengakses halaman "Home" dan "INFO".
6. Carousel:
  -Kontainer: Ditempatkan dalam <div class="carousel">, berfungsi untuk menampilkan beberapa item secara dinamis.
  -Item: Setiap item memiliki gambar (<img>) dan konten terstruktur di dalam <div class="content">, yang mencakup:
    -Penulis: Nama penulis yang ditampilkan dalam <div class="author">.
    -Judul dan Topik: Diidentifikasi dalam elemen <div class="title"> dan <div class="topic">.
    -Deskripsi: Informasi mendalam mengenai item yang ditampilkan dalam <div class="des">.
    -Tombol Aksi: Dua tombol di dalam <div class="buttons"> untuk mengakses informasi lebih lanjut atau inspeksi item.
7. Thumbnail:
  -Gambaran Ringkas: Menyediakan tampilan lebih kecil dari item-item dalam carousel, dengan format serupa yang mencakup gambar dan deskripsi singkat.
8. Navigasi Arrows:
  -Tombol Navigasi: Tombol <button> untuk berpindah antar item dalam carousel, memudahkan pengguna untuk menjelajahi konten.
9. Script:
  -Interaktivitas: Menggunakan <script src="app.js"></script> untuk menambahkan fungsionalitas JavaScript yang meningkatkan interaksi pengguna di halaman.

# Desain CSS
Web kami menggunakan CSS untuk memberikan tampilan dan responsif dan mudah diakses. berikut merupakan penjelasan lebih lanjut dari CSS kami:

1. Import Font
  Menggunakan @import untuk mengimpor font Poppins dari Google Fonts.
2. Styling Umum untuk Body
  font-family: Mengatur font ke Poppins.
  background-color: Hitam (#000).
  color: Abu-abu terang (#eee).
  margin: 0 untuk menghilangkan margin default.
  font-size: 14px.
3. Header dan Navigasi
  Flexbox untuk layout horizontal pada daftar navigasi.
  Penghapusan bullet points dan padding default.
  Transisi warna pada link saat hover.
4. Carousel
  width: 100vw, min-height: 100vh untuk tampilan penuh.
  Item: Ditempatkan dengan posisi absolut untuk tumpang tindih.
  Gambar: Menggunakan object-fit: cover untuk proporsi yang baik.
5. Desain Tombol
  Padding dan background color untuk tombol.
  Tombol kedua memiliki latar belakang transparan dan border.
6. Thumbnail
  Flexbox untuk layout thumbnail.
  Gambar dengan border-radius untuk sudut membulat.
7. Navigasi Arrows
  Tombol bulat dengan border-radius: 50%.
  Transisi halus saat hover.
8. Animasi dan Efek
  Menggunakan @keyframes untuk efek tampil/hilang pada konten.
  Animasi progres waktu untuk menampilkan durasi carousel.
9. Media Query
  Menyesuaikan gaya untuk perangkat kecil (max-width: 768px) dengan mengubah padding dan ukuran font.

# Penggunaan Javascript
Javascript pada web kami digunakan untuk animasi gambar pada web kami.Kode JavaScript ini mengelola logika navigasi dan transisi dalam carousel, termasuk navigasi manual dengan tombol dan pengalihan otomatis antar slide. Ini memberikan pengalaman interaktif dan dinamis bagi pengguna.

1. Element selection
2. Event Handlers
3. Timing Variables
4. Auto Slide Functionality
5. Show Slider Function
6. Clearing Timeouts

# Tampilan Website
berikut merupakan link untuk mengakses proyek ini: 
(https://bahauddinrahmanhakim.github.io/WEBSITE-kelompok-10/index.html)

# Credits
Proyek ini disusun oleh 'Dicky Dippos Sihite', 'Bahauddin Rahman Hakim', dan 'Roberto Christian'.
Jika ada pertanyaan lebih lanjut silahkan menghubungi

[Dicky Dippos Sihite](GitHub : https://github.com/Dicky-Sihite)
[Bahauddin Rahman Hakim](GitHub : https://github.com/BahauddinRahmanHakim)
[Roberto Christian](GitHub : https://github.com/RobertoChristian)
