## Break Line
Seperti yang dibahas di materi Paragraph, enter di dalam tulisan tidak akan dianggap enter oleh
HTML, jika kita ingin membuat enter, disarankan membuat paragraf terpisah
Namun jika kita benar-benar ingin membuat enter di dalam paragraf, kita bisa menggunakan tag br
Tag br adalah void element, jadi tidak memiliki konten

Kode : Break Line
``` html
<html>
    <body>
        <h1>Belajar HTML</h1>
        <p>
            Ini adalah paragraph<br>
            Ini adalah baris selanjutnya
        </p>
    </body>
</html>
```

## Horizontal Rule
Di HTML, kita juga bisa membuat enter dengan garis horizontal (dari kiri ke kanan) sebagai
pemisah
Untuk melakukannya, kita bisa menggunakan tag hr
Tag hr juga merupakan void element, jadi tidak memiliki konten

Kode : Horizontal Rule
``` html
<html>
    <body>
        <h1>Belajar HTML</h1>
        <p>
            Ini adalah paragraph<br>
            Ini adalah baris selanjutnya<hr>
            ini adalah baris selanjutnya dengan horizontal rule
        </p>
    </body>
</html>
```