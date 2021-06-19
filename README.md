# NibiruWorld Sosmed 

## Apa itu NibiruWorld Sosmed?
NibiruWorld Sosmed adalah sebuah aplikasi sosial media sederhana yang dibuat menggunakan CodeIgniter4.0.3 dan Bootstrap 4.

## Cara Instalasi NibiruWorld Sosmed
- Pastikan composer terinstall.
- Pastikan versi PHP yang terinstall adalah versi `7.3` ke atas.
- Jalankan `composer install`.
- Ubah file `env` menjadi `.env`, atau gunakan konfigurasi milik Anda sendiri.
- Konfigurasikan email Anda di `App\Config\Email.php`, ubah isi property `$SMTPUser` dengan email Anda dan `$SMTPPass` dengan password email Anda.
- Buat database bernama `nibiruworld`.
- Import database dari file sql yang sudah disertakan dalam repository.
- Jalankan `php spark serve`.
- Akun default yang tersedia untuk login:

  ### SuperAdmin:
  - Username: superadmin
  - Password: superadmin123
  
  ### Admin:
  - Username: admin
  - Password: admin123

  ### User:
  - Username: user
  - Password: user1234

## Bantuan
Jika Anda membutuhkan bantuan, hubungi saya di email: andrypeb27@protonmail.com atau andrypeb227@gmail.com.
