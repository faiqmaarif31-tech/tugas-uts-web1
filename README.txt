BUKUKITA - APLIKASI PEMESANAN BUKU ONLINE
UTS PEMROGRAMAN WEB 1

1. STRUKTUR FOLDER
   tugas-uts-web1/
   |-- index.html              (halaman login)
   |-- dashboard.html
   |-- stok.html
   |-- tracking.html
   |-- checkout.html
   |-- css/
   |   |-- style.css
   |-- js/
   |   |-- script.js
   |   |-- data.js
   |-- img/
       |-- pengantar_komunikasi.jpg
       |-- manajemen_keuangan.jpg
       |-- kepemimpinan.jpg
       |-- mikrobiologi.jpg
       |-- paud_perkembangan.jpeg

2. CARA MENJALANKAN
   - Ekstrak folder tugas-uts-web1.
   - Buka folder menggunakan Visual Studio Code.
   - Jalankan index.html dengan browser (disarankan menggunakan ekstensi Live Server).
   - Login memakai salah satu akun berikut:
       Rina  : rina@gmail.com / rina123
       Agus  : agus@gmail.com / agus123
       Admin : siti@gmail.com / siti123

3. FITUR
   - Login dengan validasi data pengguna dari js/data.js.
   - Modal Lupa Password dan Daftar.
   - Dashboard dengan greeting berdasarkan waktu lokal.
   - Katalog lima buku dari dataKatalogBuku dan fitur pencarian.
   - Tambah data stok menggunakan JavaScript DOM.
   - Checkout: tambah/hapus item keranjang, ubah jumlah, hitung total, validasi data pemesan dan pembayaran.
   - Pesanan disimpan menggunakan localStorage browser.
   - Tracking berdasarkan dataTracking pada data.js dan nomor DO dari transaksi checkout.
   - Laporan pemesanan dan history transaksi ditampilkan pada dashboard.

4. NOMOR DO UNTUK UJI COBA TRACKING
   - 20230012
   - 20230013
   - Nomor DO baru akan muncul setelah membuat pesanan melalui halaman checkout.

5. CATATAN
   - Aplikasi ini merupakan simulasi front-end sesuai instruksi UTS, tidak memakai server atau database.
   - Data akun pada data.js merupakan data dummy dari soal.
   - Data transaksi baru disimpan pada localStorage browser yang digunakan.
   - File sampul sudah diletakkan di folder img dan nama file disesuaikan dengan properti cover pada data.js.
