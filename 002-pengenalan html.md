# Pengenalan HTML

## HTML
**HTML (HyperText Markup Language)** adalah bahasa markup yang digunakan untuk membuat struktur dasar dari sebuah halaman web.  
HTML mendeskripsikan susunan dan isi dari konten sebuah halaman.  

Selain HTML, ada juga teknologi lain yang biasa digunakan untuk melengkapi sebuah halaman web, seperti **CSS** untuk tampilan (style) dan **JavaScript** untuk interaksi. Namun, pada materi ini kita hanya akan berfokus pada HTML.  

HTML sendiri hanyalah kumpulan kode yang berisi informasi tentang halaman web. Kode tersebut akan dibaca oleh **Web Browser** untuk kemudian ditampilkan secara visual.

---

## Kode HTML
Untuk melihat kode HTML, kita bisa membuka sebuah website dengan web browser lalu menggunakan fitur **View Page Source**.  
Sebagai contoh, ketika kita membuka [https://www.github.com/](https://www.github.com/), kita bisa melihat kode HTML yang digunakan untuk membangun halaman tersebut.

---

## Tag
Kode HTML tersusun dari **tag**. Tag adalah instruksi dalam HTML yang biasanya memiliki pasangan pembuka dan penutup.  

Contoh tag untuk membuat paragraf adalah `<p>`. Berikut contohnya:

```html
<p>Hello World</p>
<p>Ini adalah tag paragraf</p>
````

Pada contoh di atas:

* `<p>` adalah **tag pembuka**
* `</p>` adalah **tag penutup**
* teks di dalamnya, seperti *Hello World*, disebut **konten**

Sebuah tag beserta isinya disebut sebagai **elemen**.

---

## Void Element

Tidak semua tag HTML memiliki pasangan pembuka dan penutup. Beberapa tag tidak membutuhkan konten, sehingga disebut **void element**.

Contohnya adalah tag `<br>` yang digunakan untuk membuat baris baru (line break). Karena tidak memiliki isi, tag ini bisa ditulis langsung sebagai `<br>` tanpa harus menggunakan penutup.

---

## Attribute

Elemen HTML dapat memiliki **atribut**, yaitu informasi tambahan yang diletakkan pada tag pembuka.

Sebagai contoh, untuk menampilkan gambar kita bisa menggunakan tag `<img>` dengan atribut `src` sebagai penunjuk lokasi file gambar:

```html
<img src="folder_gambar/file.jpg">
```

Atribut dapat digunakan pada elemen biasa maupun pada void element.

---

## HTML Tidak Case Sensitive

Penulisan tag dalam HTML tidak bersifat **case sensitive**, artinya huruf besar atau kecil tidak berpengaruh.
Sebagai contoh, `<p>` dan `<P>` akan berfungsi sama.

Namun, praktik terbaik adalah menuliskan tag menggunakan huruf kecil semua agar lebih konsisten dan mudah dibaca.

