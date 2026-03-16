<div align="center">

# LAPORAN PRAKTIKUM  
# APLIKASI BERBASIS PLATFORM

## MODUL 2  
## HTML

<img src="assets/logo.jpeg" width="300">

### Disusun Oleh
**Shafa Adila Santoso**  
2311102158  
S1 IF-11-REG01  

### Dosen Pengampu
**Dimas Fanny Hebrasianto Permadi, S.ST., M.Kom**

### Asisten Praktikum
Apri Pandu Wicaksono  
Rangga Pradarrell Fathi  

### LABORATORIUM HIGH PERFORMANCE  
FAKULTAS INFORMATIKA  
UNIVERSITAS TELKOM PURWOKERTO  
2026

</div>

---

<div align="justify">

# 1. Dasar Teori

HTML (HyperText Markup Language) merupakan bahasa markup yang digunakan untuk membangun dan menyusun struktur dasar sebuah halaman web. HTML berfungsi untuk menampilkan berbagai elemen pada halaman web seperti teks, gambar, tabel, tautan, serta media. HTML menjadi dasar utama dalam pengembangan website karena menentukan struktur dan isi dari halaman yang akan ditampilkan oleh browser.

Struktur dasar HTML terdiri dari beberapa elemen utama yaitu `<!DOCTYPE html>`, `<html>`, `<head>`, `<title>`, dan `<body>`. Deklarasi `<!DOCTYPE html>` digunakan untuk menentukan bahwa dokumen menggunakan standar HTML5. Elemen `<html>` merupakan elemen utama yang membungkus seluruh isi halaman web. Elemen `<head>` berisi informasi metadata seperti judul halaman, sedangkan elemen `<body>` berisi seluruh konten yang ditampilkan pada halaman web.

Contoh struktur dasar HTML:

 ```html
<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
</head>
<body>
    <h1>My First Heading</h1>
    <p>My first paragraph.</p>
</body>
</html>
```

Dalam HTML terdapat beberapa komponen penting yaitu tag, elemen, dan atribut. Tag merupakan penanda yang digunakan untuk mendefinisikan elemen pada halaman web dan biasanya terdiri dari tag pembuka dan tag penutup. Elemen HTML adalah bagian dari halaman web yang terdiri dari tag pembuka, isi, dan tag penutup. Sedangkan atribut merupakan informasi tambahan yang diberikan pada sebuah tag HTML dengan format `<nama_atribut="value">`

Contoh penggunaan atribut pada HTML:

```html
<a href="https://www.google.com">Kunjungi Google</a>
```

HTML juga menyediakan berbagai elemen untuk menampilkan konten pada halaman web. Salah satunya adalah heading yang digunakan untuk membuat judul atau subjudul pada halaman web. HTML memiliki enam tingkatan heading yaitu `<h1>` hingga `<h6>` dimana `<h1>` merupakan tingkat judul paling penting. Contoh heading:

```html
    <h1>Heading 1</h1>
    <h2>Heading 2</h2>
    <h3>Heading 3</h3>
```

Selain heading, HTML memiliki hyperlink yang digunakan untuk menghubungkan satu halaman web dengan halaman web lainnya. Hyperlink dibuat menggunakan tag `<a>` dengan atribut href yang berisi alamat tujuan. Contoh hyperlink:

```html
<a href="https://www.google.com">Visit Google</a>
```
HTML juga menyediakan elemen tabel yang digunakan untuk menampilkan data dalam bentuk baris dan kolom. Elemen utama dalam tabel antara lain `<table>`, `<tr>`, `<th>`, dan `<td>`. Selain itu terdapat atribut seperti colspan dan rowspan yang digunakan untuk menggabungkan beberapa sel tabel. Contoh tabel:

```html
<table border="1">
<tr>
<th>Nama</th>
<th>Kota</th>
</tr>
<tr>
<td>Budi</td>
<td>Jakarta</td>
</tr>
</table>
```

Selain itu HTML dapat menampilkan gambar, audio, dan video untuk memperkaya tampilan halaman web. Gambar ditampilkan menggunakan tag `<img>` dengan atribut src yang menunjukkan lokasi file gambar. Sedangkan media audio dan video dapat ditampilkan menggunakan tag `<audio>` dan `<video>`. Contoh menampilkan gambar:

```html
<img src="gambar.jpg" width="200">
```
HTML juga memiliki elemen form yang digunakan untuk menerima input dari pengguna. Form biasanya digunakan untuk mengumpulkan data seperti nama, email, password, dan informasi lainnya. Elemen-elemen yang sering digunakan dalam form antara lain `<input>`, `<textarea>`, `<select>`, dan `<button>`. Contoh form sederhana:

```html
<form>
<input type="text" placeholder="Masukkan nama">
<input type="email" placeholder="Masukkan email">
<input type="submit" value="Submit">
</form>
```
Dengan memahami konsep dasar HTML seperti struktur dokumen, tag, atribut, serta berbagai elemen yang tersedia, pengguna dapat membuat halaman web yang terstruktur dengan baik dan mudah dikembangkan menggunakan teknologi web lainnya seperti CSS dan JavaScript.

---

## UNGUIDED

**Code :**

```html
<!DOCTYPE html>
<html>
<head>
    <title>Tugas Tabel Sederhana</title>
</head>
<body>

<center>
<h2>Tugas Tabel Sederhana</h2>

<table border="6" cellpadding="10" cellspacing="1">
    <tr>
        <th>NIM</th>
        <th>Nama</th>
        <th>Kelas</th>
        <th>Gelar</th>
    </tr>

    <tr>
        <td>2311102158</td>
        <td>Shafa</td>
        <td>IF-11-01</td>
        <td>S.Kom</td>
    </tr>

    <tr>
        <td>2311102158</td>
        <td>Adila</td>
        <td>IF-11-01</td>
        <td>M.Kom</td>
    </tr>

    <tr>
        <td>2311102158</td>
        <td>Santoso</td>
        <td>IF-11-01</td>
        <td>Ph.D</td>
    </tr>

</table>
</center>

</body>
</html>
```
Kode HTML di atas digunakan untuk membuat **tabel sederhana pada halaman web**. Program dimulai dengan deklarasi `<!DOCTYPE html>` yang menandakan bahwa dokumen menggunakan standar HTML5. Di dalam elemen `<body>`, terdapat judul **“Tugas Tabel Sederhana”** yang ditampilkan menggunakan tag `<h2>` dan diposisikan di tengah dengan tag `<center>`. Selanjutnya dibuat sebuah tabel menggunakan tag `<table>` dengan atribut `border`, `cellpadding`, dan `cellspacing` untuk mengatur tampilan garis tabel dan jarak antar sel. Tabel tersebut terdiri dari baris header `<th>` yang berisi kolom **NIM, Nama, Kelas, dan Gelar**, serta beberapa baris data `<tr>` yang menampilkan informasi mahasiswa menggunakan tag `<td>`. Kode ini menunjukkan cara dasar menampilkan data dalam bentuk tabel pada halaman web menggunakan HTML.


**Output :**

<p align="center">
<img src="assets/ss-hasil.png\" width="1000">
</p>