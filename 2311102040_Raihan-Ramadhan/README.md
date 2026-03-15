<div align="center">

# LAPORAN PRAKTIKUM  
# APLIKASI BERBASIS PLATFORM

## MODUL 2  
## HTML

<img src="logo.jpeg" width="300">

### Disusun Oleh
**Raihan Ramadhan**  
2311102040  
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

# 1. Dasar Teori

**HTML (HyperText Markup Language)** adalah bahasa dasar yang digunakan untuk membuat dan menyusun halaman web. HTML berfungsi untuk mengatur elemen-elemen utama yang membentuk struktur sebuah website.

Dalam HTML, setiap tag biasanya terdiri dari **sepasang tag**, yaitu tag pembuka dan tag penutup. Konten yang ingin ditampilkan pada halaman web ditempatkan di antara kedua tag tersebut.

**Elemen HTML** adalah tag HTML yang memiliki isi di antara tag pembuka dan penutupnya. Isi tersebut bisa berupa teks maupun elemen HTML lainnya yang disisipkan di dalamnya.

**Atribut HTML** merupakan informasi tambahan yang diberikan pada sebuah tag HTML. Setiap atribut memiliki fungsi yang berbeda-beda, misalnya untuk menentukan warna, lebar, tinggi, dan sebagainya.

Atribut yang paling sering digunakan adalah **id** dan **class**, karena kedua atribut ini sangat penting dalam pengembangan web menggunakan **CSS** dan **JavaScript**.

Penulisan atribut pada HTML menggunakan format:

```html
<tag atribut="nilai">
```

Nilai atribut biasanya diapit dengan tanda petik dua.

---

## Dasar Sintaks HTML

### Heading

Heading dalam HTML digunakan untuk menampilkan judul atau subjudul pada halaman web. Heading juga berperan penting dalam **optimasi mesin pencari (SEO)** karena mesin pencari menggunakan heading sebagai acuan dalam proses pengindeksan.

HTML menyediakan **enam tingkat heading**, yaitu `<h1>` hingga `<h6>`. Semakin kecil angka heading, maka semakin penting perannya dan ukurannya biasanya lebih besar pada halaman web.

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

---

### Hyperlink

Hyperlink memungkinkan sebuah halaman web berpindah atau menavigasi ke halaman lain. Hyperlink menggunakan tag:

```html
<a href="URL">Teks Link</a>
```

Agar hyperlink dapat berfungsi, diperlukan atribut **href** yang berisi alamat URL tujuan.

---

### Tabel

Tabel dalam HTML digunakan untuk menampilkan data dalam bentuk baris dan kolom.

Struktur dasar tabel terdiri dari:

- `<table>` untuk mendefinisikan tabel  
- `<tr>` untuk mendefinisikan baris  
- `<th>` untuk judul kolom  
- `<td>` untuk isi data  

Pada tabel HTML juga terdapat fitur **Merge Cell**, seperti pada aplikasi Microsoft Word atau Excel. Fitur ini dapat dibuat dengan menambahkan atribut **colspan** atau **rowspan** pada tag `<td>`, yang menentukan jumlah kolom atau baris yang akan digabungkan.

```html
<table border="1">
  <tr>
    <th>Kolom 1</th>
    <th>Kolom 2</th>
  </tr>
  <tr>
    <td colspan="2">Merge 2 kolom</td>
  </tr>
</table>
```

---

### Gambar

Untuk menampilkan gambar pada halaman web digunakan tag:

```html
<img src="path/gambar.jpg" width="300" />
```

Tag `<img>` tidak memiliki pasangan tag penutup sehingga diakhiri dengan garis miring. Tag ini membutuhkan atribut **src** yang berisi alamat direktori tempat gambar disimpan.

---

## UNGUIDED

**Code :**

```html
<!DOCTYPE html>
<html>
<head>
  <title>Tabel Dasar Center</title>
</head>
<body>
  <table width="100%" height="100%">
    <tr>
      <td align="center" valign="middle">
        <table border="1" cellpadding="10">
          <tr>
            <th>NIM</th>
            <th>Nama</th>
            <th>Kelas</th>
          </tr>
          <tr>
            <td>2311102040</td>
            <td>Raihan Ramadhan</td>
            <td>IF-11-01</td>
          </tr>
          <tr>
            <td>2311102158</td>
            <td>Shafa Adila Santoso</td>
            <td>IF-11-01</td>
          </tr>
          <tr>
            <td>2311102007</td>
            <td>Nadhif Atha Zaki</td>
            <td>IF-11-01</td>
          </tr>
        </table>
      </td>
    </tr>
  </table>
</body>
</html>
```

**Output :**

<p align="center">
<img src="output.JPG" width="1000">
</p>
