<div align="center">
  <br>

  <h1>LAPORAN PRAKTIKUM <br>
  APLIKASI BERBASIS PLATFORM
  </h1>

  <br>

  <h3>MODUL 2 <br>
  HTML
  </h3>

  <br>

  <img src="asset/telyu.png"/>



  <br>
  <br>
  <br>

  <h3>Disusun Oleh :</h3>

  <p>
    <strong>Irshad Benaya Fardeca</strong><br>
    <strong>2311102199</strong><br>
    <strong>S1 IF-11-REG01</strong>
  </p>

  <br>

  <h3>Dosen Pengampu :</h3>

  <p>
    <strong>Dimas Fanny Hebrasianto Permadi, S.ST., M.Kom</strong>
  </p>
  
  <br>
  <br>
    <h4>Asisten Praktikum :</h4>
    <strong>Apri Pandu Wicaksono </strong> <br>
    <strong>Rangga Pradarrell Fathi</strong>
  <br>

  <h3>LABORATORIUM HIGH PERFORMANCE
 <br>FAKULTAS INFORMATIKA <br>UNIVERSITAS TELKOM PURWOKERTO <br>2026</h3>
</div>
<hr>

# Dasar Teori
## 3.1 Pengenalan HTML
HTML atau HyperText Markup Language merupakan bahasa dasar yang digunakan untuk membangun sebuah web dimana HTML menangani elemen-elemen dasar pada pembangunan sebuah website. 
Struktur HTML paling dasar adalah sebagai berikut:
<img src="asset/struktur.png"/>

### 3.1.1 Tag HTML
Tag dalam HTML secara normal memiliki sepasang tag di mana tag pertama merupakan tag pembuka dan yang kedua merupakan tag penutup. 
Konten yang ingin ditampilkan pada laman web diletakkan di antara kedua tag tersebut.
```
<nama_tag> letakkan konten di sini ... </nama_tag>
```
Tag dalam HTML tidak semuanya berbentuk pasangan, ada beberapa tag yang hanya berdiri sendiri seperti
tag “<br/>” yang berguna untuk berpindah baris.

### 3.1.2 Elemen HTML
Elemen HTML merupakan tag HTML yang telah memiliki konten atau isi di antara kedua tag pembuka dan penutupnya. 
Elemen HTML dapat berupa teks atau juga dapat menyisipkan tag HTML lain pada elemen tersebut.
```
<!DOCTYPE html>
<html> 
<head> 
 <!-- Contoh elemen berisi tag lain --> 
 <title>Page Title</title> 
</head> asdff 
<body> 
 <h1>My First Heading</h1>  
 <!-- Contoh Elemen berisi Teks -->  
 <p>My first paragraph.</p> 
</body>
</html>
```

### 3.1.3 Atribut HTML
Atribut HTML merupakan tambahan informasi dari sebuah tag HTML. 
Bentuk atribut untuk setiap tag HTML berbeda-beda sehingga kegunaan atribut juga berbeda seperti menambahkan informasi warna elemen, ukuran lebar, ukuran panjang dan lain-lain. 
Namun, mayoritas atribut yang sering muncul untuk setiap tag HTML adalah atribut “id” dan “class” karena kedua atribut ini berperan besar dalam pengembangan laman web dengan CSS dan JavaScript. 
Atribut HTML dideklarasikan di dalam tag pembuka pada setiap elemen HTML dengan format nama_atribut=”value”, setiap nilai atribut diapit oleh petik dua.
```
<a href=”www.google.co.id” > Google.co.id </a> 
<input type=”button” id=”btnSubmit” class=”btnSubmit1” value=”Kirim”/> 
```

