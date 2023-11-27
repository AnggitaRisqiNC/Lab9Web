# Lab9Web
Nama : Anggita Risqi Nur Clarita

NIM : 312210450

Kelas : TI.22.A.4

## DAFTAR ISI <br>
| No | Description | Link |
|-----|------|-----|
|1|Modul Praktikum 9|[Click Here](https://drive.google.com/file/d/1s2FOb4ygoEB8ufw4leAgNVEENOgLbcZ7/view)|
|2|Instruksi Praktikum|[Click Here](#instruksi-praktikum)|
|3|Langkah-langkah Praktikum|[Click Here](#langkah-langkah-praktikum)|
|4|Pertanyaan dan Tugas|[Click Here](#pertanyaan-dan-tugas)|

## Praktikum
> ### Instruksi Praktikum
> 1. Persiapkan text editor misalnya **VSCode**.
>
> 2. Buat folder baru dengan nama **lab9_php_modular** pada docroot webserver **(htdocs)**
>
> 3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.

## Langkah-langkah Praktikum
### Jalankan Apache dan MySQL server dari menu XAMPP Control

![image](https://github.com/AnggitaRisqiNC/Lab9Web/blob/main/Screenshot/1.png)


Kemudian buat folder baru dengan nama **lab9_php_modular** pada docroot webserver **(c:\xampp\htdocs)**. Kemudian buka melalui browser dengan mengakses URL: http://localhost/lab9_php_modular/.


![image](https://github.com/AnggitaRisqiNC/Lab9Web/blob/main/Screenshot/2.png)


1. **Buat file baru dengan nama `header.php`**

    ```html
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

2. **Buat file baru dengan nama `footer.php`**

    ```html
            <footer>
                <p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p>
            </footer>
        </div>
    </body>
    </html>
    ```

3. **Buat file baru dengan nama `home.php`**
    
    ```php
    <?php require('header.php'); ?>

    <div class="content">
        <h2>Ini Halaman Home</h2>
        <p>Ini adalah bagian content dari halaman.</p>
    </div>

    <?php require('footer.php'); ?>
    ```

4. **Buat file baru dengan nama `about.php`**

    ```php
    <?php require('header.php'); ?>

    <div class="content">
        <h2>Ini Halaman About</h2>
        <p>Ini adalah bagian content dari halaman.</p>
    </div>

    <?php require('footer.php'); ?>
    ```

    **Output Halaman Home:**

    ![image](https://github.com/AnggitaRisqiNC/Lab9Web/blob/main/Screenshot/3.png)


    **Output Halaman About:**

    ![image](https://github.com/AnggitaRisqiNC/Lab9Web/blob/main/Screenshot/4.png)


### Pertanyaan dan Tugas

Implementasikan konsep modularisasi pada kode program **Praktikum 8** tentang database, sehingga setiap halamannya memiliki template tampilan yang sama.

1. **Buat folder baru dengan nama *lab9_php_praktikum***

    ![image](https://github.com/AnggitaRisqiNC/Lab9Web/blob/main/Screenshot/5.png)


    Setelah itu buat beberapa file sama seperti file-file yang ada pada praktikum 8, untuk script lebih lengkapnya kalian dapat langsung lihat pada folder [lab9_php_praktikum](https://github.com/AnggitaRisqiNC/Lab9Web/tree/main/lab9_php_praktikum).


2. **Hasil Output `koneksi.php`:**

    ![image](https://github.com/AnggitaRisqiNC/Lab9Web/blob/main/Screenshot/6.png)


3. **Hasil Output `home.php`:**

    ![image](https://github.com/AnggitaRisqiNC/Lab9Web/blob/main/Screenshot/7.png)


4. **Hasil Output `tambah.php`:**

    ![image](https://github.com/AnggitaRisqiNC/Lab9Web/blob/main/Screenshot/8.png)

    ![image](https://github.com/AnggitaRisqiNC/Lab9Web/blob/main/Screenshot/9.png)

    ![image](https://github.com/AnggitaRisqiNC/Lab9Web/blob/main/Screenshot/10.png)


5. **Hasil Output `ubah.php` :**

    ![image](https://github.com/AnggitaRisqiNC/Lab9Web/blob/main/Screenshot/11.png)

    ![image](https://github.com/AnggitaRisqiNC/Lab9Web/blob/main/Screenshot/12.png)


6. **Hasil Output `hapus.php` :** 

    ![image](https://github.com/AnggitaRisqiNC/Lab9Web/blob/main/Screenshot/13.png)

## Finish