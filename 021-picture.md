# picture
Selain untuk menampilkan gambar menggunakan tag img, di HTML juga bisa menggunakan tag
picture untuk menampilkan gambar
Salah satu keuntungan menggunakan tag picture adalah, kita bisa menggunakan beberapa lokasi
gambar, dan bisa diatur sesuai dengan ukuran layar misalnya. Jadi ketika di layar besar, kita bisa
kirim gambar dengan ukuran besar, dan ketika di layar kecil, kita bisa kirim gambar yang ukuran
kecil

## Picture Content
Tag img adalah void element, sedangkan Tag picture bukan
Di dalam tag picture, kita bisa menambahkan tag source yang berisi lokasi gambar, dan tag img
sebagai default gambar ketika semua kondisi tag source tidak terpenuhi

Kode : Picture
``` html
<html>
    <body>
        <h1>belajar picture</h1>
        <picture>
            <source media="(max-width: 500px)" srcset="021-picture/gambar-green.jpg">
            <source media="(max-width: 600px)" srcset="021-picture/gambar-black.jpg">
            <img src="021-picture/gambar.jpg" alt="gambar" style="width:250px ; height:250px;">
        </picture>
    </body>
</html>
```

## Media Attribute
Atribut media di tag source berisikan media query CSS
Detailnya akan kita bahas nanti di kelas CSS
https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries