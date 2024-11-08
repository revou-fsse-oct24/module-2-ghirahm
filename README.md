# Sky Cast - Pocket Forecast for Every Step

![Skycast Logo](asset/logo.png)

Sky Cast adalah aplikasi web yang menyediakan cara yang mudah bagi pengguna untuk mendapatkan perkiraan cuaca untuk minggu yang akan datang. Aplikasi ini mencakup tautan navigasi, pembaruan berita cuaca, dan formulir umpan balik untuk saran pengguna.

Sky Cast dapat diakses melalui https://revou-fsse-oct24.github.io/module-2-ghirahm/

## HTML Tags yang Digunakan

Berikut adalah daftar tag HTML yang digunakan dalam kode ini beserta fungsinya:

- `<html>`: Elemen root yang berisi semua elemen HTML lainnya.
- `<head>`: Berisi informasi meta tentang dokumen HTML, seperti judul dan karakter set.
- `<meta charset="UTF-8">`: Menentukan pengkodean karakter untuk dokumen HTML (UTF-8).
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Memastikan skala yang tepat di perangkat seluler.
- `<title>`: Mengatur judul halaman web yang ditampilkan di tab browser.

### Struktur Badan Utama

- `<body>`: Konten utama dokumen HTML.
  
  - `<header>`: Berisi konten header halaman, termasuk:
    - `<img>`: Menampilkan logo situs web dengan atribut `src` dan `alt` untuk sumber gambar dan teks alternatif.
    - `<nav>`: Mengelompokkan tautan navigasi dalam daftar tak terurut.
    - `<ul>`: Membuat daftar tak terurut untuk item navigasi.
    - `<li>`: Mendefinisikan item daftar individu dalam bilah navigasi.
    - `<a>`: Membuat hyperlink untuk navigasi antar bagian seperti "Home," "Article," dan "About."

### Bagian Konten

- `<main>`: Membungkus konten utama halaman web.

  - `<section>`: Digunakan untuk mengelompokkan konten menjadi berbagai bagian:
    - `#banner-home`: Berisi pesan sambutan untuk Sky Cast.
    - `#form-section`: Mengandung formulir pencarian di mana pengguna dapat memasukkan lokasi untuk mendapatkan perkiraan cuaca.
    - `#news-article`: Berisi artikel dengan berita cuaca terbaru dan tautan ke artikel lengkap.
    - `#form-suggestion`: Formulir umpan balik di mana pengguna dapat mengirimkan saran.

### Elemen Formulir

- `<form>`: Membuat formulir untuk mengumpulkan input pengguna.
  - `<label>`: Mendefinisikan label untuk bidang formulir, seperti "Region" dan "Suggestion."
  - `<input>`: Menerima berbagai jenis input pengguna, seperti teks, tombol radio, dan tombol kirim.
  - `<textarea>`: Menyediakan area input multi-baris untuk pengguna mengetik saran.
  - `<button>` dan `<input type="submit">`: Keduanya digunakan untuk mengirimkan formulir.

### Footer

- `<footer>`: Berisi informasi footer, termasuk nama aplikasi dan hak cipta.