## 3.2 Dasar sintaks
Seperti yang sudah dijelaskan sebelumnya struktur dasar HTML antara lain berupa:
```
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
• Deklarasi <! DOCTYPE html> mendefinisikan dokumen menjadi HTML5
• Elemen <html> adalah elemen dasar dari halaman HTML
• Elemen <head> berisi informasi meta tentang dokumen
• Elemen <title> menentukan judul untuk dokumen
• Elemen <body> berisi konten halaman yang terlihat


## 3.3 Heading
Heading pada HTML merupakan tag yang berguna untuk menampilkan judul dari konten laman web yang dibangun. 
Heading dalam sebuah laman web berperan penting untuk aplikasi mesin pencarian karena sistem mesin pencarian bekerja dengan menggunakan Heading laman web kita sebagai index pencarian. 
Dalam HTML terdapat enam tingkatan Heading di mana semakin kecil nilai heading nya maka semakin penting dan semakin besar ukurannya pada laman web.
```
<h1>Heading 1</h1>  
<h2>Heading 2</h2>  
<h3>Heading 3</h3>  
<h4>Heading 4</h4> 
<h5>Heading 5</h5>
<h6>Heading 6</h6>  
```
<img src="asset/heading.png"/>

## 3.4 Hyperlink
Hyperlink dalam HTML memungkinkan halaman web berpindah laman atau bernavigasi menuju laman web yang lain. 
Tag yang digunakan adalah tag ```<a>...</a>```
```
<a href="www.google.co.id"> Visit Google </a> 
```
Dalam tag Hyperlink pada HTML ada satu atribut yang harus digunakan agar konten yang ada di antara tag hyperlink berjalan dan dapat melakukan navigasi menuju laman web lain yaitu atribut href. 
Atribut ini bernilai url atau alamat dari laman web tujuan.

## 3.5 Tabel
Tabel pada HTML merupakan salah satu elemen penting khususnya digunakan untuk menampilkan data yang membutuhkan bentuk tabel. 
Tabel pada HTML didefinisikan dengan tag <table></table> dengan setiap pendefinisian baris menggunakan tag <tr></tr>, pendefinisian heading tabel menggunakan tag <th></th> dan pendefinisian kolom menggunakan tag <td></td>.
```
<table width=”80%” height=”50%” border="1"> 
 <tr> 
 <th>Nama Lengkap</th> 
 <th>Kota Kelahiran</th> 
 <th>Age</th> 
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
 <tr> 
 <td>Rasyid</td> 
 <td>Surabaya</td> 
 <td>22</td> 
 </tr> 
</table> 
```
<img src="asset/tabel1.png"/>

Dalam tabel HTML kita dapat melakukan operasi Merge Cell yang biasanya dapat dilakukan pada aplikasi perkantoran seperti Microsoft Word atau Excel dengan cara menambahkan atribut colspan dan rowspan pada tag pembuka kolom yaitu <td> nilai dari atribut tersebut berupa jumlah kolom atau baris yang akan djgabungkan.
```
<table width=”80%” height=”50%” border="1"> 
 <tr> 
 <th rowspan="2">Nama Lengkap</th> 
 <th colspan="2">Gelar Pendidikan</th> 
 <th rowspan="2">Age</th> 
 </tr> 
 <tr> 
 <th> Sarjana </th> 
 <th> Magister </th> 
 </tr> 
 <tr> 
 <td>Budi</td> 
 <td>S.Kom</td> 
 <td>M.Sc</td> 
 <td>35</td> 
 </tr> 
 <tr> 
 <td>Andi</td> 
 <td>S.SiKom</td> 
 <td>M.T</td> 
 <td>52</td> 
 </tr> 
