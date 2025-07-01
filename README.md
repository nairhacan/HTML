Oke Nairha! Ini catatan lengkap dan jelas soal **dasar-dasar HTML** sampai tamat, disusun sebagai catatan belajar yang enak dibaca dan gampang diingat:

---

## 📘 Dasar-Dasar HTML (Catatan Lengkap)

### 1. Apa itu HTML?

* HTML (HyperText Markup Language) adalah **bahasa standar** untuk membuat dan menyusun halaman web.
* HTML bekerja dengan menyusun elemen-elemen seperti teks, gambar, video, dan link agar tampil rapi di browser.

---

### 2. Struktur Dasar HTML

Sebuah file HTML biasanya punya kerangka ini:

* `<html>`: Elemen pembungkus seluruh dokumen HTML.
* `<head>`: Bagian informasi (judul halaman, link CSS, dll).
* `<body>`: Semua konten yang ditampilkan di browser.

---

### 3. Elemen dan Tag

* **Tag pembuka**: `<p>`
* **Tag penutup**: `</p>`
* **Elemen lengkap**: `<p>Hello</p>`
* **Self-closing tag**: Tag yang tidak perlu ditutup, contoh: `<br>`, `<img>`

---

### 4. Tipe-Tipe Elemen Penting

#### 📌 Elemen Teks:

* `<h1>` sampai `<h6>`: Judul (semakin kecil angkanya, makin kecil ukurannya)
* `<p>`: Paragraf
* `<strong>`: Cetak tebal
* `<em>`: Cetak miring
* `<br>`: Ganti baris
* `<hr>`: Garis pemisah

#### 📌 Elemen Tautan:

* `<a href="url">Link</a>`: Untuk buat link

#### 📌 Elemen Gambar:

* `<img src="url" alt="teks alternatif">`: Menampilkan gambar

#### 📌 Elemen Daftar:

* `<ul>`: Unordered List (bulatan)
* `<ol>`: Ordered List (angka)
* `<li>`: List item

---

### 5. Atribut dalam HTML

Atribut memberi informasi tambahan ke elemen HTML.
Contoh:

```html
<a href="https://google.com" target="_blank">Google</a>
```

* `href`: Alamat tujuan
* `target="_blank"`: Buka di tab baru

---

### 6. Elemen Layout / Struktur

#### 📦 Elemen Umum:

* `<div>`: Wadah umum (block)
* `<span>`: Wadah teks kecil (inline)

#### 🧱 Elemen Semantik (lebih bermakna):

* `<header>`: Bagian atas
* `<nav>`: Navigasi
* `<main>`: Konten utama
* `<section>`: Seksi atau bagian
* `<article>`: Artikel mandiri
* `<aside>`: Sampingan (sidebar)
* `<footer>`: Bagian bawah

---

### 7. Formulir HTML

Form digunakan untuk input data dari pengguna.

Elemen penting:

* `<form>`: Wadah form
* `<input>`: Kolom isian
* `<textarea>`: Isian banyak baris
* `<select>` dan `<option>`: Dropdown
* `<button>`: Tombol

Contoh atribut penting:

* `type`: Jenis input (`text`, `password`, `email`, `submit`, dll)
* `placeholder`: Teks bayangan
* `value`: Nilai default

---

### 8. Komentar HTML

Digunakan untuk menulis catatan di dalam kode, tidak tampil di browser:

```html
<!-- Ini komentar -->
```

---

### 9. File dan Penamaan

* File HTML disimpan dengan ekstensi `.html`
* Nama file sebaiknya **tanpa spasi**, gunakan `-` atau `_`

---

### 10. Best Practice

* Gunakan tag semantik agar struktur web rapi dan SEO-friendly.
* Selalu tutup tag kecuali yang self-closing.
* Jaga struktur: head dan body harus rapi.
* Gunakan komentar untuk memudahkan revisi.
* Tulis HTML dengan indentasi agar mudah dibaca.

---

### 11. Penghubung ke CSS dan JavaScript

* Untuk styling: `<link rel="stylesheet" href="style.css">`
* Untuk skrip: `<script src="script.js"></script>`

---

### 12. Cara Menjalankan HTML

1. Buat file `.html` di editor (misal: VS Code)
2. Klik kanan → **Open with Live Server** (jika pakai ekstensi Live Server)
3. Atau buka file langsung di browser

---

Kalau kamu ingin versi PDF-nya juga nanti bisa aku bantu buatin.

Mau lanjut ke **CSS dasar** habis ini?
