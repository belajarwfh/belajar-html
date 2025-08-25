# Installasi dan persiapan
## apa yang dibutuhkan untuk membuat website?
pertama, kita perlu menginstall browser yang akan digunakan untuk membuat website. umumnya menggunakan browser bernama chrome, tapi bisa juga pakai browser lain seperti firefox atau safari.
kedua, kita perlu install text editor, 

> text editor adalah sebuah software yang dirancang untuk membuat atau mengubah text dalam format sederhana atau teks biasa, bukan teks terformat seperti di aplikasi pengolah kata 

text editor yang umum digunakan adalah visual studio code. bisa juga pakai text editor lain seperti sublim.
kalau menggunakan visual studio code, perlu menginstall Ekstensi berikut :
1. live server -> ekstensi VS Code untuk menjalankan file HTML di browser dengan auto reload setiap kali file disimpan.
2. prettier -> ekstensi VS Code untuk merapikan kode otomatis (HTML, CSS, JS, dll) agar rapi dan konsisten.

## persiapan
hal pertama yang kita lakukan adalah memberi tau file kalau ini adalah file html dengan cara tulis : 
```html
<!DOCTYPE html>
```

lalu kemudian bisa diteruskan dengan menulis berdasarkan struktur htmlnya :
```html
<html>
  <head>
    <tittle>Hello World</tittle>
  </head>
  <body>

  </body>
</html>
```


Untuk menjalankannya adalah klik kanan, lalu klik “Open with live server “ atau Alt+L alt+o
Supaya sidebar vsc tertutup bisa pakai ctrl + b

Kalau ada tanda bulet diatas, berarti belum di save filenya.

Contoh : 
```html
<html>
<head>
	<tittle>Hello World</tittle>
</head>
	<body>
		Nama saya kemasmyunus
		Ini adalah file html sederhana
	</body>
</html>
```
