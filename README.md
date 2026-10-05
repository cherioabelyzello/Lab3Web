# Laporan Praktikum 3: CSS Dasar

Repository ini berisi hasil pelaksanaan Praktikum 3 mata kuliah **Pemrograman Web** di Universitas Pelita Bangsa. Praktikum ini membahas mengenai konsep dasar HTML, penerapannya dengan CSS Internal, Inline CSS, CSS Eksternal, serta penggunaan ID dan Class Selector.

---

## Ringkasan Langkah Praktikum

### 1. Membuat Dokumen HTML
Membuat file `lab2_css_dasar.html` dengan struktur dasar HTML5 yang mencakup bagian `<header>`, `<nav>`, dan kontainer utama `<div id="intro">` yang disiapkan dengan atribut ID dan Class.
<img width="1808" height="519" alt="1" src="https://github.com/user-attachments/assets/3c56a628-6ea3-456f-9404-67ceca55a663" />


### 2. Mendeklarasikan CSS Internal
Menambahkan tag `<style>` pada bagian `<head>` untuk memberikan aturan gaya internal (misalnya pengaturan `font-family`, batas `header`, serta warna judul `<h1>`).
<img width="1853" height="503" alt="2" src="https://github.com/user-attachments/assets/57c0a830-de5d-48d6-b6d1-64d4649b0bb1" />


### 3. Menambahkan Inline CSS
Menerapkan gaya secara langsung pada atribut `style` di dalam tag spesifik (misalnya `<p style="...">`) untuk mengubah tata letak dan warna teks khusus pada baris tersebut.

<img width="1901" height="467" alt="3" src="https://github.com/user-attachments/assets/84fbb1c9-7523-4c6f-bb76-11e8a5dcb567" />



### 4. Membuat CSS Eksternal
Membuat file terpisah `style_eksternal.css` dan menautkannya ke dokumen HTML menggunakan tag `<link rel="stylesheet">` di bagian `<head>`. File ini berisi styling untuk komponen navigasi (`<nav>`) dan efek *hover*.

<img width="929" height="535" alt="4" src="https://github.com/user-attachments/assets/6310b8cf-ed8f-4c45-8f94-809383ba6b4b" />



### 5. Menambahkan CSS Selector (ID & Class)
Menambahkan aturan gaya berbasis **ID Selector** (`#intro`) untuk membingkai area konten utama dan **Class Selector** (`.button`, `.btn-primary`) untuk membuat tampilan link menjadi tombol visual yang menarik.

<img width="1895" height="572" alt="5" src="https://github.com/user-attachments/assets/2d64e871-e71e-4ebd-9dc5-da2e7d607062" />


<img width="938" height="650" alt="6" src="https://github.com/user-attachments/assets/2879d62c-1872-4c13-b209-93259b57b1a5" />

---

## Jawaban Tugas & Pertanyaan Praktikum

1. **Perbedaan `h1 {...}` dan `#intro h1 {...}`:
   * `h1 {...}`: Menerapkan gaya ke **semua** elemen `<h1>` di seluruh halaman web.
   * `#intro h1 {...}`: Menerapkan gaya **hanya** pada elemen `<h1>` yang berada di dalam kontainer yang memiliki `id="intro"`.

2. **Prioritas Eksekusi CSS (Internal, Eksternal, Inline):**
   * CSS yang ditampilkan adalah **Inline CSS**, karena Inline CSS memiliki hierarki/spesifisitas paling tinggi dibanding Internal dan Eksternal CSS.

3. **Prioritas ID Selector vs Class Selector:**
   * Apabila satu elemen memiliki ID dan Class bersamaan, gaya dari **ID Selector** yang akan ditampilkan karena ID memiliki prioritas (*specificity level*) yang lebih tinggi daripada Class.

---

## Cara Menjalankan Project

1. Clone repository ini:
   ```bash
   git clone https://github.com/username/Lab3Web.git
   ```
2. Buka file `lab2_css_dasar.html` menggunakan peramban web (browser) pilihan Anda.
