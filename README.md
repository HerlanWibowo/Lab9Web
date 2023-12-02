## Pemograman Web 1

## Praktikum-9

### Langkah Langakah Praktikum

#### 1. Buat file php dengan nama <b>header.php</b>
Memasukkan code html untuk header yaang berisi navbar
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Contoh Modularisasi</title>
    <link href="style.css" rel="stylesheet" type="text/stylesheet" media="screen" />
</head>

<body>
    <div class="container">
        <header>
            <h1>Modularisasi Menggunakan Require</h1>
        </header>
        <nav>
            <a href="home.php">Home</a>
            <a href="about.php">Tentang</a>
            <a href="kontak.php">Kontak</a>
        </nav>
```
![header](/image/header.png)
#### 2. Buat file php dengan nama <b>footer.php</b>
Memasukkan code html untuk footer yang akan digabungkan dengan header
```
        <footer>
            <p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p>
        </footer>
    </div>
</body>

</html>
```
![footer](/image/footer.png)
#### 3. Buat file php dengan nama <b>home.php</b>
Menambahkan header dan footer kedalam file home.php dengan function require()
```
<?php require('header.php');?>

<div class="content">
    <h2>Ini adalah Home</h2>
    <p>Ini adalah bagian content dari halaman</p>
</div>
<?php require('footer.php');?>
``` 
![home](/image/home.png)
#### 4. Buat file php dengan nama <b>about.php</b>
Menambahkan header dan footer kedalam file about.php dengan function require()
```
<?php require('header.php'); ?>
<div class="content">
    <h2>Ini Halaman About</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>
<?php require('footer.php'); ?>
```
![about](/image/about.png)
### Tugas dan Pertanyaan
Implementasikan konsep modularisasi pada kode program praktikum 8 tentang
database, sehingga setiap halamannya memiliki template tampilan yang sama.
- Source Code
  
      Saya memasukkann baris kode file tambah.php dan ubah.php pada index.php dengan function require_once()
      begitu pula pada file tambah.php dan ubah.php sehingga setiap halaman memiliki tampilan yang sama
![tugas](/image/code%20Tugas.png)

- Output

![outputTugas](/image/Tugas.png)
# Terima kasih!