</table>
```
<img src="asset/tabel2.png"/>

## 3.6 Image
Menampilkan gambar pada halaman web merupakan sebuah improvisasi dalam pembuatan desain sebuah web yang dapat memperindah tampilan website. 
Tag HTML yang digunakan adalah <img/> tag ini tidak memiliki pasangan penutup maka dari itu diakhir tag pembuka ditambahkan garis miring seperti di atas.Terdapat satu atribut wajib yang harus ditambahkan seperti atribut href pada tag Hyperlink yaitu atribut src yang bernilai alamat direktori gambar disimpan.
```
<img src="gundam.jpg" width="50%" height="50%"/> 
<p>Ini Gambar Gundam</p> 
```
<img src="asset/gundam.png"/>

## 3.7 Audio / Video Elemen
Sebelum berkembangnya teknologi HTML5, untuk menyisipkan audio atau video, diperlukan sebuah plugin seperti Flash Player namun sekarang dengan HTML5 memiliki tag yang dapat menyisipkan audio atau video ke dalam laman web. 
Untuk audio menggunakan tag <audio> untuk tag pembuka dan <source> untuk memanggil url atau alamat direktori file. Sedangkan untuk video menggunakan tag <video>.
```
    <audio controls>
        <source src="fah.mp3" type="audio/mpeg">
    </audio>
    <video width="400" controls>
        <source src="caseoh.mp4" type="video/mp4">
    </video>
    <p>
        Video courtesy of
        <a href="https://twitch.tv/caseoh_?sr=a" target="_blank">CaseOh</a>.
    </p>
```
<img src="asset/caseoh.png"/>

## 3.8 Form
Form pada HTML digunakan sebagai wadah untuk menampung dan mengumpulkan data-data dari pengguna jika diperlukan untuk disimpan dalam sebuah database. 
Tag dasar untuk pemanggilan form adalah <form> ... </form> dan diantara tag form tersebut merupakan tempat mendefinisikan elemenelemen yang dibutuhkan form yang akan dibuat nantinya. 
Atribut utama dari tag form yaitu action, atribut ini bernilai tujuan data akan diolah dengan bahasa pemrograman web saat tombol “Submit” ditekan, selain itu atribut method yang hanya bernilai POST atau GET ini juga sangat dibutuhkan untuk pengolahan data dengan bahasa pemrograman web. Pembahasan lebih lanjut ada pada modul PHP.
### 3.8.1. Elemen Form  
Elemen-elemen form pada html adalah sebagai berikut: 
| Tag | Type | Fungsionalitas |
| :--- | :--- | :--- |
| `<input />` | `type="text"` | Input data teks standar satu baris |
| `<input />` | `type="password"` | Input teks dengan karakter yang disamarkan |
| `<input />` | `type="email"` | Input dengan validasi format alamat email |
| `<input />` | `type="radio"` | Pemilihan satu opsi dari beberapa pilihan |
| `<input />` | `type="checkbox"` | Pemilihan satu atau lebih opsi mandiri |
| `<input />` | `type="submit"` | Tombol untuk mengirimkan (submit) data form |
| `<select>` | `<option>` | Menampilkan dropdown list untuk pemilihan data |
| `<textarea>` | - | Input data teks multiline (paragraf panjang) |
| `<button>` | `type="button"` | Menampilkan tombol kustom untuk aksi tertentu |

### 3.8.2. Atribut Elemen Form  
Atribut-atribut elemen form yang sering digunakan antara lain sebagai berikut:  
| Atribut | Value | Fungsionalitas |
| :--- | :--- | :--- |
| `id` | Custom (Unik) | Identitas unik untuk CSS, JavaScript, atau Anchor Link. |
| `name` | Custom | Identitas elemen yang akan dikirimkan ke server/backend. |
| `class` | Custom | Pengelompokan elemen untuk styling CSS atau manipulasi JS. |
| `placeholder` | Teks | Menampilkan petunjuk sementara di dalam field input. |
| `value` | Bebas | Menentukan nilai default atau nilai yang akan dikirim. |
| `disabled` | - | Menonaktifkan elemen agar tidak bisa dioperasikan sama sekali. |
| `readonly` | - | Membiarkan elemen terlihat, tapi isinya tidak bisa diubah. |
| `checked` | - | Memilih Checkbox/Radio secara otomatis saat halaman dimuat. |
| `selected` | - | Menentukan opsi default pada elemen `<select>`. |

```
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Formulir Pendaftaran Praktikan</title>

