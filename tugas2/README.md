# Dokumentasi Tugas 2 - Pemrograman Web

Halo! Ini adalah dokumentasi untuk Tugas 2 Pemrograman Web. Untuk tugas ini, saya membuat replika sederhana dari website Kebun Raya ITERA.

## 1. Kenapa Pakai Struktur Semantik?
Biar kodenya rapi dan lebih gampang dibaca (baik oleh developer lain maupun oleh mesin pencari kayak Google), saya menggunakan tag-tag semantik HTML5 di `index.html` dan `berita.html`. Ini rincian fungsinya:

*   `<header>`: Saya pakai buat bungkus logo, judul web (Kebun Raya ITERA), dan menu navigasi utama.
*   `<nav>`: Khusus buat tempat link menu biar terkelompok dengan jelas (misalnya link ke Beranda dan Berita).
*   `<main>`: Ini wadah utama semua isi konten halamannya. 
*   `<section>`: Buat misahin bagian-bagian besar. Contohnya, ada *section* khusus buat "Tentang Kebun Raya ITERA", *section* daftar penghargaan, dan *section* daftar harga paket.
*   `<article>`: Tag ini pas banget buat ngebungkus konten yang bisa berdiri sendiri. Saya pakainya untuk masing-masing item berita/penghargaan, dan artikel berita lengkap di halaman `berita.html`.
*   `<aside>`: Ini buat info tambahan atau semacam pengumuman di pinggir halaman. Saya isi dengan info pendaftaran maba dan pemberitahuan gangguan layanan.
*   `<footer>`: Bagian paling bawah website, isinya info kontak UPA Konservasi Flora Sumatera dan link kategori.

## 2. Tantangan dan Solusinya
Waktu ngerjain tugas ini lumayan ada beberapa *trial and error*:

*   **Tantangan:** Awalnya sempat bingung bedain kapan harus pakai `<section>` dan kapan pakai `<article>`. Terus, bingung juga gimana cara bikin *list* (poin-poin) di dalam sebuah tabel.
*   **Solusi:** Setelah nyari referensi dan eksperimen, akhirnya paham kalau `<article>` itu buat konten spesifik yang mandiri (kayak satu berita), kalau `<section>` itu buat tema yang lebih luas. Buat *list* di dalam tabel, solusinya ternyata gampang: tinggal masukin tag `<ul>` dan `<li>` langsung ke dalam tag `<td>`.

## 3. Hasil Validasi W3C
Kedua file HTML (`index.html` dan `berita.html`) udah dicek di W3C Validator dan alhamdulillah hasilnya lolos tanpa *error*.

*(Tempat untuk screenshot validasi)*
- **Screenshot Validasi `index.html`:**
  `![Validasi Index](masukkan_link_gambar_di_sini)`
- **Screenshot Validasi `berita.html`:**
  `![Validasi Berita](masukkan_link_gambar_di_sini)`

## 4. Link Hosting (GitHub Pages)
Tugas ini udah di-hosting di GitHub Pages sesuai format yang diminta. Semua link (*routing*) antar halaman juga udah berfungsi normal.

*   **URL:** [https://[username-github-kamu].github.io/pemweb/tugas2](https://[username-github-kamu].github.io/pemweb/tugas2)

*(Jangan lupa ubah `[username-github-kamu]` sama username asli kamu ya!)*# pemweb-tugas2
