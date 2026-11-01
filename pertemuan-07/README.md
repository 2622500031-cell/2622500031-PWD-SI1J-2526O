 # Pertemuan 7 (P7) - Pemrosesan Formulir dengan PHP, Validasi Sisi Peladen, dan PRG

Mata Kuliah: Pemrograman Web Dasar (IS205) | Semester Gasal 2026/2027
Nama / NIM: Verinda Viola / 2622500031

## B.1 Baseline P6
- Artefak P6 (index.php, style.css, script.js, img/) disalin ke pertemuan-07.
- Hasil pemeriksaan: tampilan, navigasi, foto profil, dan validasi JavaScript berfungsi.

## B.2 Pengujian Laragon
- Apache berjalan di Laragon.
- Halaman pertemuan-07 di localhost menampilkan hasil yang sama dengan pertemuan-06.
## B.3 Pemeriksaan Formulir
- Formulir contactForm di index.php memakai method="get" dan action="index.php".
- script.js menangani event submit dan memakai event.preventDefault().
## C.3 Menerima Data dengan $_GET
- Kode PHP $_GET['nama'] ditambahkan di bagian atas index.php.
- Tes ?nama=Andi menampilkan "Nama yang diterima: Andi".
- Tes ?nama=Budi%20Anduk menampilkan "Nama yang diterima: Budi Anduk".
- Tanpa parameter nama, tidak ada tulisan dan tidak ada error.
## C.4 Pengiriman Formulir dengan GET
- Menambahkan contactForm.submit(); di script.js setelah validasi berhasil.
- Data valid: halaman dimuat ulang, URL berisi parameter ?nama=...&email=..., dan tertampil "Nama yang diterima".
- Data kosong/tidak valid: pesan validasi muncul dan formulir tidak terkirim.
## E.1 Demonstrasi GET (indexGet.php)
- index.php disalin menjadi indexGet.php, action diubah ke indexGet.php, method tetap get.
- Tes: setelah klik Kirim, URL menjadi indexGet.php?nama=...&email=... dan tertampil "Nama yang diterima".