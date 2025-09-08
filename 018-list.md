## Unordered List
Untuk membuat daftar tulisan, kita bisa menggunakan tag ul di HTML
Tiap daftar isi nya, kita bisa menggunakan tag li

Kode : Unordered List
``` html
<html>
    <body>
        <h2>daftar hobi</h2>
        <ul>
            <li>Badminton</li>
            <li>catur</li>
            <li>main game</li>
        </ul>
    </body>
</html>
```

## Ordered List
Jika kita ingin membuat daftar yang berurut (memiliki angka), kita bisa mengganti tag ul menjadi ol
Untuk daftar isi nya tetap sama menggunakan tag li

Kode : Ordered List
``` html
<html>
    <body>
        <h2>tahapan belajar html</h2>
        <ol>
            <li>belajar pengenalan web</li>
            <li>belajar html</li>
            <li>menjalankan web</li>
        </ol>
    </body>
</html>
```

## Ordered List Type
Pada kasus ketika kita menggunakan daftar yang berurut (ol), kita bisa mengubah format daftar
nya, defaultnya menggunakan angka (dimulai dari 1).
Kita bisa menambahkan attribute type di ol dengan nilai :
type=”1”, artinya daftar isi akan menggunakan angka (ini adalah defaultnya)
type=”A”, artinya daftar isi akan menggunakan huruf kapital
type=”a”, artinya daftar isi akan menggunakan huruf kecil
type=”I”, artinya daftar isi akan menggunakan angka romawi kapital
type=”i”, artinya daftar isi akan menggunakan angka romawi kecil

Kode : Ordered List Type
``` html
<html>
    <body>
        <h2>tahapan belajar html</h2>
        <ol type="I">
            <li>belajar pengenalan web</li>
            <li>belajar html</li>
            <li>menjalankan web</li>
        </ol>
    </body>
</html>
```