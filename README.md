# Laporan Praktikum 3: CSS Dasar

Repository ini berisi hasil pelaksanaan Praktikum 3 mata kuliah **Pemrograman Web** di Universitas Pelita Bangsa. Praktikum ini membahas mengenai konsep dasar HTML, penerapannya dengan CSS Internal, Inline CSS, CSS Eksternal, serta penggunaan ID dan Class Selector.

---

## Ringkasan Langkah Praktikum

### 1. Membuat Dokumen HTML
Membuat file `lab2_css_dasar.html` dengan struktur dasar HTML5 yang mencakup bagian `<header>`, `<nav>`, dan kontainer utama `<div id="intro">` yang disiapkan dengan atribut ID dan Class.

### 2. Mendeklarasikan CSS Internal
Menambahkan tag `<style>` pada bagian `<head>` untuk memberikan aturan gaya internal (misalnya pengaturan `font-family`, batas `header`, serta warna judul `<h1>`).

### 3. Menambahkan Inline CSS
Menerapkan gaya secara langsung pada atribut `style` di dalam tag spesifik (misalnya `<p style="...">`) untuk mengubah tata letak dan warna teks khusus pada baris tersebut.

### 4. Membuat CSS Eksternal
Membuat file terpisah `style_eksternal.css` dan menautkannya ke dokumen HTML menggunakan tag `<link rel="stylesheet">` di bagian `<head>`. File ini berisi styling untuk komponen navigasi (`<nav>`) dan efek *hover*.

### 5. Menambahkan CSS Selector (ID & Class)
Menambahkan aturan gaya berbasis **ID Selector** (`#intro`) untuk membingkai area konten utama dan **Class Selector** (`.button`, `.btn-primary`) untuk membuat tampilan link menjadi tombol visual yang menarik.

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