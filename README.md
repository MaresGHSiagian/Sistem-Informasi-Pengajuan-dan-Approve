1. Install Vendor dengan " Composer Install"


2. Jalankan perintah berikut untuk menjalankan migrasi database:
   php artisan migrate
   Langkah
   Memasukkan Data Dummy (Opsional)
   Jika Anda ingin memasukkan data dummy ke dalam database, Anda dapat menjalankan perintah berikut:
   php artisan db:seed --class=CreateUsersSeeder
   php artisan db:seed --class=SubmissionSeeder
   php artisan db:seed --class=CreateVehicleListSeeder


