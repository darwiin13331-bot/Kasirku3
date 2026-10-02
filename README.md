# KasirKu Pro v3 — HTML

Aplikasi kasir berbasis HTML/CSS/JavaScript yang dapat dijalankan langsung di browser dan di-host menggunakan **GitHub Pages**.

## Menjalankan

Buka `index.html` di browser.

## Login demo

- Admin: `admin` / `admin123`
- Kasir: `kasir` / `kasir123`

## Deploy ke GitHub Pages

1. Buat repository baru di GitHub, misalnya `kasirku-pro`.
2. Upload `index.html`, `README.md`, dan `.nojekyll` ke root repository.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/ (root)`.
6. Simpan dan tunggu GitHub Pages selesai menerbitkan situs.

## Catatan data

Data aplikasi disimpan di `localStorage` browser. Data tidak otomatis tersinkron antar perangkat/browser. Gunakan fitur backup/restore di aplikasi untuk memindahkan data.

## Teknologi

HTML5, CSS3, dan JavaScript vanilla. Tidak membutuhkan server atau database untuk penggunaan lokal.
