## Unordered List
Untuk membuat daftar tanpa urutan (bullet point), kita bisa menggunakan tag `<ul>` di HTML.  
Setiap item dalam daftar dituliskan dengan tag `<li>`.

**Contoh Kode: Unordered List**
```html
<html>
    <body>
        <h2>Daftar Hobi</h2>
        <ul>
            <li>Badminton</li>
            <li>Catur</li>
            <li>Main Game</li>
        </ul>
    </body>
</html>
````

---

## Ordered List

Jika kita ingin membuat daftar yang berurutan (memiliki angka), kita bisa mengganti tag `<ul>` menjadi `<ol>`.
Untuk item daftar tetap menggunakan tag `<li>`.

**Contoh Kode: Ordered List**

```html
<html>
    <body>
        <h2>Tahapan Belajar HTML</h2>
        <ol>
            <li>Belajar pengenalan web</li>
            <li>Belajar HTML</li>
            <li>Menjalankan web</li>
        </ol>
    </body>
</html>
```

---

## Ordered List dengan Atribut `type`

Pada daftar berurutan (`<ol>`), kita bisa mengubah format penomoran dengan menambahkan atribut `type`.
Secara default, daftar menggunakan angka (dimulai dari 1). Berikut pilihan nilainya:

* `type="1"` → menggunakan angka (default)
* `type="A"` → menggunakan huruf kapital (A, B, C, …)
* `type="a"` → menggunakan huruf kecil (a, b, c, …)
* `type="I"` → menggunakan angka Romawi kapital (I, II, III, …)
* `type="i"` → menggunakan angka Romawi kecil (i, ii, iii, …)

**Contoh Kode: Ordered List Type**

```html
<html>
    <body>
        <h2>Tahapan Belajar HTML</h2>
        <ol type="I">
            <li>Belajar pengenalan web</li>
            <li>Belajar HTML</li>
            <li>Menjalankan web</li>
        </ol>
    </body>
</html>
```