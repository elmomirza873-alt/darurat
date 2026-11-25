DARURAT PWA - PETUNJUK PEMASANGAN

ISI PAKET
- index.html : aplikasi
- app.js : fungsi aplikasi
- manifest.webmanifest : identitas PWA
- sw.js : cache/offline
- icons : ikon aplikasi

CARA MENJALANKAN
1. Ekstrak ZIP.
2. Upload seluruh isi folder (bukan folder pembungkusnya) ke hosting yang mendukung HTTPS, misalnya GitHub Pages.
3. Buka alamat HTTPS tersebut di Chrome Android.
4. Pilih menu browser > "Tambahkan ke layar utama" atau "Install app".

CATATAN PENTING
- PWA perlu HTTPS untuk instalasi dan service worker; membuka index.html langsung dari file manager bukan cara pemasangan yang benar.
- Kontak/profil disimpan di localStorage browser pada perangkat tersebut.
- WhatsApp/SMS/telepon membuka aplikasi terkait; pengguna tetap perlu menekan kirim atau konfirmasi.
- Geolocation meminta izin browser dan bisa gagal jika GPS/jaringan tidak tersedia.
- Alarm audio hanya dapat berjalan ketika halaman aktif dan browser mengizinkan audio.
- Unggah bukti transfer versi ini hanya mencatat pengajuan secara lokal di perangkat. Tidak ada server, tidak ada pengiriman bukti kepada pemilik, tidak ada OCR/verifikasi bank, dan tidak ada aktivasi lisensi otomatis.
- Rekening Mandiri yang ditampilkan mengikuti detail yang sebelumnya diberikan pengguna: 1850004479140 atas nama BAYU RAHADIAN. Pastikan rekening ini memang rekening yang ingin digunakan sebelum aplikasi dipublikasikan.
- Karena tidak ada backend, status Premium dan masa aktif belum dapat dikelola dengan aman lintas perangkat. Jangan menjual langganan berbayar dengan mengandalkan status lokal ini.
- Fungsi SOS dasar sebaiknya diuji pada HP asli sebelum dipakai dalam keadaan darurat. PWA tidak menjamin berjalan ketika browser ditutup atau sistem menghentikan proses.

PRIVASI
Data kontak dan profil tersimpan pada browser perangkat ini. Jangan gunakan perangkat bersama tanpa menghapus data aplikasi. Versi ini belum menyediakan sinkronisasi cloud maupun penghapusan akun jarak jauh.
