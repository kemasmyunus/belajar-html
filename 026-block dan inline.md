# block dan inline
Di dalam HTML, semua element memiliki nilai display, tergantung dari jenis element yang
digunakan
Secara garis besar, ada dua nilai untuk display, block dan inline

## block
Element yang memiliki nilai display block, selalu dimulai dengan baris baru.
Web browser secara otomatis menambahkan jarak / margin sebelum dan setelah element
Dan element dengan nilai display block, selalu mengambil ukuran penuh yang tersedia, yag artinya
dia akan meregang dari kiri dan kanan
Contoh tag yang menggunakan nilai display block adalah :
h1-h6, p, header, body, ul, li, ol, table, form, dan lain-lain

## inline
Sedangkan dalam display inline, element tidak dimulai dengan baris baru
Selain itu dalam display inline, element hanya menggunakan ukuran seperlunya saja
Contoh tag yang menggunakan nilai display inline :
a, b, i, em, button, strong, input, dan lain-lain

## div
Div adalah salah satu tag di HTML yang memiliki nilai display block
Div biasanya digunakan sebagai container (wadah) untuk beberapa element HTML
Div banyak digunakan ketika kita ingin membedakan bagian-bagian dalam element HTML, misal
ada bagian menu, content, footer, header dan lain-lain
Biasanya semua itu dibungkus dalam Div

kode : div
``` html
<html>
    <body>
        <div id="menu" style="background-color:yellow;">
            <ul>
                <li>Beranda</li>
                <li>Artikel</li>
                <li>Media Sosial</li>
            </ul>
        </div>
        <div id="content" style="background-color:pink;">
            <h1>Judul Halaman</h1>
            <p>isi halaman</p>
        </div>
    </body>
</html>
```

## span
Jika Div menggunakan nilai display block, ada lagi tag span, yang menggunakan nilai display inline
Span biasa digunakan pada kasus kita ingin menggunakan display inline, misal kita mau membuat
tulisa Programmer Zaman Now, namun tiap kata berbeda warna
Hal itu tidak bisa dilakukan jika menggunakan p, karena p akan mengubah seluruh warna tulisan
Kita bisa gunakan span di tiap kata, agar bisa menambah style di tiap span

kode span
``` html
<html>
    <body>
        <h1>
            <span style="color:red;">Kemas</span>
            <span style="color:blue">WFH</span>
        </h1>
    </body>
</html>
```