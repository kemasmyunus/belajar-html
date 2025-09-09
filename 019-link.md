# link
Saat membuat Web, biasanya kita akan membuat banyak sekali halaman HTML
Untuk berpindah dari satu halaman ke halaman lain, kita biasanya jarang melakukannya secara
manual dengan cara mengetikkannya di search bar Web Browser
HTML memiliki ﬁtur Link (Tautan), dimana kita bisa meng-klik Link tersebut, dan berpindah ke
halaman HTML lain
Link tidak harus dalam bentuk Text, Link juga bisa dalam bentuk Gambar misalnya (yang akan kita
bahas di materi Image)

## tag a
Untuk membuat Link di HTML, kita bisa menggunakan tag a
Isi konten tag a adalah isi dari tampilan Link, bisa Text atau yang lainnya
Tag a memiliki attribute href, yang berisi lokasi tujuan Link tersebut
Tag a juga memiliki attribute target, yang digunakan sebagai target jendela Web Browser, kita bisa
gunakan nilai :
target=”_self”, artinya halaman akan ditampilkan di halaman yang sama, ini adalah bawaan default
target=”_blank”, artinya halaman akan ditampilkan di jendela baru di Browser
Tag a juga memiliki attribute title, untuk menuliskan judul yang keluar ketika mouse berada di atas
Link tersebut

Kode : Link
``` html
<html>
    <body>
        <h1>Belajar link</h1>
        <ul>
            <li><a href="https://instagram.com/kemasmyunus" target="_blank">Instagram</a></li>
            <li><a href="https://github.com/kemasmyunus" target="_blank">Github</a></li>            
        </ul>
    </body>
</html>
```

## Absolute URL
Saat kita menulis halaman tujuan dari href di Link, kita bisa menggunakan absolute URL
Absolute URL merupakan alamat lengkap sebuah tujuan Link
Dalam absolute URL, kita wajib menuliskan seluruh detail domain dan halaman yang dituju, misal
https://instagram.com/kemasmyunus
https://github.com/kemasmyunus
Kelebihan menggunakan Absolute URL adalah, kita bisa membuat Link menuju domain yang
berbeda dengan website yang kita buat

## Relative URL
Relative URL adalah lokasi href dimana tetap menggunakan domain website saat ini
Relative URL memiliki dua format, bisa diawali dengan /, atau tidak diawali dengan /
Misal sekarang kita berada di halaman http://127.0.0.1/belajar-link/index.html , lalu kita memiliki
link sebagai berikut :
hello.html, artinya akan menuju ke http://127.0.0.1/belajar-link/hello.html
/hello.html, artinya akan menuju ke http://127.0.0.1/hello.html
pzn/hello.html, artinya akan menuju ke http://127.0.0.1/belajar-link/pzn/hello.html


Kode : Relative URL
``` html
<html>
    <body>
        <h1>Belajar Relative URL</h1>
        <ul>
            <li><a href="hello.html">hello.html</a></li>
            <li><a href="yns/index.html">yns/index.html</a></li>
        </ul>
    </body>
</html>
```

## Bookmark
Pada kasus halaman web yang sangat panjang, ada bagusnya kita menggunakan Bookmark
Bookmark adalah link yang bisa digunakan untuk menampilkan HTML element dengan id tertentu
Bookmark menggunakan # pada href, misal jika kita menggunakan index.html#eko, artinya ketika
membuka halaman index.html, maka Web Browser akan otomatis menampilkan pada posisi HTML
Element dengan id eko
Jika kita ingin membuat link di halaman HTML itu sendiri, kita bisa langsung buat Link dengan href
langsung berisi #bookmark nya

Kode : Bookmark di Halaman Sendiri
``` html
<html>
    <body>
        <h1>daftar isi</h1>
        <ul>
            <li><a href="#judul1">Judul 1</a></li>
            <li><a href="#judul2">Judul 2</a></li>
            <li><a href="#judul3">Judul 3</a></li>
        </ul>

        <h1 id="#judul1">Judul 1</h1>
        <p>artikel</p>
        <p>artikel</p>
        <p>artikel</p>
    </body>
</html>
```

Kode : Bookmark ke Halaman Lain
``` html
<html>
    <body>
        <h1>daftar isi</h1>
        <ul>
            <li><a href="019-link-bookmark-dihalaman-sendiri.html#judul1">Judul 1</a></li>
            <li><a href="019-link-bookmark-dihalaman-sendiri.html#judul2">Judul 2</a></li>
            <li><a href="019-link-bookmark-dihalaman-sendiri.html#judul3">Judul 3</a></li>
        </ul>
    </body>
</html>
```