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
<br> 
<img width="416" height="434" alt="image" src="https://github.com/user-attachments/assets/628ea32d-6131-4789-a52d-d77198599835" />
<br>
<img width="503" height="502" alt="image" src="https://github.com/user-attachments/assets/5bf01deb-9bb2-4de1-b9dc-cfd0419e403f" />
<br>
<img width="651" height="383" alt="image" src="https://github.com/user-attachments/assets/089f66a6-b77e-4ebd-b1e0-eb3bcc9bfcec" />

- Screenshot Form Input
<img width="651" height="499" alt="image" src="https://github.com/user-attachments/assets/d87dfa4f-d790-43eb-8887-9b4378197e2d" />

- Screenshot Form
<img width="651" height="487" alt="image" src="https://github.com/user-attachments/assets/c2bd898e-cac8-4984-b335-8ea653fff554" />
<img width="640" height="196" alt="image" src="https://github.com/user-attachments/assets/a9568078-ee4c-4eb5-b958-8475724b0059" />

- Screenshot Mobil
<img width="577" height="457" alt="image" src="https://github.com/user-attachments/assets/c7419968-e42f-4063-868f-2be3aa41da08" />

<img width="496" height="300" alt="image" src="https://github.com/user-attachments/assets/b98fc1d0-7c40-431b-a92a-b505cd2f0dfd" />

