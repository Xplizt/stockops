# StockOps - Inventory Management System
## Cara Menginstall
1. Unduh Sumber Kode dan Database\
Silakan unduh sumber kode dan database dari repo github ini.

2. Persiapan Alat\
Jika Anda belum memiliki MySQL atau XAMPP (untuk Windows), atau MAMP (untuk macOS), unduh dan instal salah satu dari program tersebut.

3. Buat Database\
Setelah program terinstal, buatlah database dengan nama stock, lalu impor file database yang telah diunduh. (folder DATABSE_FILE -> unzip stock.zip) \
![db](https://github.com/user-attachments/assets/7911d130-a0e4-40f8-a187-28d64b577578)

5. Letakkan Code dalam XAMPP\
Jika database sudah berhasil diimpor, salin sumber kode yang telah diunduh ke folder htdocs yang terletak di direktori XAMPP atau MAMP.

6. Konfigurasi File config.php\
Buka file ~/application/config/config.php. Di dalam file tersebut, Anda akan menemukan site_url, yang merupakan array global. Ganti localhost:8888/stockops dengan nomor port yang sesuai dengan sistem Anda. Misalnya, jika Anda menggunakan localhost:8080/stockops, ubah ke nomor port tersebut atau ubah hanya menjadi https://localhost/stockops \
![image](https://github.com/user-attachments/assets/eaaa2767-2760-4abe-841e-82faa3cf44e9) \
![image](https://github.com/user-attachments/assets/2ad1cd6b-1c64-41de-b115-5838b05b8706)


7. Konfigurasi File database.php\
Buka folder applications >> config >> database.php. Periksa apakah nama database yang dibuat sudah sesuai. Jika Anda menggunakan username dan password database yang berbeda di sistem Anda, ubah bagian username dan password agar sesuai. (biasanya username: 'root'; password: '')\
![image](https://github.com/user-attachments/assets/47441412-4947-4e71-9b7c-936ab3557b88) \
![image](https://github.com/user-attachments/assets/044bd0d9-e16b-4901-adcc-5edb03eb6f30)



9. Akses di Browser\
Setelah semua file berhasil diinstal dan dikonfigurasi, buka browser Anda, lalu ketik url sesuai dengan yang Anda masukkan di config.php. Halaman tersebut seharusnya mengarahkan Anda ke halaman login.

Kredensial admin:\
admin@admin.com\
password
