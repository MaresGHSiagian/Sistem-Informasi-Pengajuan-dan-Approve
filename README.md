# Setup dan Instalasi Aplikasi

## 1. Install Vendor

Jalankan perintah berikut untuk menginstal dependensi menggunakan Composer:

```bash
composer install
```

## 2. Konfigurasi Database

Buat database dengan duplikat .env example buat nama menjadi .env
dengan konfigurasi berikut:

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=bca
DB_USERNAME=root
DB_PASSWORD=
```

## 3. Menjalankan Migrasi Database

Jalankan perintah berikut untuk melakukan migrasi database:

```bash
php artisan migrate
```

## 4. Memasukkan Data Dummy (Opsional)

Jika Anda ingin memasukkan data dummy ke dalam database, jalankan perintah berikut:

```bash
php artisan db:seed --class=CreateUsersSeeder
php artisan db:seed --class=SubmissionSeeder
php artisan db:seed --class=CreateVehicleListSeeder
```

## 5. Akun yang Tersedia

Berikut beberapa akun yang dapat digunakan untuk login:

- **Admin:**
  - Email: `admi@admin.com`
  - Password: `admin`
- **Approval:**
  - Email: `marespdd@gmail.com`
  - Password: `mares30`
- **User:**
  - Email: `arni@gmail.com`
  - Password: `arnii123` (atau dapat mendaftar akun baru)

## 6. Menjalankan Aplikasi

Untuk menjalankan aplikasi, gunakan perintah berikut:

```bash
php artisan serve
```

Kemudian akses aplikasi melalui:

```
http://localhost:8000/
```

Pastikan semua langka langka dilakukan dengan benar.
