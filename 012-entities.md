## Reserved Characters
Beberapa karakter sudah dipesan oleh HTML, sehingga kita tidak bisa gunakan pada tulisan teks
biasa, contoh karakter <, / atau >
Oleh karena itu, jika kita memaksakan menuliskan hal tersebut di teks paragraf misal, secara
otomatis halaman HTML akan error / rusak / tidak sesuai dengan yang kita mau

Kode : HTML Reserved Characters
``` html
<html>
    <body>
        <h1>Belajar <HTML></h1>
    </body>
</html>
```

## Entities
Karakter yang sudah dipesan di HTML, dinamakan HTML Entity
Ada banyak sekali HTML Entity, dan direkomendasikan untuk menggunakan simbol Entity nya,
ketika kita ingin menggunakan karakter tersebut
Tapi sebenarnya tidak wajib, kita tetap bisa menggunakan karakter asli, namun lebih aman jika
menggunakan simbol Entity nya
Kita bisa lihat seluruh daftar HTML Entity di :
https://oinam.github.io/entities/
https://html.spec.whatwg.org/multipage/named-characters.html

Kode : HTML Entities
``` html
<html>
    <body>
        <h1>Belajar &#60;HTML&#62;</h1>
    </body>
</html>
```
