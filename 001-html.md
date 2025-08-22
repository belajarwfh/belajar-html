# Penjelasan HTML

## Apa itu HTML?
**HTML (HyperText Markup Language)** adalah bahasa markup yang digunakan untuk membuat struktur dasar halaman web.  
Perlu diingat: **HTML bukanlah bahasa pemrograman**, melainkan bahasa markup.  
Artinya, HTML hanya mengatur **struktur dan isi** dari sebuah halaman web, bukan logika pemrograman.

HTML bekerja dengan menggunakan **tag** (markup) yang memberi tahu browser bagaimana cara menampilkan konten seperti teks, gambar, video, atau link.

---

## Bagaimana HTML bekerja?
Ketika kita mengakses sebuah website:
1. Browser akan mengirim **request (permintaan)** ke **web server**.
2. Web server mengirimkan **response (balasan)** berupa file HTML, CSS, JavaScript, gambar, atau file lain yang dibutuhkan.
3. Browser akan membaca file HTML tersebut, lalu menampilkannya dalam bentuk halaman web yang rapi.

Contoh sederhana:
- Jika kita membuka website `doraemon.jp`, maka browser akan mengirim request ke server di Jepang.
- Server akan mengirim file HTML (serta CSS, JS, gambar, dll) kembali ke browser kita.
- Browser menampilkan file tersebut sebagai halaman web Doraemon.

---

## Mengapa HTML penting?
Jika kita ingin membuat website, **HTML adalah dasar yang wajib dikuasai**.  
Namun biasanya, HTML dipadukan dengan:
- **CSS** → untuk mengatur tampilan (warna, ukuran, layout).
- **JavaScript** → untuk menambahkan interaktivitas (animasi, validasi form, dll).
- **PHP/Backend** → untuk mengolah data dan berhubungan dengan database.

Jadi, HTML adalah pondasi awal sebelum mempelajari teknologi web lainnya.

---

## Struktur Dasar HTML
Struktur dasar file HTML terbagi menjadi dua bagian utama:

1. **Head** → berisi informasi tentang halaman web (judul, metadata, link CSS/JS).
2. **Body** → berisi konten utama yang akan ditampilkan di browser (teks, gambar, video, dll).

Contoh sederhana file HTML:

```html
<html>
  <!-- Bagian Head -->
  <head>
    <title>Belajar HTML</title>
  </head>

  <!-- Bagian Body -->
  <body>
    <h1>Selamat Datang</h1>
    <p>Ini adalah contoh paragraf pada repo belajar-html.</p>
  </body>
</html>
````

---

## Penjelasan Tag HTML

Tag HTML selalu ditulis dengan tanda **siku** `< >`.

* **Opening tag** (tag pembuka): `<html>`
* **Closing tag** (tag penutup): `</html>`
* Semua konten diletakkan **di antara tag pembuka dan penutup**.

Contoh:

```html
<p>Ini adalah sebuah paragraf.</p>
```

* `<` → left-angle bracket
* `p` → tag name
* `>` → right-angle bracket
* `<p>` → opening tag (p = paragraph)
* `/` → forward slash
* `</p>` → closing tag
* `Ini adalah sebuah paragraf.` → isi konten

---

## Kesimpulan

* HTML adalah bahasa markup, bukan bahasa pemrograman.
* HTML membangun struktur dasar halaman web.
* Website biasanya menggunakan HTML, CSS, dan JavaScript secara bersama.
* Struktur HTML terdiri dari **head** dan **body**.
* Tag HTML selalu memiliki **pembuka** dan **penutup**.

HTML adalah langkah awal yang sangat penting sebelum belajar teknologi web lainnya seperti CSS, JavaScript, dan database.
