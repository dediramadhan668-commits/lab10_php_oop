# Lab 10 PHP OOP

Nama: Dedi Ramadhan
NIM: 312410171
Kelas: TI 24 A1

## 1. Persiapan Awal
- Membuka text editor VSCode.
- Membuat folder baru dengan nama lab10_php_oop di dalam direktori htdocs.

## 2. File mobil.php
File ini berisi contoh dasar penerapan OOP di PHP.
Isi dan fungsi file:
- Class Mobil memiliki property privat warna, merk, dan harga.
- Konstruktor memberi nilai awal pada property.
- Method gantiWarna() mengubah warna.
- Method tampilWarna() menampilkan warna.
- Dua objek dibuat yaitu a dan b.
- Setiap objek memakai method untuk mengubah dan menampilkan warna.

## 3. File form.php
File ini berupa class library untuk membuat form input HTML secara dinamis.
Isi dan fungsi:
- Menyimpan konfigurasi form.
- Method addField() untuk menambah field.
- Method displayForm() untuk menampilkan form.
- Bersifat library dan tidak dieksekusi langsung.

## 4. File form_input.php
File ini memakai class Form dari form.php.
Langkah:
- Melakukan include terhadap form.php.
- Membuat objek Form baru.
- Menambahkan field Nim, Nama, dan Alamat.
- Menampilkan form HTML melalui displayForm().

## 5. File database.php
File ini merupakan library untuk koneksi database dan operasi CRUD sederhana.
Fitur:
- Konstruktor membuat koneksi ke database.
- Method query() menjalankan query bebas.
- Method get() mengambil data.
- Method insert() menambah data.
- Method update() memperbarui data.
- Method delete() menghapus data.

## 6. Implementasi Modularisasi
Semua komponen dipisah menjadi beberapa file:
- mobil.php untuk class dasar.
- form.php untuk library form.
- database.php untuk koneksi database.
- form_input.php sebagai implementasi form.
- config.php untuk konfigurasi.
Struktur modular membuat kode lebih rapi dan mudah dipelihara.

## 7. Repository GitHub
Semua file, screenshot, dan README diunggah ke repository GitHub dengan nama:
Lab10Web

## 8. Kesimpulan
Pada praktikum ini dipelajari:
- Konsep dasar OOP seperti class, property, method, dan object.
- Cara membuat class sederhana di PHP.
- Pembuatan class library dan penggunaannya pada file lain.
- Modularisasi kode dengan memisahkannya ke beberapa file.
- Dasar class untuk koneksi database.

## 9. Daftar File
lab10_php_oop/
├── mobil.php
├── form.php
├── form_input.php
├── database.php
├── config.php
└── README.md

## 10. Dokumentasi
- Screenshot Database
  <img width="416" height="434" alt="image" src="https://github.com/user-attachments/assets/628ea32d-6131-4789-a52d-d77198599835" />
  

- Screenshot Form Input
- Screenshot Form
- Screenshot Mobil
