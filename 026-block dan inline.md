# Block dan Inline pada HTML

Setiap elemen di HTML memiliki **nilai display** yang menentukan bagaimana elemen tersebut ditampilkan di halaman web.  
Secara umum, ada dua jenis utama display: **block** dan **inline**.

---

## Block
Elemen dengan display **block** selalu dimulai di **baris baru**.  
Browser juga otomatis memberi jarak (margin) sebelum dan sesudah elemen.  

Ciri lainnya, elemen block akan **melebar memenuhi lebar halaman yang tersedia** (dari kiri ke kanan).  

**Contoh tag block:**  
`h1–h6`, `p`, `header`, `body`, `ul`, `li`, `ol`, `table`, `form`, dll.

---

## Inline
Elemen dengan display **inline** tidak dimulai di baris baru.  
Ukurannya hanya sesuai dengan konten di dalamnya, **tidak melebar ke seluruh halaman**.  

**Contoh tag inline:**  
`a`, `b`, `i`, `em`, `button`, `strong`, `input`, dll.

---

## Div
`<div>` adalah elemen **block** yang sering digunakan sebagai **container (wadah)**.  
Div berguna untuk mengelompokkan bagian halaman, misalnya menu, konten, header, atau footer.  
Biasanya setiap bagian dibungkus dengan div agar mudah diatur tampilannya.  

**Contoh penggunaan div:**
```html
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
      <p>Isi halaman</p>
    </div>
  </body>
</html>
````

---

## Span

Kalau `div` bersifat block, ada juga `<span>` yang bersifat **inline**.
`<span>` biasanya digunakan untuk memberi **style khusus** pada bagian teks tertentu, tanpa memengaruhi seluruh paragraf.

Misalnya kita ingin membuat teks “Programmer Zaman Now” dengan warna berbeda di tiap kata, kita bisa gunakan span untuk tiap katanya.

**Contoh penggunaan span:**

```html
<html>
  <body>
    <h1>
      <span style="color:red;">Kemas</span>
      <span style="color:blue;">WFH</span>
    </h1>
  </body>
</html>
```

---

Dengan memahami perbedaan **block** dan **inline**, kita bisa lebih mudah mengatur tata letak elemen di halaman web.