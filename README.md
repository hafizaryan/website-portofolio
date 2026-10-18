# Website Portofolio - Hafiz Aryan Siregar

Repositori ini berisi kode sumber website portofolio pribadi Hafiz Aryan Siregar. Halaman utama pada repositori ini (`index.html`) berfungsi sebagai halaman pengalihan (redirect) ke situs portofolio aktif di https://hafizaryan.github.io, sedangkan isi portofolio lengkapnya tersedia pada halaman-halaman di dalam repositori ini.

## Fitur

- **Intro**: perkenalan singkat pemilik portofolio.
- **About**: informasi latar belakang, minat, dan pengalaman.
- **Works**: daftar proyek yang pernah dikerjakan.
- **Gallery**: galeri foto kegiatan dan proyek, ditampilkan dengan slider Swiper.js.
- **Certificates**: halaman khusus sertifikat (`certificate.html`).
- **Link**: halaman daftar tautan (`link.html`).
- **Contact**: formulir kontak untuk menghubungi pemilik situs.

## Teknologi

- HTML5 untuk struktur halaman
- CSS3 untuk styling dan layout
- JavaScript untuk interaktivitas dan animasi
- Swiper.js untuk slider galeri
- Font Awesome untuk ikon
- Google Fonts untuk tipografi

## Struktur Folder

- `index.html` - halaman pengalihan ke hafizaryan.github.io
- `certificate.html` - halaman sertifikat
- `link.html` - halaman daftar tautan
- `assets/` - berkas pendukung situs
- `css/` - berkas stylesheet
- `js/` - berkas JavaScript
- `images/` - berkas gambar
- `public/` - berisi `_redirects` untuk aturan redirect saat deploy
- `site.webmanifest` - manifest aplikasi web
- `LICENSE` - lisensi MIT

## Cara Menjalankan

Situs ini statis dan tidak membutuhkan proses build.

1. Clone repositori ini.
2. Jalankan server statis sederhana, contohnya `python -m http.server 8000` atau `npx serve .`, lalu buka `http://localhost:8000` di browser.
3. Cara paling sederhana, buka berkas `index.html` langsung di browser.

## Lisensi

MIT, lihat berkas `LICENSE`.
