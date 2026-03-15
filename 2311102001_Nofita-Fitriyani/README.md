<h1 align="center">LAPORAN PRAKTIKUM</h1>
<h1 align="center">APLIKASI BERBASIS PLATFORM</h1>

<br>

<h2 align="center">MODUL 2</h2>
<h2 align="center">HTML</h2>

<br><br>

<p align="center">
<img src="LogoTelkom.png" width="350">
</p>
<br><br><br>

<h2 align="center">Disusun Oleh :</h2>

<p align="center" style="font-size:28px;">
  <b>Nofita Fitriyani</b><br>
  <b>2311102001</b><br>
  <b>S1 IF-11-REG 01</b>
</p>
<br>
<h2 align="center">Dosen Pengampu :</h2>

<p align="center" style="font-size:28px;">
  <b>Dimas Fanny Hebrasianto Permadi, S.ST., M.Kom</b>
</p>
<br>
<h2 align="center">Asisten Praktikum :</h2>

<p align="center" style="font-size:28px;">
  <b>Apri Pandu Wicaksono</b><br>
  <b>Rangga Pradarrell Fathi</b>
</p>
<br>
<h1 align="center">LABORATORIUM HIGH PERFORMANCE</h1>
<h1 align="center">FAKULTAS INFORMATIKA</h1>
<h1 align="center">UNIVERSITAS TELKOM PURWOKERTO</h1>
<h1 align="center">TAHUN 2026</h1>

<hr>

### Dasar Teori
HTML atau HyperText Markup Language adalah bahasa markup yang digunakan untuk membuat struktur dasar sebuah halaman web. Dengan HTML, kita dapat menampilkan berbagai elemen seperti teks, gambar, link, form, dan tabel. Salah satu elemen penting dalam HTML adalah tabel.

Tabel pada HTML digunakan untuk menampilkan data dalam bentuk baris dan kolom agar informasi menjadi lebih terstruktur dan mudah dibaca. Elemen utama yang digunakan untuk membuat tabel adalah `<table>`, sedangkan untuk membuat baris digunakan tag `<tr>`, untuk judul kolom digunakan tag `<th>`, dan untuk isi data digunakan tag `<td>`.

### Source Code
```html
<!DOCTYPE html>
<html>
<head>
<title>Tugas 2 - Tabel Dasar</title>
</head>

<body>

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<center>
<table border="1" cellspacing="0" >
<tr>
<th>Nama Lengkap</th>
<th>Kota Kelahiran</th>
<th>Age</th>
</tr>

<tr>
<td>Nofita Fitriyani</td>
<td>Purwokerto</td>
<td>20</td>
</tr>

<tr>
<td>Budi</td>
<td>Jakarta</td>
<td>35</td>
</tr>

<tr>
<td>Andi</td>
<td>Semarang</td>
<td>52</td>
</tr>

</table>
</center>

</body>
</html>
```

### Output 
Output program menampilkan sebuah tabel sederhana yang berada di tengah halaman. Tabel tersebut memiliki 3 kolom, yaitu Nama Lengkap, Kota Kelahiran, dan Age, serta berisi 3 baris data.

<img src="output.png">

### Pembahasan Source Code
Pada tugas ini, tabel harus ditampilkan di tengah layar tanpa menggunakan CSS atau styling. Oleh karena itu, digunakan tag `<center>` untuk menempatkan tabel di bagian tengah secara horizontal. Selain itu, digunakan beberapa tag `<br>` untuk memberi jarak ke bawah sehingga tabel tampak berada di bagian tengah halaman. Atribut border="1" digunakan untuk menampilkan garis tabel, sedangkan cellspacing="0" digunakan agar jarak antar garis tabel tidak renggang.

`<!DOCTYPE html>` berfungsi untuk mendeklarasikan bahwa dokumen yang digunakan adalah HTML5.
`<html>` merupakan tag pembuka untuk seluruh isi dokumen HTML.
`<head>` digunakan untuk menyimpan informasi tambahan halaman, seperti judul halaman.
`<title>Tugas 2 - Tabel Dasar</title>` berfungsi menampilkan judul halaman pada tab browser.
`<body>` berisi seluruh isi halaman web yang akan ditampilkan kepada pengguna.
Tag `<br>` digunakan untuk membuat baris kosong atau memberi jarak ke bawah. Pada kode ini, beberapa tag `<br>` dipakai agar tabel turun ke bagian tengah halaman secara vertikal.
Tag `<center>` digunakan untuk meletakkan tabel di tengah halaman secara horizontal. Cara ini dipakai karena pada soal tidak diperbolehkan menggunakan CSS atau styling.
Tag `<table border="1" cellspacing="0">` digunakan untuk membuat tabel.
`border="1"` menampilkan garis pada tabel.
`cellspacing="0"` menghilangkan jarak antar sel sehingga garis tabel terlihat menyatu.
Tag `<tr>` digunakan untuk membuat baris tabel.
Tag `<th>` digunakan untuk membuat judul kolom tabel. Pada program ini terdapat 3 judul kolom, yaitu: Nama Lengkap, Kota Kelahiran, Age

Tag `<td>` digunakan untuk mengisi data pada tiap sel tabel. Pada program ini terdapat 3 data, yaitu: 
Nofita Fitriyani, Purwokerto, 20
Budi, Jakarta, 35
Andi, Semarang, 52

Secara keseluruhan, kode program ini menampilkan tabel sederhana yang berisi data identitas dan ditampilkan di tengah halaman tanpa menggunakan CSS.

### Kesimpulan
Berdasarkan program yang dibuat, dapat disimpulkan bahwa HTML dapat digunakan untuk membuat tabel sederhana dengan mudah menggunakan tag `<table>`, `<tr>`, `<th>`, dan `<td>`. Tabel dapat diletakkan di tengah halaman tanpa CSS dengan memanfaatkan tag `<center>` dan bantuan tag `<br>` untuk memberi jarak vertikal. Program ini sudah sesuai dengan ketentuan soal, yaitu membuat tabel dasar yang berada di tengah layar tanpa menggunakan CSS atau styling tambahan.

### Referensi
- [Materi Modul 2](https://drive.google.com/file/d/1Gcsi-U4rzqU0GC6dYTlzO7KUthrGoL8q/view?usp=sharing)

