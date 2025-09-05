# Style

## Apa itu CSS?
Sampai di sini kita sudah bisa membuat tulisan di HTML.  
Tapi, bagaimana kalau kita ingin mengubah **warna tulisan**, **jenis font**, atau **ukurannya**?  

Untuk itu kita menggunakan **CSS (Cascading Style Sheets)**.  
Namun dalam materi ini kita hanya akan belajar cara paling sederhana dengan **atribut `style`**, meskipun dalam praktik nyata nantinya kita lebih disarankan memakai file CSS terpisah.

---

## Atribut `style`
Setiap tag di HTML bisa diberikan atribut `style`.  
Di dalam `style`, kita bisa menambahkan aturan CSS untuk mengatur tampilan elemen.

Format penulisan:  
```html
<namatag style="property:value">
<namatag style="property:value; property2:value2">
````

* **property** = aturan CSS (misalnya warna, ukuran, dll)
* **value** = nilai dari aturan tersebut

Jika ada lebih dari satu aturan, pisahkan dengan `;` (titik koma).

---

## Beberapa Properti CSS yang Umum

Berikut beberapa contoh properti CSS dasar:

* `background-color` → mengubah warna latar belakang
* `color` → mengubah warna teks
* `font-family` → mengubah jenis font
* `font-size` → mengubah ukuran teks
* `text-align` → mengatur rata teks:

  * `left` (kiri)
  * `right` (kanan)
  * `center` (tengah)
  * `justify` (rata kiri-kanan)

---

## Contoh Kode

```html
<html>
  <body>
    <h1 style="color: red;">Belajar HTML</h1>

    <p style="background-color: aqua;">Hari ini kita akan belajar HTML</p>

    <p style="color: blue; font-size: 200%;">
      Ini teks dengan warna biru dan ukuran font 200%
    </p>
  </body>
</html>
```

---

👉 Jadi, dengan atribut `style`, kita bisa langsung memberikan gaya pada elemen HTML.
Tapi ingat, untuk membuat website yang lebih rapi dan terstruktur, sebaiknya gunakan **file CSS terpisah**.