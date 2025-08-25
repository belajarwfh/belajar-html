# Instalasi dan Persiapan Membuat Website

## Apa yang Dibutuhkan?

Sebelum membuat website, ada beberapa hal yang perlu dipersiapkan:

1. **Browser**
   Digunakan untuk menampilkan (menjalankan) website yang kita buat.
   Umumnya menggunakan **Google Chrome**, tetapi bisa juga memakai **Firefox**, **Safari**, atau browser lain.

2. **Text Editor**
   Text editor adalah sebuah perangkat lunak (software) yang dirancang untuk membuat atau mengubah teks dalam format sederhana (plain text), bukan teks terformat seperti di aplikasi pengolah kata (misalnya Microsoft Word).

   Text editor yang umum digunakan untuk membuat website adalah:

   * **Visual Studio Code (VS Code)** → rekomendasi utama.
   * **Sublime Text** atau text editor lainnya.

   Jika menggunakan **Visual Studio Code**, sebaiknya instal ekstensi berikut:

   * **Live Server** → ekstensi untuk menjalankan file HTML di browser dengan auto-reload setiap kali file disimpan.
   * **Prettier** → ekstensi untuk merapikan kode otomatis (HTML, CSS, JavaScript, dll) agar lebih rapi dan konsisten.

---

## Persiapan File HTML Pertama

Hal pertama yang perlu dilakukan adalah memberi tahu browser bahwa file yang kita buat adalah **dokumen HTML**, dengan menuliskan deklarasi berikut di baris paling atas:

```html
<!DOCTYPE html>
```

Setelah itu, tuliskan struktur dasar HTML:

```html
<html>
  <head>
    <tittle>Hello World</tittle>
  </head>
  <body>

  </body>
</html>
```

---

## Menjalankan File HTML

Untuk melihat hasil file HTML di browser:

1. Klik kanan pada file di **VS Code**.
2. Pilih **Open with Live Server**, atau gunakan shortcut **Alt + L** lalu **Alt + O**.

---

## Tips Tambahan di VS Code

* Untuk menutup/menampilkan sidebar di VS Code: tekan **Ctrl + B**.
* Jika ada tanda bulat di tab atas file, itu berarti file **belum disimpan**.

---

## Contoh File HTML Sederhana

```html
<html>
  <head>
    <tittle>Hello World</tittle>
  </head>
  <body>
    Nama saya Kemas Myunus. <br>
    Ini adalah file HTML sederhana.
  </body>
</html>
```

---
