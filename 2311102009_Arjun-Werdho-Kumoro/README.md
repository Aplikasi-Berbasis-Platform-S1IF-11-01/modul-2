<div align="center">
  <br />
  <h1>LAPORAN PRAKTIKUM <br>APLIKASI BERBASIS PLATFORM</h1>
  <br />
  <h3>MODUL 2 <br> HTML</h3>
  <br />
  <img src="assets/Logo_Telkom_University_potrait.png" alt="Logo" width="300"> 
  <br /><br /><br />

  <h3>Disusun Oleh :</h3>
  <p>
    <strong>Arjun Werdho Kumoro</strong><br>
    <strong>2311102009</strong><br>
    <strong>IF-11-REG01</strong>
  </p>

  <br />

  <h3>Dosen Pengampu :</h3>
  <p>
    <strong>Dimas Fanny Hebrasianto Permadi, S.ST., M.Kom</strong>
  </p>

  <br />

  <h4>Asisten Praktikum :</h4>
  <strong>Apri Pandu Wicaksono</strong><br>
  <strong>Rangga Pradarrell Fathi</strong>

  <br /><br />

  <h3>
  LABORATORIUM HIGH PERFORMANCE <br>
  FAKULTAS INFORMATIKA <br>
  UNIVERSITAS TELKOM PURWOKERTO <br>
  2026
  </h3>
</div>

---

# DASAR TEORI

HTML (HyperText Markup Language) merupakan bahasa markup yang digunakan untuk membuat dan menyusun struktur halaman web. HTML bekerja dengan menggunakan berbagai tag yang berfungsi untuk menentukan elemen-elemen yang akan ditampilkan pada halaman web seperti teks, gambar, tautan, maupun tabel. Setiap tag dalam HTML memiliki fungsi tertentu yang membantu dalam membangun struktur dokumen sehingga dapat ditampilkan dengan baik oleh web browser.

Salah satu elemen yang sering digunakan dalam HTML adalah tabel. Tabel digunakan untuk menampilkan data secara terstruktur dalam bentuk baris dan kolom. Elemen tabel dalam HTML dibuat menggunakan tag `<table>`. Di dalam tag tersebut terdapat beberapa tag lain seperti `<tr>` (table row) yang berfungsi untuk membuat baris, `<th>` (table header) yang digunakan sebagai judul kolom tabel, serta `<td>` (table data) yang digunakan untuk menampilkan isi data pada tabel.

Selain itu, HTML juga menyediakan atribut tambahan pada tabel, salah satunya adalah atribut `border` yang digunakan untuk menampilkan garis pada tabel sehingga struktur baris dan kolom dapat terlihat dengan jelas. Dalam pengembangan web modern, pengaturan tampilan biasanya menggunakan CSS, namun pada HTML dasar atribut seperti `border`, `align`, dan `valign` masih dapat digunakan untuk mengatur tampilan sederhana tanpa menggunakan styling tambahan.

Melalui penggunaan tabel dalam HTML, data seperti daftar nama, kelas, atau nomor induk mahasiswa dapat disajikan secara terstruktur. Oleh karena itu, pemahaman mengenai elemen tabel dalam HTML menjadi dasar penting dalam pembuatan halaman web sederhana.

---

# UNGUIDED

## Code

```html
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
        <td>IF-11-01</td>
        <td>Arjun</td>
        <td>2311102001</td>
    </tr>

    <tr>
        <td>IF-11-02</td>
        <td>Werdho</td>
        <td>2311102002</td>
    </tr>

    <tr>
        <td>IF-11-03</td>
        <td>Kumoro</td>
        <td>2311102003</td>
    </tr>

</table>
</center>

</body>
</html>
```
## Output
![Screenshot Git](assets/ss01.png)
# Penjelasan
Kode HTML di atas digunakan untuk menampilkan sebuah tabel yang berisi data kelas, nama, dan NIM mahasiswa. Baris `<!DOCTYPE html>` berfungsi untuk memberi tahu browser bahwa dokumen menggunakan standar HTML5.

Tag `<html>` merupakan elemen utama yang membungkus seluruh isi halaman web. Di dalamnya terdapat dua bagian utama yaitu `<head>` dan `<body>`. Bagian `<head>` berisi informasi mengenai halaman web seperti judul halaman yang ditampilkan pada tab browser melalui tag `<title>`.

Bagian `<body>` merupakan bagian yang berisi konten utama yang akan ditampilkan pada halaman web. Pada kode di atas terdapat tag `<center>` yang digunakan untuk menempatkan tabel di tengah halaman secara horizontal.

Tabel dibuat menggunakan tag `<table>` dengan atribut border="1" agar tabel memiliki garis pembatas. Di dalam tabel terdapat beberapa elemen penting yaitu `<tr>` yang digunakan untuk membuat baris tabel, `<th>` yang berfungsi sebagai judul kolom seperti Kelas, Nama, dan NIM, serta `<td>` yang digunakan untuk menampilkan data pada setiap kolom tabel.

Dengan menggunakan struktur tag tersebut, data dapat ditampilkan secara rapi dalam bentuk tabel sehingga informasi lebih mudah dibaca dan dipahami oleh pengguna.