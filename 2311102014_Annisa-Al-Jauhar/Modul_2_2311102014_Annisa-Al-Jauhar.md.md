<div align="center">

# LAPORAN PRAKTIKUM
# APLIKASI BERBASIS PLATFORM

---

## MODUL 2
## TABEL DASAR HTML

---

<img src="Logo_Telkom_University_potrait.png" width="200">

---

**Disusun Oleh :**

**ANNISA AL JAUHAR**

**2311102014**

**S1 IF-11-REG01**

---

**Dosen Pengampu :**

Dimas Fanny Hebrasianto Permadi, S.ST., M.Kom

---

**PROGRAM STUDI S1 INFORMATIKA**

**FAKULTAS INFORMATIKA**

**UNIVERSITAS TELKOM PURWOKERTO**

**2025/2026**

</div>

---

## 1. Dasar Teori

**HTML (HyperText Markup Language)** merupakan bahasa markah standar web yang digunakan untuk membuat dan menyusun struktur sebuah halaman website. HTML bekerja menggunakan sederet tag bersarang (nested element) untuk memberi tahu web browser bagaimana cara menampilkan elemen teks, gambar, maupun layout secara keseluruhan di layar. HTML bersifat statis dan menjadi fondasi utama dalam pengembangan halaman web sebelum mempelajari teknologi lain seperti CSS maupun JavaScript.

Dalam pembuatan struktur tabel murni memanfaatkan HTML (tanpa bantuan dari Cascading Style Sheets atau CSS), kita dapat menggunakan format elemen `<table>` dan didukung oleh tag `<tr>` untuk baris, `<th>` untuk header tabel, serta `<td>` untuk sel data tabel. Setiap elemen tabel harus berada di dalam tag `<table>` sebagai tag utama yang mendefinisikan keseluruhan struktur tabel.

HTML juga menyediakan atribut seperti `rowspan` untuk menggabungkan baris dan `colspan` untuk menggabungkan kolom. Atribut lain yang sering digunakan pada sisi presentasi meliputi `<center>` untuk meratakan konten di tengah dan `border`, `cellpadding`, `cellspacing` pada tag `<table>` untuk mengatur spasi sel dan border batas garis. Selain itu, atribut `width` dan `height` dapat digunakan untuk mengatur ukuran tabel, serta atribut `align` dan `valign` untuk mengatur posisi konten secara horizontal maupun vertikal.

Teknik **Nested Table** yaitu menempatkan tabel di dalam tabel lainnya juga dapat dimanfaatkan untuk memposisikan konten di tengah layar tanpa menggunakan CSS sama sekali. Tabel luar berfungsi sebagai container yang memenuhi seluruh layar menggunakan `width="100%"` dan `height="100%"`, sedangkan tabel dalam berisi data yang ingin ditampilkan di tengah halaman.

---

## 2. Penjelasan Kode HTML

Berikut adalah implementasi tabel dasar yang diposisikan di tengah layar tanpa menggunakan CSS.

### Kode HTML (index.html)
```html
<html>
<head>
    <title>Tabel Dasar</title>
</head>
<body>

<table width="100%" height="100%">
    <tr>
        <td align="center" valign="middle">

            <table border="1">
                <tr>
                    <th>No</th>
                    <th>Nama</th>
                    <th>Nilai</th>
                </tr>
                <tr>
                    <td>1</td>
                    <td>Annisa</td>
                    <td>90</td>
                </tr>
                <tr>
                    <td>2</td>
                    <td>Tegar</td>
                    <td>85</td>
                </tr>
            </table>

        </td>
    </tr>
</table>

</body>
</html>
```

### Penjelasan Kode

Tabel luar menggunakan `width="100%"` dan `height="100%"` agar memenuhi seluruh layar. Atribut `align="center"` dan `valign="middle"` pada `<td>` membuat konten di dalamnya berada tepat di tengah layar secara horizontal maupun vertikal. Tabel dalam menggunakan `border="1"` untuk menampilkan garis pada tabel. Teknik ini disebut nested table yaitu tabel di dalam tabel.

---

## 3. Hasil

![Hasil Tabel](screenshot.png)

---

<div align="center">

</div>