<div align="center">
  <br />
  <h1>LAPORAN PRAKTIKUM <br>APLIKASI BERBASIS PLATFORM</h1>
  <br />
  <h3>MODUL 2 <br> HTML</h3>
  <br />
  <br />
  <img src="logo.jpeg" alt="Logo" width="300"> 
  <br />
  <br />
  <br />
  <h3>Disusun Oleh :</h3>
  <p>
    <strong>Yoga Hogantara</strong><br>
    <strong>2311102153</strong><br>
    <strong>S1 IF-11-01</strong>
  </p>
  <br />
  <h3>Dosen Pengampu :</h3>
  <p>
    <strong>Dimas Fanny Hebrasianto Permadi, S.ST., M.Kom</strong>
  </p>
  <br />
  <br />
    <h4>Asisten Praktikum :</h4>
    <strong> Apri Pandu Wicaksono </strong> <br>
    <strong>Rangga Pradarrell Fathi</strong>
  <br />
  <h3>LABORATORIUM HIGH PERFORMANCE
 <br>FAKULTAS INFORMATIKA <br>UNIVERSITAS TELKOM PURWOKERTO <br>2026</h3>
</div>

---

## 1. Dasar Teori

HTML (HyperText Markup Language) merupakan fondasi utama dalam merancang kerangka sebuah situs web. Cara kerjanya mengandalkan sistem tag atau elemen yang saling bersarang (nested) untuk menginstruksikan peramban (browser) bagaimana cara menyajikan konten, baik itu teks, gambar, maupun media lainnya.

Salah satu fitur yang tersedia pada HTML adalah pembuatan tabel. Tabel dapat dibuat langsung menggunakan elemen HTML tanpa harus menggunakan bantuan CSS (Cascading Style Sheets). Dalam struktur tabel HTML terdapat beberapa elemen utama, antara lain:

- `<table>` Kontainer utama yang membungkus seluruh struktur tabel.
- `<tr>` Digunakan untuk mendefinisikan baris baru dalam tabel.
- `<th>` Menandakan sel sebagai header atau judul kolom (biasanya teks otomatis tebal).
- `<td>` Digunakan untuk mengisi sel dengan data atau konten.


Pada HTML versi lama juga terdapat beberapa atribut presentasi seperti `border` yang berfungsi untuk ketebalan border, dan tag `<center>` dapat digunakan untuk menempatkan elemen pada posisi tengah halaman. 

---

## 2. Penjelasan Kode HTML

Berikut ini adalah implementasi tabel berdasarkan struktur dasar HTML murni beserta hasil tampilannya.

### Kode HTML (`table.html`)

```html
<!DOCTYPE html>
<html>

<head>
    <title>Tabel gweh</title>
</head>

<body>

    <table border="2" align="center">
        <tr>
            <th>No</th>
            <th>Nama</th>
            <th>NIM</th>
            <th>Jurusan</th>
        </tr>

        <tr>
            <td>1</td>
            <td>Yoga Hogantara</td>
            <td>2311102153</td>
            <td>Informatika</td>
        </tr>

        <tr>
            <td>2</td>
            <td>Yhota</td>
            <td>2311102153</td>
            <td>IF</td>
        </tr>

    </table>

</body>

</html>
```

### Hasil Tampilan (Screenshot)

![Hasil Tabel HTML](1.PNG)

### Penjelasan Code

- **Baris 7–32** menggunakan tag pembungkus `<center>` yang berfungsi untuk menempatkan seluruh elemen tabel pada posisi tengah halaman. Dengan penggunaan tag ini, tabel akan otomatis ditampilkan di tengah layar browser tanpa perlu tambahan pengaturan menggunakan CSS.

- **Baris 9** menggunakan beberapa atribut pada tag `<table>`, yaitu `border="1"`, `cellpadding="5"`, dan `cellspacing="0"`.  
  - `border` berfungsi menampilkan garis batas tabel dengan ketebalan 1 piksel.  
  - `cellpadding` memberikan jarak antara isi sel dengan garis batas sel sebesar 5 piksel.  
  - `cellspacing` digunakan untuk menghilangkan jarak antar sel sehingga tampilan tabel terlihat lebih rapat.

- **Baris 11–12** menggunakan elemen `<th>` sebagai header tabel yang dilengkapi atribut `rowspan` dan `colspan`.  
  - `rowspan="2"` pada kolom **Nama Lengkap** membuat sel tersebut memanjang hingga dua baris.  
  - `colspan="2"` pada bagian **Gelar Pendidikan** menggabungkan dua kolom yang kemudian dibagi menjadi **Sarjana** dan **Magister** pada baris berikutnya.

- **Baris 19–30** berisi data tabel yang ditulis menggunakan elemen `<td>`. Setiap baris data dibungkus oleh tag `<tr>` yang menandakan satu baris tabel. Di dalam setiap baris tersebut terdapat beberapa sel yang berisi informasi seperti nama, gelar pendidikan, dan usia yang ditampilkan sejajar sesuai kolomnya.

## Refrensi

- [Materi Modul 2](https://drive.google.com/file/d/1Gcsi-U4rzqU0GC6dYTlzO7KUthrGoL8q/view?usp=sharing)