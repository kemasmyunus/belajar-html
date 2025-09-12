# Computer Code
Sebagai programmer, kita sering menulis artikel atau tutorial yang berisi kode program.  
Jika kita menuliskan kode program di dalam tag **paragraph (`<p>`)**, maka semua **enter** dan **spasi** akan dirapikan otomatis oleh HTML. Akibatnya, kode tidak tampil sesuai aslinya.  

Agar kode tampil persis seperti yang kita tulis, kita bisa menggunakan **tag `<pre>`**.  

## Tag `<pre>`
Tag `<pre>` berfungsi untuk menampilkan teks apa adanya, termasuk spasi dan baris baru.  
Namun perlu diingat, jika kita menuliskan kode HTML di dalam `<pre>`, tetap saja kode tersebut bisa terbaca sebagai HTML. Untuk itu, kita perlu menggunakan **HTML Entities** (misalnya `&lt;` untuk `<` dan `&gt;` untuk `>`).  

### Contoh
Kode berikut menampilkan program Java sederhana di dalam HTML:

```html
<html>
    <body>
        <h1>Belajar Kode Java</h1>
        <pre>
public static void main(String[] args) {
    System.out.println("Hello World");
}
        </pre>
    </body>
</html>
````