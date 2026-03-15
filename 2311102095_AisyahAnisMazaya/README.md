<div align="center">
  <br />

  <h1>LAPORAN PRAKTIKUM <br>
  APLIKASI BERBASIS PLATFORM
  </h1>

  <br />

  <h3>MODUL 2 <br>
  HTML
  </h3>

  <br />

  <p align="center">
<img src="logo.jpeg" width="200">
</p>

  <br />
  <br />
  <br />

  <h3>Disusun Oleh :</h3>

  <p>
    <strong>Aisyah Anis Mazaya</strong><br>
    <strong>2311102095</strong><br>
    <strong>S1 IF-11-REG01</strong>
  </p>

  <br />

  <h3>Dosen Pengampu :</h3>

  <p>
    <strong>Dimas Fanny Hebrasianto Permadi, S.ST., M.Kom</strong>
  </p>
  
  <br />
  <br />
    <h4>Asisten Praktikum :</h4>
    <strong>Apri Pandu Wicaksono </strong> <br>
    <strong>Rangga Pradarrell Fathi</strong>
  <br />

  <h3>LABORATORIUM HIGH PERFORMANCE
 <br>FAKULTAS INFORMATIKA <br>UNIVERSITAS TELKOM PURWOKERTO <br>2026</h3>
</div>

<hr>

## Dasar Teori

HTML adalah fondasi utama dalam membangun struktur halaman web. Cara kerjanya mengandalkan sistem tag bersarang yang menginstruksikan browser untuk menyusun teks, gambar, hingga tata letak secara keseluruhan. Jika ingin membuat tabel murni hanya dengan HTML tanpa bantuan CSS, kita bisa menggunakan elemen `<table>` sebagai bingkai utama, yang kemudian diisi dengan `<tr>` untuk membuat baris, `<th>` untuk judul kolom, serta `<td>` untuk mengisi data di setiap selnya.

Untuk kebutuhan layout yang lebih kompleks, tersedia atribut `rowspan` untuk menyatukan beberapa baris atau `colspan` untuk menggabungkan kolom. Meskipun saat ini sudah dianggap metode lama atau legacy, HTML juga menyediakan opsi pengaturan tampilan langsung melalui atribut `border`, `cellpadding`, dan `cellspacing` untuk mengatur garis serta jarak antar sel. Bahkan, ada tag `<center>` yang dapat digunakan untuk meletakkan konten tepat di posisi tengah halaman secara instan.

## Kode Program

```html
<table border="1" align="center">
    <tr>
        <th>Nama</th>
        <th>Mata Kuliah</th>
    </tr>
    <tr>
        <!-- 2311102095 - Aisyah Anis Mazaya - Modul_2 -->
        <td>Aisyah</td>
        <td>Aplikasi Berbasis Platform</td>
    </tr>
    <tr>
        <td>Anis</td>
        <td>Kewirausahaan</td>
    </tr>
     <tr>
        <td>Picu</td>
        <td>Informatika Untuk Masyarakat</td>
    </tr>
    <tr>
        <td>Muja</td>
        <td>Computing Project</td>
    </tr>
    <tr>
</table>
```

### Output

![Output](sstabel.png)
Kode HTML tersebut berfungsi untuk membuat sebuah tabel data mahasiswa yang rapi di tengah halaman. Penggunaan tag `<table>` dengan atribut `border="1"` memberikan garis tepi pada setiap sel, sementara `align="center"` memastikan tabel berada tepat di posisi tengah. Pada baris pertama, digunakan tag `<tr>` yang berisi header `<th>` untuk kolom "Nama" dan "Mata Kuliah" yang secara otomatis tercetak tebal.

Selanjutnya, setiap baris data mahasiswa didefinisikan menggunakan tag `<tr>` dan sel datanya menggunakan tag `<td>`. Data yang ditampilkan mencakup daftar nama seperti Aisyah, Anis, Picu, dan Muja beserta mata kuliah yang mereka ambil, seperti Aplikasi Berbasis Platform hingga Computing Project. Di dalam kode juga terdapat komentar HTML yang berisi informasi identitas mahasiswa (NIM dan Modul) sebagai dokumentasi internal tanpa muncul di tampilan browser. Struktur ini diakhiri dengan tag penutup `</table>` untuk memastikan dokumen HTML valid dan terstruktur dengan benar.