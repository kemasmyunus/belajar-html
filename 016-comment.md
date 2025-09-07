# Komentar di HTML

Komentar adalah **catatan tambahan** yang ditulis di dalam kode HTML. Komentar **tidak akan muncul** di halaman web yang dilihat oleh pengguna.

Biasanya komentar digunakan oleh **pengembang web** untuk:

* Memberi penjelasan tentang bagian kode tertentu
* Memberi catatan atau pengingat
* Menonaktifkan bagian kode tanpa menghapusnya

### Cara Menulis Komentar di HTML

Gunakan format berikut:

```html
<!-- Ini adalah komentar -->
```

Semua yang berada di dalam `<!--` dan `-->` tidak akan terlihat di halaman web, **meskipun berisi tag HTML**.

### Contoh Kode:

```html
<html>
  <body>
    <h1>Belajar HTML</h1>

    <!-- Ini adalah komentar <p> dan tidak akan muncul di halaman web </p> -->

    <p>Ini muncul</p>
  </body>
</html>
```

> Pada contoh di atas:
>
> * Komentar berisi tag `<p>`, tapi **tidak ditampilkan** di halaman.
> * Teks "Ini muncul" akan tampil di browser karena berada di luar komentar.