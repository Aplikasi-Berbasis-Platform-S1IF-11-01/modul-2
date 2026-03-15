<div align="center">
  <br />
  <h1>LAPORAN PRAKTIKUM <br>ALGORITMA PEMROGRAMAN</h1>
  <br />
  <h3>MODUL 2 <br> HTML</h3>
  <br />
  <br />
  <img src="assets/logo.png" alt="logo" width="300">
  <br />
  <br />
  <br />
  <h3>Disusun Oleh :</h3>
  <p>
    <strong>Kanasya Abdi Aziz</strong><br>
    <strong>2311102140</strong><br>
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
  <strong>Apri Pandu Wicaksono</strong> <br>
  <strong>Rangga Pradarrell Fathi</strong>
  <br />
  <h3>LABORATORIUM HIGH PERFORMANCE
  <br>FAKULTAS INFORMATIKA
  <br>UNIVERSITAS TELKOM PURWOKERTO
  <br>2026</h3>
</div>

---

## 1. Dasar Teori

HTML (HyperText Markup Language) adalah bahasa umum yang digunakan untuk membuat kerangka halaman web. Ini bekerja melalui sistem elemen atau tag yang saling bersarang (*nested*), yang memberi tahu browser bagaimana konten harus ditampilkan.

Membuat tabel secara langsung menggunakan elemen-elemen berikut adalah salah satu fitur dasar HTML: `<table>` adalah komponen utama yang membungkus seluruh struktur tabel, `<tr>` adalah elemen baris yang menentukan baris dalam tabel, `<th>` adalah sel khusus untuk judul kolom atau baris yang biasanya tercetak tebal, dan `<td>` adalah elemen standar yang berisi data atau konten tabel.

HTML memiliki atribut untuk menggabungkan sel, seperti `colspan` untuk menggabungkan kolom secara horizontal dan `rowspan` untuk menggabungkan baris secara vertikal, untuk tata letak yang lebih kompleks.

---

## 2. Penjelasan Kode HTML (Unguided)

Berikut adalah implementasi tabel data mahasiswa menggunakan teknik *nested table* sesuai dengan tugas praktikum.

### Kode HTML (`unguided.html`)

```html
<!DOCTYPE html>
<html lang="id">
    <head>
        <title>Tabel </title>
    </head>
    <body>
        <center>
            <table widht="80" border="1" cellpadding="1" cellspacing="0">
                <tr>
                    <th><b>Nama Lengkap</b></th>
                    <th><b>Kota Kelahiran</b></th>
                    <th><b>Usia</b></th>
                </tr>
                <tr align="center"> 
                    <td>Kanasya Abdi Aziz</td>
                    <td>Sokaraja</td>
                    <td>21</td>
                </tr>
                <tr align="center">
                    <td>M. Faleno Albar Firjatulloh</td>
                    <td>Bumiayu</td>
                    <td>21</td>
                </tr>
                <tr align="center">
                    <td>Agnes Refilina Fiska</td>
                    <td>Cilacap</td>
                    <td>21</td>
                </tr>
            </table>
            <br><br><br>
        </center>
    </body>
</html>
````

---

### Hasil Tampilan (Screenshot)

![Hasil Tabel HTML](assets/1.png)

---

### Penjelasan Code

#### Layout dan Pengaturan Posisi

`<body>` berisi semua konten visual yang akan dilihat pengguna.

`<center>` digunakan untuk membuat tabel berada tepat di tengah halaman secara horizontal.

Catatan: Tag `<center>` sebenarnya sudah dianggap usang (*deprecated*) dalam standar HTML modern. Saat ini lebih disarankan menggunakan CSS seperti `margin: auto`.

#### Komponen Tabel

Tabel didefinisikan dengan tag `<table>` yang memiliki beberapa atribut:

* `border="1"` menambahkan garis tepi tipis di sekeliling sel.
* `cellpadding="1"` memberikan jarak antara garis tepi sel dengan isi teks di dalamnya.
* `cellspacing="0"` menghilangkan celah antar garis sel sehingga terlihat menyatu.
* `widht="80"` (sedikit salah ketik, seharusnya `width`) digunakan untuk menentukan lebar tabel.

#### Isi Data Tabel

Tabel ini terbagi menjadi dua bagian utama.

**Header (`<tr>` dengan `<th>`)**

Baris pertama berisi judul kolom yaitu:

* Nama Lengkap
* Kota Kelahiran
* Usia

Penggunaan tag `<th>` secara otomatis membuat teks menjadi tebal (*bold*).

**Data (`<tr>` dengan `<td>`)**

Terdapat tiga baris data di bawahnya. Atribut `align="center"` pada tag `<tr>` memastikan semua teks di baris tersebut rata tengah.

Isinya meliputi:

* Kanasya Abdi Aziz (Sokaraja, 21)
* M. Faleno Albar Firjatulloh (Bumiayu, 21)
* Agnes Refilina Fiska (Cilacap, 21)

---

## Referensi

* [Materi Modul 2](https://drive.google.com/file/d/1Gcsi-U4rzqU0GC6dYTlzO7KUthrGoL8q/view?usp=sharing)
