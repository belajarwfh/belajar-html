# Penjelasan HTML

## Apa itu HTML?

**HTML (HyperText Markup Language)** adalah bahasa markup yang digunakan untuk membuat struktur dasar halaman web.

> ⚠️ Perlu diingat: **HTML bukanlah bahasa pemrograman**, melainkan **bahasa markup**.
> Artinya, HTML hanya mengatur **struktur dan isi** dari sebuah halaman web, bukan logika pemrograman.

HTML bekerja dengan menggunakan **tag** (markup) yang memberi tahu browser bagaimana cara menampilkan konten seperti teks, gambar, video, atau link.

---

## Bagaimana HTML Bekerja?

Ketika kita mengakses sebuah website:

1. **Browser** (contoh: Chrome, Firefox) akan mengirim **request** (permintaan) ke **web server**.
2. **Web server** mengirimkan **response** (balasan) berupa file HTML, CSS, JavaScript, gambar, atau file lain yang dibutuhkan.
3. Browser membaca file HTML tersebut, lalu menampilkannya dalam bentuk halaman web.

Contoh sederhana:

* Jika kita membuka website `doraemon.jp`, maka browser akan mengirim request ke server di Jepang.
* Server mengirim file HTML (serta CSS, JS, gambar, dll) kembali ke browser kita.
* Browser menampilkan file tersebut sebagai halaman web Doraemon.

---

## Mengapa HTML Penting?

Jika kita ingin membuat website, **HTML adalah dasar yang wajib dikuasai**.

Namun, HTML biasanya dipadukan dengan:

* **CSS (Cascading Style Sheets)** → mengatur tampilan (warna, ukuran, layout).
* **JavaScript** → menambahkan interaktivitas (animasi, validasi form, dll).
* **PHP / Backend language** → mengolah data dan berhubungan dengan database.

Jadi, HTML adalah pondasi awal sebelum mempelajari teknologi web lainnya.

---

## Struktur Dasar HTML

Struktur dasar file HTML terbagi menjadi dua bagian utama:

1. **Head** → berisi informasi tentang halaman web (judul, metadata, link CSS/JS).
2. **Body** → berisi konten utama yang ditampilkan di browser (teks, gambar, video, dll).

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
```

---

## Penjelasan Tag HTML

Tag HTML selalu ditulis dengan tanda **siku** `< >`.

* **Opening tag** (tag pembuka): `<html>`
* **Closing tag** (tag penutup): `</html>`
* Konten diletakkan **di antara tag pembuka dan penutup**.

Contoh:

```html
<p>Ini adalah sebuah paragraf.</p>
```

Keterangan:

* `<` → left-angle bracket (kurung siku kiri)
* `p` → tag name (nama tag)
* `>` → right-angle bracket (kurung siku kanan)
* `<p>` → opening tag (p = paragraph)
* `/` → forward slash (garis miring)
* `</p>` → closing tag (penutup tag)
* `Ini adalah sebuah paragraf.` → isi konten

---
