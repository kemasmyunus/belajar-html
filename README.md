# Belajar HTML

## 1. Pengenalan HTML
HTML (HyperText Markup Language) adalah bahasa yang digunakan untuk membuat halaman web. HTML menggunakan elemen-elemen (tag) untuk menentukan struktur dari sebuah halaman web.

## 2. Struktur Dasar HTML
Berikut adalah contoh struktur dasar sebuah dokumen HTML:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Judul Halaman</title>
</head>
<body>
    <h1>Selamat Datang di HTML</h1>
    <p>Ini adalah paragraf pertama saya!</p>
</body>
</html>
```

## 3. Elemen Dasar HTML
Berikut beberapa elemen dasar dalam HTML:

### a. Heading (Judul)
Menggunakan tag `<h1>` hingga `<h6>` untuk membuat judul.
```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
```

### b. Paragraf
Menggunakan tag `<p>` untuk membuat paragraf.
```html
<p>Ini adalah paragraf.</p>
```

### c. Link (Tautan)
Menggunakan tag `<a>` untuk membuat hyperlink.
```html
<a href="https://www.google.com">Kunjungi Google</a>
```

### d. Gambar
Menggunakan tag `<img>` untuk menampilkan gambar.
```html
<img src="gambar.jpg" alt="Deskripsi Gambar">
```

### e. List (Daftar)
#### Ordered List (Daftar Berurut)
```html
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
</ol>
```

#### Unordered List (Daftar Tidak Berurut)
```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
</ul>
```

### f. Tabel
Menggunakan tag `<table>` untuk membuat tabel.
```html
<table border="1">
    <tr>
        <th>Nama</th>
        <th>Usia</th>
    </tr>
    <tr>
        <td>Ana</td>
        <td>25</td>
    </tr>
</table>
```

## 4. Formulir dalam HTML
Tag `<form>` digunakan untuk membuat formulir input pengguna.
```html
<form>
    <label for="nama">Nama:</label>
    <input type="text" id="nama" name="nama">
    <br>
    <input type="submit" value="Kirim">
</form>
```

## 5. HTML Semantik
HTML semantik membantu memberikan makna pada struktur halaman web.
```html
<header>
    <h1>Judul Situs</h1>
</header>
<nav>
    <ul>
        <li><a href="#">Beranda</a></li>
        <li><a href="#">Tentang</a></li>
    </ul>
</nav>
<section>
    <article>
        <h2>Judul Artikel</h2>
        <p>Isi artikel...</p>
    </article>
</section>
<footer>
    <p>Hak Cipta &copy; 2025</p>
</footer>
```
