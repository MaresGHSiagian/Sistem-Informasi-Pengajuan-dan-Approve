# Instalasi dan Konfigurasi Aplikasi

## 1. Install Vendor
Jalankan perintah berikut untuk menginstal dependensi proyek:
```bash
composer install
```

## 2. Migrasi Database
Jalankan perintah berikut untuk menjalankan migrasi database:
```bash
php artisan migrate
```

## 3. Memasukkan Data Dummy (Opsional)
Jika Anda ingin memasukkan data dummy ke dalam database, jalankan perintah berikut:
```bash
php artisan db:seed --class=CreateUsersSeeder
php artisan db:seed --class=SubmissionSeeder
php artisan db:seed --class=CreateVehicleListSeeder
```

## 4. Akun Default
Berikut adalah akun default yang dapat digunakan:

### Akun Admin
- **Email:** admin@admin.com  
- **Password:** admin

### Akun Approval
- **Email:** marespdd@gmail.com  
- **Password:** mares30

### Akun User
- **Email:** arni@gmail.com  
- **Password:** arnii123 (atau bisa mendaftar sendiri)

---
Pastikan semua langkah telah dijalankan dengan benar agar aplikasi dapat berfungsi sebagaimana mestinya.

