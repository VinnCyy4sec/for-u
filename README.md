# A Letter Just For Cey

Website confession romantis static berbasis HTML, CSS, dan Vanilla JavaScript. Tidak membutuhkan npm, build command, backend, database, atau music player.

## Jalankan lokal

Buka `index.html` langsung atau gunakan VS Code Live Server.

## Edit konten

Semua konten personal berada di `js/config.js`:

- Nama penerima.
- Satu foto Cey dan alt text.
- Pesan utama confession.
- Respons pilihan confession.
- Konfigurasi musik opsional yang sengaja tidak ditampilkan atau diaktifkan.

## Tambahkan foto

1. Masukkan satu foto ke `assets/images/cey-photo.jpg`.
2. Ubah `available: false` menjadi `available: true` di `js/config.js`.
3. Edit `alt` dan `caption` bila perlu.

Jika foto belum tersedia, website menampilkan placeholder elegan tanpa broken asset.

## Navigasi

Website memakai 6 halaman slideshow dengan transisi horizontal, tombol sebelumnya/selanjutnya, keyboard `ArrowLeft` dan `ArrowRight`, serta swipe kiri/kanan pada mobile. Konten panjang di halaman gombalan dapat scroll secara internal.

## GitHub Pages

1. Buat repository GitHub.
2. Upload isi folder ini dengan `index.html` di root repository.
3. Buka `Settings` → `Pages`.
4. Pilih `Deploy from a branch`.
5. Pilih branch `main` dan folder `/ (root)`.
6. Klik `Save`, tunggu deployment, lalu buka URL GitHub Pages.

Semua path lokal relatif. Website tetap static dan siap GitHub Pages.
