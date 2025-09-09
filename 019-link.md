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
