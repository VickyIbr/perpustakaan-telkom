<p align="center">
  <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="300" alt="Laravel Logo">
</p>

<h1 align="center">Perpustakaan Digital</h1>

<p align="center">
Project Bootcamp Mandiri – SMK Telkom Sandhy Putra Jakarta  
Uji Kompetensi Keahlian PPLG – 2026
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Laravel-12-red">
  <img src="https://img.shields.io/badge/PHP-blue">
  <img src="https://img.shields.io/badge/MySQL-Database-orange">
  <img src="https://img.shields.io/badge/Bootstrap-5-purple">
</p>

---

# Deskripsi Project

Sistem Informasi Perpustakaan berbasis **Laravel 12** yang dirancang untuk mengelola data buku, pengguna, dan transaksi peminjaman.

Project ini dibuat sebagai bagian dari Bootcamp USK 2026 dan Uji Sertifikasi Kompetensi dengan menerapkan konsep:

- MVC (Model-View-Controller)
- Migration & Seeder
- Middleware (Role-Based Access)
- Authentication System
- CRUD Operations
- Blade Templating Engine

---

# Fitur Sistem

## Admin
- CRUD Data Buku
- CRUD Data User
- CRUD Data Transaksi
- Manajemen Role (Admin & Member)

## Member
- Melihat daftar buku
- Melakukan transaksi peminjaman

---

# Struktur Teknologi

- Laravel 12
- PHP
- MySQL
- Bootstrap 5 (CDN)
- Composer
- XAMPP

---

# Instalasi & Menjalankan Project

## Clone Repository / Download Repository 

```bash
git clone https://github.com/VickyIbr/perpustakaan-telkom.git
cd perpustakaan-telkom
```
### Buka Project
- Buka project Laravel menggunakan **Visual Studio Code**.
- Hapus folder `vendor` (jika masih ada).

### Install Dependency
Jalankan perintah berikut di terminal:

```bash
composer install
```

### Konfigurasi Database
Buka file `.env`, lalu sesuaikan dengan database yang ingin digunakan.
#### 🔹 Opsi 1: Menggunakan SQLite
Ubah bagian berikut di `.env` menjadi sebagai berikut:

```env
DB_CONNECTION=sqlite
# DB_HOST=127.0.0.1
# DB_PORT=3306
# DB_DATABASE=laravel
# DB_USERNAME=root
# DB_PASSWORD=
```

#### 🔹 Opsi 2: Menggunakan MySQL (XAMPP)
Ubah bagian berikut di `.env` menjadi sebagai berikut:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=perpustakaan_digital
DB_USERNAME=root
DB_PASSWORD=
```

### Migrasi & Seeder
Jalankan perintah berikut di terminal:
```bash
php artisan migrate --seed
```

### Jalankan Project
Jalankan perintah berikut di terminal:
```bash
php artisan serve
```

---

<center>

© 2026  
VI · EA · MA  
XII TEL 8 - 32

</center>
