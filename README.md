# Lab-3 | Membuat List, Tabel dan Form

Nama : Tiara Hayatul Khoir

Kelas : TI.24.A.5

NIM : 312410474

Mata Kuliah : Pemrograman Web

### Membuat Folder HTML
Saya membuat file **Lab3Web** berisi struktur dasar HTML folder ini menjadi wadah utama untuk menampilkan contoh List, Table, dan Form.

### Membuat Ordered, Unordered, dan Description List
Membuat dokumen HTML dengan nama **file lab3_list.html**.
Menambahkan tiga jenis list pada HTML:
- Unordered List (`<ul>`) → daftar dengan simbol
- Ordered List (`<ol>`) → daftar bernomor
- Description List (`<dl>`) → daftar dengan keterangan

```html
<section id="order-list"> 
 <h2>Ordered List</h2> 
 <ol> 
 <li>Pemrograman Web</li> 
 <li>Sistem Informasi</li> 
 <li>Basis Data 2</li> 
 </ol> 
</section>

<section id="unorder-list"> 
 <h2>Unordered List</h2> 
 <ul type="square"> 
 <li>Jaringan Komputer</li> 
 <li>Struktur Data</li> 
 <li>Algoritma &amp; Pemrograman</li> 
 </ul> 
</section>

<section id="unorder-list"> 
 <h2>Description List</h2> 
 <dl> 
 <dt>Fakultas Teknik</dt> 
 <dd>Teknik Industri</dd> 
 <dd>Teknik Informatika</dd> 
 <dd>Teknik Lingkungan</dd> 
 <dt>Fakultas Ekonomi dan Bisnis</dt> 
 <dd>Akuntansi</dd> 
 <dd>Manajemen</dd> 
 <dd>Bisnis Digital</dd> 
 </dl> 
</section>
```

### Tampilan Web Ordered, Unordered, dan Description List
![Gambar Tampilan](https://github.com/tir890/Lab3Web/blob/788efe465c00edea140ad8666634bdd8c5f4f3ac/Lab3Web/empat.png)

### Membuat Tabel

Untuk membuat tabel buatlah file baru dengan nama **lab3_tabel.html**.
Lalu tambahkan elemen `<table>` untuk menyajikan data dalam bentuk baris dan kolom menggunakan tag `<tr>`, `<th>`, dan `<td>`.

```html
<!DOCTYPE html> 
<html lang="en"> 
<head> 
 <meta charset="UTF-8"> 
 <meta name="viewport" content="width=device-width, initial-scale=1.0">  <title>HTML Lanjutan</title> 
</head> 
<body> 
 <header> 
 <h1>Membuat Table</h1> 
 </header> 
</body> 
</html>
```

Kode yang digunakan untuk penggabungan sel data, dengan menggunakan atribut `<rowspan>` dan `<colspan>`.

```html
<table border="1" cellpadding="6" cellspacing="0"> 
 <thead> 
 <tr> 
 <th>No.</th> 
 <th>Fakultas</th> 
 <th>Program Studi</th> 
 </tr> 
 </thead> 
 <tbody> 
 <tr> 
 <td>1.</td> 
 <td rowspan="3">Teknik</td> 
 <td>Teknik Informatika</td> 
 </tr> 
 <tr> 
 <td>2.</td> 
 <td>Teknik Industri</td> 
 </tr> 
 <tr> 
 <td>3.</td> 
 <td>Teknik Lingkungan</td> 
 </tr> 
 </tbody> 
</table>
```

### Tampilan Web Tabel
![Tampilan Tabel](https://github.com/tir890/Lab3Web/blob/fbe8f0b137183736a393b612da0d0c9665e5f1d8/Lab3Web/enam.png)

### Membuat Form
Sama seperti langkah-langkah sebelumnya yaitu membuat file baru dengan nama **lab3_form.html**. 
Membuat form HTML untuk menerima input pengguna menggunakan tag `<form>`.
Elemen yang digunakan:
- `<input type="text">` untuk teks
- `<input type="password">` untuk sandi
- `<input type="submit">` untuk tombol kirim

```html
<!DOCTYPE html> 
<html lang="en"> 
<head> 
 <meta charset="UTF-8"> 
 <meta name="viewport" content="width=device-width, initial-scale=1.0">  <title>HTML Lanjutan</title> 
</head> 
<body> 
 <header> 
 <h1>Membuat List</h1> 
 </header> 
</body> 
</html>

<form action="proses.php" method="post"> 
 <fieldset> 
 <legend>Data Pelanggan</legend> 
 <p> 
 <label for="nama">Nama</label> 
 <input type="text" id="nama" name="nama"> 
 </p> 
 <p> 
 <label for="alamat">Alamat</label> 
 <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>  </p> 
 <p> 
 <label>Jenis Kelamin</label> 
 <input id="jk_l" type="radio" name="kelamin" value="L" /><label for="jk_l">Laki-laki</label> 
 <input id="jk_p" type="radio" name="kelamin" value="P" /><label

for="jk_p">Perempuan</label> 
 </p> 
 <p><input type="submit" value="Login"></p> 
 </fieldset> 
</form>
```

Yang terakhir adalah menambahkan kode CSS agar tampilan web menjadi berwarna dan interaktif.

```css
<style> 
 form p > label { 
 display: inline-block; 
 width: 100px; 
 } 
 form input[type="text"], form textarea { 
 border: 1px solid #197a43; 
 } 
 form input[type="submit"] { 
 border: 1px solid #197a43; 
 background-color: #197a43; 
 color: #ffffff; 
 font-weight: bold; 
 padding: 5px 15px; 
 } 
</style>
```

### Tampilan Web Formulir
![Gambar Tampilan Formulir](https://github.com/tir890/Lab3Web/blob/98ab8fdb3cbf12f626eb234e2e362e96954586f3/Lab3Web/delapan.png)
