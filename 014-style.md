# style
## css
Sekarang kita sudah bisa membuat tulisan, pertanyaannya, bagaimana jika kita ingin mengubah
font, ukurannya, dan warnanya
Untuk melakukan itu, sebenarnya kita perlu belajar CSS terlebih dahulu
Namun pada kelas ini, kita akan bahas sekilas cara menggunakan CSS yang sederhana, walaupun
pada kenyataanya nanti ketika kita membuat web, lebih disarankan tidak mempraktekan materi ini

## Style Attribute
Setiap tag di HTML memiliki atribut style, dimana kita bisa menambahkan informasi CSS, yaitu
untuk mengubah gaya isi element-nya
Style attribute berisikan key:value CSS, jika lebih dari satu, maka gunakan ; (titik koma) sebagai
pemisah, misal :
`<namatag style=”property:value”>`
`<namatag style=”property:value; property2:value2”>`

## Contoh CSS
Berikut adalah contoh css atribut yang bisa kita gunakan, lebih lanjutnya akan kita bahas di kelas
CSS
background-color : untuk mengubah warna latar belakang
color : untuk mengubah warna font
font-family : untuk mengubah jenis font
font-size : untuk mengubah ukuran text
text-align : untuk mengubah rata tulisan secara horizontal, bisa left (kiri), right (kanan), center
(tengah), justify (kiri dan kanan)

Kode : Style
``` html
<html>
    <body>
        <h1 style="color: red;">Belajar HTML</h1>

        <p style="background-color: aqua;">Hari ini kita akan belajar HTML</p>

        <p style="color: blue; font-size: 200%">Ini ada style dengan warna biru dan ukuran font 200%</p>
    </body>
</html>

```