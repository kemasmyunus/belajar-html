# Pengenalan HTML
## HTML
HTML adalah singkatan dari HyperText Markup Language, ini adalah struktur dasar dari halaman web.
HTML mendeskripsikan struktur sari isi konten halaman web. selain html, terdapat hal lain untuk mendeskripsikan sebuah halaman web, seperti untuk gaya tampilan halaman web menggunakan CSS atau interaksi halaman web menggunakan Javascript.
di materi ini, kita hanya akan fokus membahas html, tidak akan membahas tentang css atau javascript. html sendiri sebenarnya hanyalah kumpulan kode yang berisi informasi halaman web. kode html akan dibaca oleh web browser untuk diampilkan secara visual.

## Kode HTML
untuk melihat kode html, kita bisa buka website yang kita mau menggunakan web browser. lalu gunakan menu view source di aplikasi web browser nya.
misal kita buka website https://www.github.com/

## Tag
Kode html, berisikan kumpulan tag yang kita buat. tag adalah perintah dalam html yang memiliki aturan pembuka dan penutup.
ada banyak sekali tag di html, nanti kita akan pelajari satu per satu. contoh untuk membuat sebuah tulisan paragraf di html, kita bisa menggunakan tag `p`, dimana penulisannya :
``` html
<p> Hello World </p>
<p> Ini adalah tag paragraf</p>
```
pada contoh code tag `p` diatas, terdapat tag `<p>` yang merupakan tag pembuka untuk tag paragraf dan tag `</p>` yang merupakan tag penutup
sedangkan `Hello World` adalah isi konten dari tag p
tag berisi kontennya bisa kita sebut dengan nama element.

## Void Element
Pada beberapa kasus, ada tag di HTML yang tidak perlu memiliki konten, hal ini bisa kita sebut dengan void element.
contoh, di html terdapat tag untuk membuat break line / enter, dengan menggunakan tag `br`.
karena tag `br` tidak memiliki konten, maka kita bisa menggunakan perintah `<br>` atau `</br>` tanpa harus menggunakan tag pembuka dan tag penutup.

## Attribute
Element memiliki atribut. atribut adalah informasi tambahan untuk tag yang kita gunakan. kita bisa tambahkan atribut di element pada tag pembuka.
contoh untuk menampilkan gambar di html, kita bisa menggunakan tag `<img>` dengan atribut `src` yang berisikan lokasi gambar yang ingin kita tampilkan.
`<img src="folder_gambar/file.jpg">` .
attribute bisa digunakan di element biasa atau di void element.

## HTML tidak case sensitive
Penulisan tag di html tidak case sensitive, artinya huruf besar atau kecil tidak masalah. namun sangat disarankan menggunakan huruf kecil semua, misal `<p>`, jangan `<P>`.
