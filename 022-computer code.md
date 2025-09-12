# Computer Code
Sebagai programmer, kadang kita sering membuat web artikel tentang kode program
Pada kasus seperti ini, ketika kita membuat kode program di HTML menggunakan paragraph, maka
akan menyulitkan, karena semua enter dan spasi akan dinormalkan oleh HTML
Kadang kita ingin menampilkan kodenya apa adanya

## Tag Pre
Untuk menampilkan tulisan di dalam HTML apa adanya, kita bisa menggunakan tag pre
Namun perlu diingat, kode HTML tetap tidak akan ditampilkan, jadi kita harus menggunakan HTML
Entities

kode : pre
``` html
<html>
    <body>
        <h1>Belajar Kode Java</h1>
        <pre>
            public statuc void main(String[] args){
                System.out.println("Hello World");
            }
        </pre>
    </body>
</html>
```