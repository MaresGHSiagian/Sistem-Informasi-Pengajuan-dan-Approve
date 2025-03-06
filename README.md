# Instalasi dan Konfigurasi

## 1. Install Vendor

Jalankan perintah berikut untuk menginstall vendor menggunakan Composer:

```sh
composer install
```

## 2. Jalankan Migrasi Database

Untuk menjalankan migrasi database, gunakan perintah berikut:

```sh
php artisan migrate
```

## 3. Memasukkan Data Dummy (Opsional)

Jika ingin memasukkan data dummy ke dalam database, jalankan perintah berikut:

```sh
php artisan db:seed --class=CreateUsersSeeder
php artisan db:seed --class=SubmissionSeeder
php artisan db:seed --class=CreateVehicleListSeeder
```

## 4. Akun Default

Berikut adalah akun default yang tersedia:

### Akun Admin:

- **Email:** [admin@admin.com](mailto\:admin@admin.com)
- **Password:** admin

### Akun Approval:

- **Email:** [marespdd@gmail.com](mailto\:marespdd@gmail.com)
- **Password:** mares30

### Akun User:

- **Email:** [arni@gmail.com](mailto\:arni@gmail.com)
- **Password:** arnii123 *(atau akun bisa didaftar)*

## 5. Mengakses Aplikasi

Untuk menjalankan pengajuan, kunjungi URL berikut di browser:

```
http://localhost:8000/
```

Pastikan semua langka langka dilakukan dengan benar
