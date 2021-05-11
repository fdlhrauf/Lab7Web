# Lab7Web
# Pengantar PHP
PHP adalah singkatan dari PHP Hypertext Prepocessor dan merupakan bahasa pemrograman yang di desain khusus untuk web development atau pengembangan web. PHP memiliki sifat Server-Side karena PHP dijalankan atau di eksekusi dari sisi server. maksud di jalankan dari sisi server adalah PHP di jalankan pada komputer server dan bukan pada komputer client. PHP di jalankan melalui aplikasi web browser sama halnya seperti HTML. Hampir semua situs-situs besar dan populer di kembangkan menggunakan PHP. seperti misalnya wordpress, joomla, facebook, twitter, wikipedia dan situs besar lainnya.

# Intruksi Praktikum
1. Persiapkan text editor misalnya Sublime text
2. Buat folder batu dengan nama lab7_php_dasar pada docroot webserver (htdocs)
3. Ikuti Langkah-langkah yang dijelaskan berikut.

# Langkah-langkah Praktikum
# Persiapan
Untuk memulai membuat kode php, perlu disiapkan web server dan interpreter PHP terlebih dahulu. Web servar yang kita gunakan adalah Apache 2 dan interpreter PHP 7. Untuk memudahkan proses praktikum, kita gunakan aplikasi bundle web server yaitu XAMPP.

# Install XAMPP
Unduh XAMPP dari https://www.apachefriends.org/download.html dan pilih versi portable untuk memudahkan proses installasi. Kemudian extract file tersebut, seusikan direktorinya (misal: c:\xampp).

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Screenshoot/1.JPG)

# Konfigurasi Web Server
* Konfigurasi Apache : Untuk konfigurasi HTTP server, seperti port yang digunakan akses HTTP, modul yang diaktifkan, lokasi document root, dll. Lokasi file: \xampp\apache\conf\httpd.conf

* Konfigrasi PHP : Untuk konfigurasi perilaku engine PHP yang berefek pada keamanan dan performa.Seperti batas maksimal waktu eksekusi script, batas file yang dapat diupload, error reporting, dll. Lokasi file: \xampp\php\php.ini

* Konfigrasi MySql : Konfigurasi server MySQL, seperti administrator user, port, timezone, dll.
Lokasi file: \xampp\mysql\bin\my.ini
# Menjalankan Web Server
Untuk menjalankan web server dari menu XAMPP Control.

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Screenshoot/3.JPG)

* Uji coba apakah server sudah bekerja dengan baik
http://127.0.0.1 atau http://localhost

Tampil halaman utama XAMPP jika server sudah bekerja dengan baik.

* Dokumen Website
 Semua file website tempatkan di rektori : \xampp\htdocs\
 
* Database MySQL
Direktori : \xampp\mysql\

Manajemen database : http://localhost/phpmyadmin

# Memulai PHP
Buatlah folder lab7_php_dasar pada root directory web server (c:\xampp\htdocs)

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Screenshoot/2.JPG)

Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL : htpp://localhost/lab7_php_dasar/

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Screenshoot/4.JPG)

# PHP Dasar
Buatlah file baru dengan nama file php_dasar.php

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Screenshoot/55.JPG)

Kemudian untuk mengakses hasilnya melalui URL : lab7_web_dasar/php_dasar.php

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Screenshoot/5.JPG)

# Variable PHP
Menambahkan variable pada program

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Screenshoot/6.JPG)

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Screenshoot/7.JPG)

# Predefine Variablr $_GET 

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Screenshoot/8.JPG)

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Screenshoot/9.JPG)

# Membuat Form Input

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Screenshoot/10.JPG)

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Screenshoot/11.JPG)

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Screenshoot/12.JPG)

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Screenshoot/13.JPG)

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Screenshoot/14.JPG)

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Screenshoot/15.JPG)

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Screenshoot/16.JPG)

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Screenshoot/switch.JPG)

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Screenshoot/19.JPG)

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Screenshoot/20.JPG)

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Screenshoot/21.JPG)

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Screenshoot/22.JPG)

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Screenshoot/23.JPG)

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Screenshoot/24.JPG)


# T U G A S

Buatlah program PHP sederhana dengan menggunakan form input yang menampilkan nama, tanggal lahir dan pekerjaan. Kemudian tampilkan outputnya dengan menghitung umur berdasarkan inputan tanggal lahir. Dan pilihan pekerjaan dengan gaji yang berbeda-beda sesuai pilihan pekerjaan.

# Langkah - Langkah

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Tugas/01.JPG)

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Tugas/02.JPG)

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Tugas/033.JPG)

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Tugas/input.JPG)

![imag](https://github.com/fdlhrauf/Lab7Web/blob/main/Tugas/input2.JPG)


Nama : Siti Fadillah Rauf
Kelas : TI.19.A.1
NIM : 311910206
