# Project-updating-data-database-python
This project about updating data in database in python (In Indonesia)

Updating Data in Database: 
- Menggunakan perintah update
- Mirip dengan pernyataan penyisipan tetapi menyertakan klausa tempat untuk menentukan catatan apa yang akan diperbarui
- Tambahkan semua nilai yang ingin kita perbaharui dengan klausa nilai sebagai columns=value

Updating One Row:
Misalkan disini kita ingin memberikan nilai  = True pada kolom active dengan kondisi dimana nilai kolom id = 3.
Pertama, kita harus meng-import fungsi update dari SQLAlchemy terlebih dahulu. Kemudian dilanjutkan dengan penulisan query SQL.
Perintah rowcount disini digunakan hanya untuk melihat data baru yang kita ubah.

Inserting Multiple Rows:
Sebagai contoh yang kedua, kita akan mengupdate data salary dengan nilai 0.00 untuk kondisi kolom active = True.

Correlated Updates:
- Menggunakan perintah select() untuk mendapatkan nilai dari kolom yang akan kita update
- Biasa digunakan untuk memperbarui records ke nilai maksimum atau mengubah string agar cocok dengan singkatan dari tabel lain
Misalkan kita ingin memperbarui nilai salary menjadi nilai yang terbesar dari kolom tersebut. 
