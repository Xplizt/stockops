# StockOps - Inventory Management System
## Cara Menginstall
1. Unduh Sumber Kode dan Database\
Silakan unduh sumber kode dan database dari repo github ini.

2. Persiapan Alat\
Jika Anda belum memiliki MySQL atau XAMPP (untuk Windows), atau MAMP (untuk macOS), unduh dan instal salah satu dari program tersebut.

3. Buat Database\
Setelah program terinstal, buatlah database dengan nama stock, lalu impor file database yang telah diunduh. (folder DATABSE_FILE -> unzip stock.zip)\ ![db](https://github.com/user-attachments/assets/7911d130-a0e4-40f8-a187-28d64b577578)


4. Letakkan Code dalam XAMPP\
Jika database sudah berhasil diimpor, salin sumber kode yang telah diunduh ke folder htdocs yang terletak di direktori XAMPP atau MAMP.

5. Konfigurasi File config.php\
Buka file ~/application/config/config.php. Di dalam file tersebut, Anda akan menemukan site_url, yang merupakan array global. Ganti localhost:8888/stockops dengan nomor port yang sesuai dengan sistem Anda. Misalnya, jika Anda menggunakan localhost:8080/stockops, ubah ke nomor port tersebut atau ubah hanya menjadi https://localhost/stockops

6. Konfigurasi File database.php\
Buka folder applications >> config >> database.php. Periksa apakah nama database yang dibuat sudah sesuai. Jika Anda menggunakan username dan password database yang berbeda di sistem Anda, ubah bagian username dan password agar sesuai. (biasanya username: 'root'; password: '')

7. Akses di Browser\
Setelah semua file berhasil diinstal dan dikonfigurasi, buka browser Anda, lalu ketik url sesuai dengan yang Anda masukkan di config.php. Halaman tersebut seharusnya mengarahkan Anda ke halaman login.

Kredensial admin:\
admin@admin.com\
password
