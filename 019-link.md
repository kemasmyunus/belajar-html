# Link (Tautan) di HTML

Saat membuat sebuah **website**, biasanya kita akan memiliki banyak halaman HTML.
Untuk berpindah dari satu halaman ke halaman lain, kita **tidak perlu mengetik alamat secara manual di browser**.

HTML menyediakan fitur **Link (Tautan)**.
Dengan link, kita bisa cukup **klik** teks atau gambar, lalu langsung berpindah ke halaman tujuan.

> Catatan: Link tidak harus berupa teks, bisa juga berupa **gambar** (akan dibahas di materi *Image*).

---

## Tag `<a>`

Untuk membuat link di HTML, kita menggunakan **tag `<a>`**.

* Isi dari tag `<a>` adalah **tampilan link** (bisa berupa teks atau elemen lain).
* Tag `<a>` memiliki beberapa **atribut penting**:

1. **`href`** → berisi alamat tujuan link.
2. **`target`** → menentukan cara membuka link.

   * `target="_self"` → membuka di halaman yang sama (default).
   * `target="_blank"` → membuka di tab/jendela baru.
3. **`title`** → teks tambahan yang muncul saat kursor diarahkan ke link (*tooltip*).

---

### Contoh Kode Link

```html
<html>
    <body>
        <h1>Belajar Link</h1>
        <ul>
            <li>
                <a href="https://instagram.com/kemasmyunus" target="_blank" title="Kunjungi Instagram">
                    Instagram
                </a>
            </li>
            <li>
                <a href="https://github.com/kemasmyunus" target="_blank" title="Lihat Github">
                    Github
                </a>
            </li>            
        </ul>
    </body>
</html>
```

---

## Absolute URL

Ketika menuliskan alamat tujuan di atribut `href`, kita bisa menggunakan **Absolute URL**.

* **Absolute URL** adalah alamat lengkap menuju halaman atau website.
* Dalam Absolute URL, kita harus menuliskan **seluruh domain + halaman** yang dituju.

Contoh:

```
https://instagram.com/kemasmyunus  
https://github.com/kemasmyunus  
```

### Kelebihan Absolute URL

* Bisa digunakan untuk membuat link ke **website lain** (domain berbeda).

---

Oke, aku bantu rapikan markdown-nya supaya lebih mudah dipahami, runtut, dan enak dibaca. Aku tambahkan penjelasan dengan poin-poin biar lebih jelas.

---

# Link (Tautan) di HTML

Saat membuat sebuah **website**, biasanya kita akan memiliki banyak halaman HTML.
Untuk berpindah dari satu halaman ke halaman lain, kita **tidak perlu mengetik alamat secara manual di browser**.

HTML menyediakan fitur **Link (Tautan)**.
Dengan link, kita bisa cukup **klik** teks atau gambar, lalu langsung berpindah ke halaman tujuan.

> Catatan: Link tidak harus berupa teks, bisa juga berupa **gambar** (akan dibahas di materi *Image*).

---

## Tag `<a>`

Untuk membuat link di HTML, kita menggunakan **tag `<a>`**.

* Isi dari tag `<a>` adalah **tampilan link** (bisa berupa teks atau elemen lain).
* Tag `<a>` memiliki beberapa **atribut penting**:

1. **`href`** → berisi alamat tujuan link.
2. **`target`** → menentukan cara membuka link.

   * `target="_self"` → membuka di halaman yang sama (default).
   * `target="_blank"` → membuka di tab/jendela baru.
3. **`title`** → teks tambahan yang muncul saat kursor diarahkan ke link (*tooltip*).

---

### Contoh Kode Link

```html
<html>
    <body>
        <h1>Belajar Link</h1>
        <ul>
            <li>
                <a href="https://instagram.com/kemasmyunus" target="_blank" title="Kunjungi Instagram">
                    Instagram
                </a>
            </li>
            <li>
                <a href="https://github.com/kemasmyunus" target="_blank" title="Lihat Github">
                    Github
                </a>
            </li>            
        </ul>
    </body>
</html>
```

---

## Absolute URL

Ketika menuliskan alamat tujuan di atribut `href`, kita bisa menggunakan **Absolute URL**.

* **Absolute URL** adalah alamat lengkap menuju halaman atau website.
* Dalam Absolute URL, kita harus menuliskan **seluruh domain + halaman** yang dituju.

Contoh:

```
https://instagram.com/kemasmyunus  
https://github.com/kemasmyunus  
```

### Kelebihan Absolute URL

* Bisa digunakan untuk membuat link ke **website lain** (domain berbeda).

---

# Link (Tautan) di HTML

## Relative URL

Selain **Absolute URL**, kita juga bisa menggunakan **Relative URL**.

* **Relative URL** adalah alamat tujuan link yang **mengikuti domain website saat ini**.
* Artinya kita tidak perlu menuliskan nama domain secara lengkap, cukup menuliskan **lokasi file relatif terhadap halaman yang sedang dibuka**.

Relative URL bisa ditulis dengan beberapa cara:

1. **Tanpa awalan “/”** → relatif terhadap folder saat ini.

   * `hello.html` → `http://127.0.0.1/belajar-link/hello.html`

2. **Dengan awalan “/”** → relatif terhadap root domain.

   * `/hello.html` → `http://127.0.0.1/hello.html`

3. **Menggunakan sub-folder** → relatif terhadap folder saat ini.

   * `pzn/hello.html` → `http://127.0.0.1/belajar-link/pzn/hello.html`

---

### Contoh Kode: Relative URL

```html
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

---

## Bookmark (Anchor Link)

Pada halaman web yang panjang, kita bisa menggunakan **Bookmark** agar pengunjung langsung menuju ke bagian tertentu.

* **Bookmark** adalah link yang menunjuk ke elemen HTML tertentu dengan **atribut `id`**.
* Pada `href`, kita tambahkan tanda **`#`** diikuti dengan **id target**.

### Contoh Bookmark di Halaman Sendiri

```html
<html>
    <body>
        <h1>Daftar Isi</h1>
        <ul>
            <li><a href="#judul1">Judul 1</a></li>
            <li><a href="#judul2">Judul 2</a></li>
            <li><a href="#judul3">Judul 3</a></li>
        </ul>

        <h1 id="judul1">Judul 1</h1>
        <p>Artikel tentang Judul 1</p>
        <p>Artikel lanjutan...</p>

        <h1 id="judul2">Judul 2</h1>
        <p>Artikel tentang Judul 2</p>
        <p>Artikel lanjutan...</p>

        <h1 id="judul3">Judul 3</h1>
        <p>Artikel tentang Judul 3</p>
        <p>Artikel lanjutan...</p>
    </body>
</html>
```

---

### Contoh Bookmark ke Halaman Lain

Kita juga bisa membuat link ke **bagian tertentu di halaman lain**.

```html
<html>
    <body>
        <h1>Daftar Isi</h1>
        <ul>
            <li><a href="019-link-bookmark-dihalaman-sendiri.html#judul1">Judul 1</a></li>
            <li><a href="019-link-bookmark-dihalaman-sendiri.html#judul2">Judul 2</a></li>
            <li><a href="019-link-bookmark-dihalaman-sendiri.html#judul3">Judul 3</a></li>
        </ul>
    </body>
</html>
```

---

👉 Dengan demikian:

* Gunakan **Relative URL** untuk navigasi antar-halaman dalam satu domain.
* Gunakan **Bookmark** untuk langsung menuju bagian tertentu di halaman yang sama atau halaman lain.