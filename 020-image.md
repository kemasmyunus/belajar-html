# Image
Image / gambar bisa digunakan untuk memperindah tampilan website yang kita buat
HTML mendukung untuk menampilkan gambar dengan tag img
Hampir semua format gambar yang didukung oleh Web Browser, bisa ditampilkan di halaman web
HTML

## Image Attribute
Tag img adalah void element, jadi tidak memiliki konten
Terdapat beberapa atribut yang bisa kita gunakan dalam tag img
Attribute src yang digunakan untuk menentukan lokasi gambar yang mau ditampilkan, bisa
menggunakan Absolute URL atau Relative URL
Attribute alt yang digunakan sebagai representasi text atau tulisan untuk gambar

Kode : Image
``` html
<html>
    <body>
        <h1>belajar html gambar</h1>
        <img src="020-gambar/gambar.jpg" alt="tidak senang">
    </body>
</html>
```
## Image Size
Secara bawaan default, ukuran gambar akan selalu ditampilkan sesuai aslinya
Kadang-kadang, kita ingin mengubah ukuran gambarnya
Untuk melakukan itu, kita perlu batuan CSS
Kita bisa gunakan attribute CSS :
width untuk mengubah ukuran lebar
height untuk mengubah ukuran tinggi
Kita bisa gunakan satuan px (pixel), atau % untuk persentase dari ukuran asli

Kode : Image Size
``` html
<html>
    <body>
        <h1>belajar html gambar</h1>
        <img style="width: 250px; height: 250px;" src="020-gambar/gambar.jpg" alt="tidak senang">
    </body>
</html>
```