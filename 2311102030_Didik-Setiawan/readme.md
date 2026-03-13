

<div align="center">
  <br />
  <h1>LAPORAN PRAKTIKUM <br>APLIKASI BERBASIS PLATFORM</h1>
  <br />
  <h3>MODUL 2 <br> HTML</h3>
  <br />
  <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2F1.bp.blogspot.com%2F-vb7jyBjK-sM%2FXXfKp51LrjI%2FAAAAAAAACts%2FEjcXzlgZwSswNWXsBHMyX-6aav1mjA77QCPcBGAYYCw%2Fs1600%2FLogo_Telkom_University_potrait.png&f=1&nofb=1&ipt=9d030d54102ea96369d39fe491220e0536195abc8ee443279c1a420302206400" alt="Logo Telkom" width="300"> 
  <br /><br /><br />
  
  <h3>Disusun Oleh :</h3>
  <p>
    <strong>Didik Setiawan</strong><br>
    <strong>2311102030</strong><br>
    <strong>IF-11-REG-01</strong>
  </p>
  <br />
  
  <h3>Dosen Pengampu :</h3>
  <p><strong>Dimas Fanny Hebrasianto Permadi, S.ST., M.Kom</strong></p>
  <br />
  
  <h4>Asisten Praktikum :</h4>
  <strong>Apri Pandu Wicaksono</strong> <br>
  <strong>Rangga Pradarrell Fathi</strong>
  <br />
  
  <h3>LABORATORIUM HIGH PERFORMANCE<br>FAKULTAS INFORMATIKA<br>UNIVERSITAS TELKOM PURWOKERTO<br>2026</h3>
</div>

---

## DASAR TEORI

HTML (HyperText Markup Language) adalah bahasa markup yang digunakan untuk merancang dan mengatur struktur halaman web. Bahasa ini bekerja dengan memanfaatkan berbagai tag yang menentukan elemen-elemen yang akan ditampilkan di laman web seperti teks, gambar, tautan, maupun tabel. Setiap tag memiliki peran spesifik dalam membentuk struktur dokumen agar dapat ditampilkan dengan benar oleh peramban web.

Salah satu elemen penting dalam HTML adalah tabel, yang berfungsi untuk menampilkan data dalam format baris dan kolom. Struktur tabel dibuat menggunakan tag <.table>, yang di dalamnya terdapat elemen lain seperti <.tr> (table row) untuk membuat baris, <.th> (table header) sebagai judul kolom, dan <.td> (table data) untuk menampilkan isi data di dalam tabel. Kombinasi tag-tag tersebut memungkinkan penyajian informasi yang lebih rapi dan mudah dibaca pengguna.

Selain itu, HTML juga menyediakan atribut tambahan untuk tabel, salah satunya atribut border yang berfungsi menampilkan garis pembatas agar struktur baris dan kolom lebih jelas. Meskipun dalam pengembangan web modern tampilan biasanya diatur menggunakan CSS, atribut dasar seperti border, align, dan valign masih dapat digunakan untuk pengaturan sederhana tanpa memerlukan gaya tambahan.

Dengan memanfaatkan tabel dalam HTML, data seperti daftar nama, kelas, atau nomor induk mahasiswa dapat disusun secara sistematis. Oleh karena itu, memahami elemen tabel menjadi bagian penting dalam pembuatan halaman web dasar.



## UNGUIDED

### kode html



```bash
<!DOCTYPE html>
<html lang="en">
<head>
    <title>TABEL DASAR</title>
</head>
<body>                                  
    <center>
    <table border="1">
        <tr>
            <th>Kelas</th>
            <th>Nama</th>
            <th>NIM</th>
        </tr>
        <tr>
            <td>if-11-01</td>
            <td>Didik Setiawan</td>
            <td>2311102030</td>
        </tr>
        <tr>
            <td>if-11-01</td>
            <td>Brian Farrel Evandika</td>
            <td>2311102037</td>
        </tr>
        <tr>
            <td>if-11-08</td>
            <td>Tegar Aji Pangestu</td>
            <td>2311102121</td>
        </tr>
    </table>
    </center>
</body>                             
</html>
```
![Alt 1](https://raw.githubusercontent.com/didiksetia1/asset/refs/heads/main/image.png)


##### penjelasan
Kode HTML tersebut digunakan untuk membuat halaman web sederhana yang menampilkan tabel berisi data mahasiswa. Pada bagian awal terdapat deklarasi `<!DOCTYPE html>` yang menunjukkan bahwa dokumen ini adalah halaman HTML. Tag `<head>` berisi judul halaman “TABEL DASAR” yang akan tampil di tab browser, sedangkan bagian `<body>` menampilkan isi halaman. Di dalamnya terdapat tag `<center>` untuk menempatkan tabel di tengah halaman dan tag `<table border="1">` untuk membuat tabel dengan garis tepi. Setiap baris tabel dibuat menggunakan tag `<tr>`, sedangkan `<th>` digunakan untuk judul kolom seperti “Kelas”, “Nama”, dan “NIM”. Data mahasiswa dimasukkan ke dalam tag `<td>` di tiap baris. Hasil akhirnya adalah sebuah tabel sederhana yang menampilkan informasi kelas, nama, dan NIM mahasiswa secara terstruktur dan rapi di tengah halaman web.


