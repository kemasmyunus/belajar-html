# Picture

Selain menggunakan tag **`<img>`** untuk menampilkan gambar di HTML, kita juga bisa menggunakan tag **`<picture>`**.
Keuntungan menggunakan `<picture>` adalah kita bisa menampilkan **gambar yang berbeda sesuai kondisi tertentu**, misalnya ukuran layar.

👉 Contoh:

* Jika layar **besar**, tampilkan gambar berukuran besar.
* Jika layar **kecil**, tampilkan gambar versi kecil (lebih ringan).

---

## Perbedaan `<img>` dan `<picture>`

* `<img>` adalah **void element** (tidak punya isi, hanya 1 tag tunggal).
* `<picture>` **bukan void element**, sehingga bisa berisi beberapa tag di dalamnya.

Di dalam `<picture>`, biasanya kita menambahkan:

* **`<source>`** → untuk menentukan gambar yang akan ditampilkan berdasarkan kondisi tertentu.
* **`<img>`** → sebagai gambar default (ditampilkan jika semua kondisi `<source>` tidak terpenuhi).

---

## Contoh Kode `<picture>`

```html
<html>
  <body>
    <h1>Belajar Picture</h1>

    <picture>
      <!-- Jika layar max 500px -->
      <source media="(max-width: 500px)" srcset="021-picture/gambar-green.jpg">

      <!-- Jika layar max 600px -->
      <source media="(max-width: 600px)" srcset="021-picture/gambar-black.jpg">

      <!-- Default gambar -->
      <img src="021-picture/gambar.jpg" alt="gambar" style="width:250px; height:250px;">
    </picture>

  </body>
</html>
```

---

## Atribut `media`

* Atribut **`media`** pada tag `<source>` berisi **media query CSS**.
* Media query digunakan untuk menentukan **kapan gambar tersebut ditampilkan**, biasanya berdasarkan ukuran layar.

👉 Lebih detail tentang media query bisa dipelajari di:
[MDN Web Docs - Media Queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries)