# Reserved Characters (Karakter yang Dipesan)

Di HTML, ada beberapa karakter khusus yang **tidak bisa langsung ditulis** di dalam teks biasa.
Contohnya: `<`, `>` atau `/`.

Kalau kita memaksakan menulis karakter ini langsung di HTML, biasanya hasilnya akan **error** atau tidak tampil sesuai yang kita mau.

### Contoh salah:

```html
<html>
    <body>
        <h1>Belajar <HTML></h1>
    </body>
</html>
```

Kode di atas akan dianggap browser sebagai tag HTML, bukan teks biasa.
Akibatnya, tulisan yang muncul tidak sesuai.

---

# Entities (Cara Menulis Karakter Khusus)

Supaya karakter khusus tadi bisa tetap ditampilkan sebagai teks, HTML menyediakan yang disebut **HTML Entities**.

**HTML Entity** adalah kode khusus yang dimulai dengan `&` dan diakhiri dengan `;`.
Dengan cara ini, browser tahu bahwa yang kita maksud adalah **karakter**, bukan tag HTML.

Contoh:

* `<` ditulis sebagai `&lt;` atau `&#60;`
* `>` ditulis sebagai `&gt;` atau `&#62;`
* `&` ditulis sebagai `&amp;`

### Contoh benar:

```html
<html>
    <body>
        <h1>Belajar &lt;HTML&gt;</h1>
    </body>
</html>
```

Hasilnya di browser:
**Belajar <HTML>**

---

Kalau mau lihat daftar lengkap HTML Entities:

* [oinam.github.io/entities](https://oinam.github.io/entities/)
* [html.spec.whatwg.org](https://html.spec.whatwg.org/multipage/named-characters.html)