<style>
body{
    text-align:center;
    font-family: Arial, sans-serif;
}
table{
    margin:auto;
}
</style>

</head>

<body>

<h2>Formulir Pendaftaran Praktikan</h2>

<form action="#" method="POST">

<table>

<tr>
<td><label for="nama_id"><b>Nama:</b></label></td>
<td>:</td>
<td>
<input type="text" name="nama_input" id="nama_id"
placeholder="Input Nama" value="Praktikan" readonly>
</td>
</tr>

<tr>
<td><label for="uname_id"><b>Username:</b></label></td>
<td>:</td>
<td>
<input type="text" name="uname_input" id="uname_id"
placeholder="Input Username" value="Praktikum" disabled>
</td>
</tr>

<tr>
<td><label for="password_id"><b>Password:</b></label></td>
<td>:</td>
<td>
<input type="password" name="password_input" id="password_id"
placeholder="Input Password" required>
</td>
</tr>

<tr>
<td><label for="email_id"><b>Email:</b></label></td>
<td>:</td>
<td>
<input type="email" name="email_input" id="email_id"
placeholder="Input Email" required>
</td>
</tr>

<tr>
<td><b>Jenis Kelamin:</b></td>
<td>:</td>
<td>
<input type="radio" name="jk_input" id="pria" value="Pria">
<label for="pria">Pria</label>

<input type="radio" name="jk_input" id="wanita" value="Wanita">
<label for="wanita">Wanita</label>
</td>
</tr>

<tr>
<td><b>Hobi:</b></td>
<td>:</td>
<td>

<input type="checkbox" name="hobi_input[]" id="renang" value="Renang">
<label for="renang">Renang</label><br>

<input type="checkbox" name="hobi_input[]" id="bersepeda" value="Bersepeda">
<label for="bersepeda">Bersepeda</label><br>

<input type="checkbox" name="hobi_input[]" id="memancing" value="Memancing">
<label for="memancing">Memancing</label>

</td>
</tr>

<tr>
<td><label for="jp_id"><b>Jenjang Pendidikan:</b></label></td>
<td>:</td>
<td>

<select name="jp_input" id="jp_id">
<option value="" selected disabled>------Pilih------</option>
<option value="D3">Tamat D3</option>
<option value="S1">Tamat S1</option>
<option value="S2">Tamat S2</option>
<option value="S3">Tamat S3</option>
</select>

</td>
</tr>

<tr>
<td><label for="kritik_saran"><b>Kritik & Saran:</b></label></td>
<td>:</td>
<td>
<textarea id="kritik_saran" name="kritik_saran" rows="5" cols="30"></textarea>
</td>
</tr>

<tr>
<td colspan="3" align="right">

<input type="reset" value="Cancel">
<input type="submit" value="Submit">

</td>
</tr>

</table>

</form>

</body>
</html>
```
<img src="asset/formulir.png"/>

## Unguided 
### 1. Buat tampilan table dasar namun harus di tengah layar/center dan tidak boleh menggunakan css atau styling atau apapun itu.

### Source Code
```html
<!-- Irshad Benaya Fardeca -->
<!-- 2311102199 -->
<!-- S1IF-11-01 -->

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tugas 2</title>
</head>

<body>
    <!-- tabel -->
    <table border="1" align="center">
        <tr>
            <th>Nama</th>
            <th>NIM</th>
            <th>Kelas</th>
        </tr>
        <tr>
            <td>Irshad Benaya F</td>
            <td>2311102199</td>
            <td>IF-11-01</td>
        </tr>
        <tr>
            <td>Andika Neviantoro</td>
            <td>2311102167</td>
            <td>IF-11-01</td>
        </tr>
        <tr>
            <td>Mohammad Alfan N</td>
            <td>2311102170</td>
            <td>IF-11-01</td>
        </tr>
    </table>
</body>

</html>
```

### Output:
<img src="asset/output.png"/>