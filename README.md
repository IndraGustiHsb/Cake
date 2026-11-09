# Custom Cake Dashboard
Dashboard katalog cake bertema Premium Dark (navy, pink, ungu, cyan).

## Isi paket
- `index.html` — aplikasi lengkap.
- `assets/cake-placeholder.svg` — gambar default produk.
- `README.md` — petunjuk.

## Fitur
Tambah/edit/hapus cake; nama, kategori, harga, deskripsi, upload foto; pencarian; filter kategori; ringkasan katalog; grafik kategori; backup dan import JSON. Foto otomatis di-resize.

## Upload ke GitHub Pages
1. Buat repository bernama `CUSTOM-CAKE-DASHBOARD`.
2. Upload `index.html`, `README.md`, dan folder `assets` ke root repository.
3. Buka Settings → Pages.
4. Source: Deploy from a branch; Branch: `main`; Folder: `/(root)`.
5. Klik Save. Tunggu deploy. URL: `https://USERNAME.github.io/CUSTOM-CAKE-DASHBOARD/`.

## Penyimpanan
Aplikasi memakai IndexedDB browser (fallback Local Storage). Data dan foto yang ditambahkan hanya tersimpan pada browser/perangkat tempat input dilakukan, bukan di GitHub dan tidak tersinkron ke perangkat lain. Klik Backup JSON secara berkala. Untuk katalog bersama lintas perangkat, perlu backend/database online.

Nilai katalog adalah penjumlahan harga produk, bukan omzet transaksi.
