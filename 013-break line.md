# Break Line (Ganti Baris)

Seperti yang sudah dibahas di materi **Paragraph**, menekan tombol **Enter** di kode HTML **tidak akan membuat baris baru** di tampilan browser.
Kalau mau membuat baris baru, biasanya kita buat paragraf terpisah dengan `<p>`.

Tapi, kalau kita ingin memaksa baris baru di dalam paragraf yang sama, kita bisa menggunakan tag `<br>` (**break line**).

👉 `<br>` termasuk **void element**, artinya tidak punya isi dan tidak perlu ditutup dengan tag penutup.

### Contoh Break Line

```html
<html>
    <body>
        <h1>Belajar HTML</h1>
        <p>
            Ini adalah paragraf pertama<br>
            Ini adalah baris baru di paragraf yang sama
        </p>
    </body>
</html>
```

Hasil di browser:
Ini adalah paragraf pertama
Ini adalah baris baru di paragraf yang sama

---

# Horizontal Rule (Garis Pemisah)

Selain baris baru, kita juga bisa menambahkan **garis horizontal** sebagai pemisah konten.
Caranya menggunakan tag `<hr>`.

👉 `<hr>` juga **void element**, jadi tidak perlu tag penutup.

### Contoh Horizontal Rule

```html
<html>
    <body>
        <h1>Belajar HTML</h1>
        <p>
            Ini adalah paragraf pertama<br>
            Ini adalah baris selanjutnya
        </p>
        <hr>
        <p>
            Ini adalah paragraf setelah garis pemisah
        </p>
    </body>
</html>
```

Hasil di browser:
Teks pertama → garis horizontal → teks setelah garis.