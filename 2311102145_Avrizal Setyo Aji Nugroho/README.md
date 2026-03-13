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
    <strong>Avrizal Setyo Aji Nugroho</strong><br>
    <strong>2311102145</strong><br>
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
<html lang="id">
  <head>
    <meta charset="UTF-8" />
    <title>Tugas 2_Avrizal Setyo Aji Nugroho</title>
  </head>

  <body>
    <center>
      <h1>Tugas 2 - Tabel Dasar</h1>
      <h3>Avrizal Setyo Aji Nugroho</h3>
      <h3>2311102145</h3>
    </center>

    <table border="0" width="100%" height="600" cellpadding="0" cellspacing="0">
      <tr>
        <td align="center" valign="middle">
          <table border="1" cellpadding="15" cellspacing="0">
            <thead>
              <tr>
                <th>No</th>
                <th>Item</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>1</td>
                <td>SAWIT</td>
              </tr>
              <tr>
                <td>2</td>
                <td>KELAPA</td>
              </tr>
              <tr>
                <td>3</td>
                <td>APEL HIJAU</td>
              </tr>
              <tr>
                <td>4</td>
                <td>ANGREK MEKAR</td>
              </tr>
              <tr>
                <td>5</td>
                <td>Avrizal Setyo A.N</td>
              </tr>
            </tbody>
          </table>
        </td>
      </tr>
    </table>
  </body>
</html>
```

### Hasil Tampilan (Screenshot)

![Hasil Tabel HTML](Screenshot%202026-03-13%20204659.png)

### Penjelasan Code

- **Baris 11–14** Menggunakan tag pembungkus <center> untuk menempatkan judul utama (h1) dan identitas mahasiswa (h3) di posisi tengah halaman secara horizontal. Hal ini membuat struktur header terlihat rapi tepat di bagian atas tengah layar.

- **Baris 16–49** Menggunakan struktur tabel bersarang (nested table). Tabel luar berfungsi sebagai kontainer utama dengan atribut width="100%" dan height="600", serta atribut align="center" dan valign="middle" pada sel di dalamnya. Hal ini bertujuan agar tabel data utama yang ada di baris 20 benar-benar berada di titik tengah halaman (baik secara horizontal maupun vertikal).

- **Baris 20**: Pada tag `<table>` untuk data utama, digunakan atribut `border="1"`, `cellpadding="15"`, dan `cellspacing="0"`.
  - `border="1"`: menampilkan garis tepi pada setiap sel tabel.
  - `cellpadding="15"`: memberikan ruang antara teks dengan garis sel agar mudah dibaca.
  - `cellspacing="0"`: merapatkan jarak antar sel sehingga garis tabel terlihat menyatu (garis tunggal).

- **Baris 21–26**: Bagian `<thead>` mendefinisikan kepala tabel yang berisi dua kolom utama, yaitu **No** dan **Item**.

- **Baris 27–46**: Bagian `<tbody>` berisi lima baris data yang dibungkus dengan tag `<tr>`. Setiap baris memiliki dua sel (`<td>`) yang menampilkan nomor urut dan nama item. Struktur ini bersifat linier tanpa `rowspan` atau `colspan`.

---

## Refrensi

- [Materi Modul 2](https://drive.google.com/file/d/1Gcsi-U4rzqU0GC6dYTlzO7KUthrGoL8q/view?usp=sharing)
