# Lab-3 | Membuat List, Tabel dan Form

Nama : Tiara Hayatul Khoir

Kelas : TI.24.A.5

NIM : 312410474

Mata Kuliah : Pemrograman Web

### Membuat Dokumen HTML

Saya membuat file `lab4_html_lanjutan.html` berisi struktur dasar HTML dengan tag `<html>`, `<head>`, dan `<body>`.
Dokumen ini menjadi wadah utama untuk menampilkan contoh List, Table, dan Form.

### Membuat Ordered, Unordered, dan Form List
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

#### Tampilan Web
![Gambar Tampilan](https://github.com/tir890/Lab3Web/blob/788efe465c00edea140ad8666634bdd8c5f4f3ac/Lab3Web/empat.png)

### Membuat Tabel

Untuk membuat tabel buatlah file baru dengan nama lab3_tabel.html.
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
