# Image

Image / gambar bisa digunakan untuk memperindah tampilan website yang kita buat.  
HTML mendukung penampilan gambar menggunakan tag `<img>`.  
Hampir semua format gambar yang didukung oleh Web Browser bisa ditampilkan di halaman web.

---

## Image Attribute

Tag `<img>` adalah **void element**, jadi tidak memiliki konten.  
Terdapat beberapa atribut yang bisa kita gunakan dalam tag `<img>`:

- **`src`** → digunakan untuk menentukan lokasi gambar yang akan ditampilkan, bisa menggunakan **Absolute URL** atau **Relative URL**.  
- **`alt`** → digunakan sebagai representasi teks atau tulisan alternatif jika gambar tidak dapat ditampilkan.  

**Contoh kode:**
```html
<html>
    <body>
        <h1>Belajar HTML Gambar</h1>
        <img src="020-gambar/gambar.jpg" alt="tidak senang">
    </body>
</html>
````

---

## Image Size

Secara default, ukuran gambar akan selalu ditampilkan sesuai ukuran aslinya.
Namun, kadang-kadang kita ingin mengubah ukuran gambar.

Untuk melakukan itu, kita bisa menggunakan **CSS** dengan atribut:

* **`width`** → mengatur lebar gambar.
* **`height`** → mengatur tinggi gambar.

Nilai dapat menggunakan satuan **px** (pixel), atau **%** untuk persentase dari ukuran asli.

**Contoh kode:**

```html
<html>
    <body>
        <h1>Belajar HTML Gambar</h1>
        <img style="width: 250px; height: 250px;" src="020-gambar/gambar.jpg" alt="tidak senang">
    </body>
</html>
```