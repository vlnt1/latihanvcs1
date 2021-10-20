# latihanvcs1
## CARA MENGGUNAKAN GIT
Cara Menggunakan Git
1. Login Git
Untuk login ke Git, Anda bisa menggunakan akun GitHub, Gitlab, atau Bitbucket. Jika belum memiliki akun dari ketiga platform tersebut, Anda bisa mendaftarkan diri terlebih dahulu. Selanjutnya Anda bisa melakukan login awal pada Git  menggunakan Command Prompt  (Windows) atau Command Line (Linux) . Kemudian masukkan perintah-perintah yang akan kami jelaskan di bawah ini.
Selanjutnya, masukkan username GitHub Anda menggunakan perintah di bawah ini. Lalu tekan ENTER jika sudah benar.
$ git config --global user.name "UsernameAnda"
Kemudian masukkan email yang terdaftar di GitHub Anda menggunakan perintah di bawah  ini. Lalu tekan ENTER jika sudah benar.
$ git config --global user.email IsiDenganEmailAnda@gmail.com
Selanjutnya untuk memastikan proses login Anda berhasil, masukkan perintah berikut.
$ git config --list
[image](https://user-images.githubusercontent.com/92628033/137586118-88396cac-1525-4701-91a8-075077b78caf.png)

2. Login Github
Langkah kedua dalam belajar menggunakan Git adalah Anda harus login ke dalam website GitHub. Github dan Git memiliki hubungan khusus, yaitu Git yang berperan sebagai version control system dan Github menjadi hosting atau sebagai penyimpan kode pemrograman. Setelah Anda login, akan muncul tampilan dashboard dari GitHub seperti  gambar di bawah ini. 
[image](https://user-images.githubusercontent.com/92628033/137586140-612d53f0-5deb-4394-95a9-29b24c4f703b.png) 
3. Buat Repository
Setelah berhasil login ke GitHub, Anda bisa mulai membuat repository. Klik create repository
 [image](https://user-images.githubusercontent.com/92628033/137586144-d254cf17-39da-4352-8d71-d7f121d879ad.png)

Kemudian Anda akan diarahkan pada halaman untuk membuat repository baru seperti gambar di bawah ini.
 [image](https://user-images.githubusercontent.com/92628033/137586150-6479287d-c605-4aa2-9862-15d0ed0af5b3.png)

Anda perlu mengisi detail informasi berikut:
•	Nama Repository : digunakan untuk identitas repository yang dibuat.
•	Deskripsi Repository : berfungsi untuk deskripsi dari repository yang dibuat.
•	Jenis Repository   : jenis repository  dibagi menjadi Public dan Private. Ketika Anda mengatur repository menjadi Public, orang lain dapat melihat repository yang Anda buat. Sebaliknya, jika Anda mengaturnya sebagai Private, repository tersebut hanya bisa diakses oleh Anda.
Setelah mengisi detail informasi di atas, klik Create Repository.



4. Buat Folder pada Windows
Selanjutnya, Anda perlu membuat folder pada local disk komputer Anda. Fungsinya adalah untuk menyimpan update file dari repository GitHub yang telah Anda buat.
 [image](https://user-images.githubusercontent.com/92628033/137586157-3ffd0c29-2494-4c12-9be4-daf6c1c08ebf.png)
5. Buka Folder Menggunakan Git Bash
 [image](https://user-images.githubusercontent.com/92628033/137586163-fc57ef61-6381-46fc-a162-aa3f5fbc389b.png)
Setelah berhasil membuat folder pada local disk komputer Anda,  buka folder tersebut dengan cara klik kanan lalu pilih Git Bash Here. Setelah itu, Command Prompt akan muncul seperti di bawah ini. 
 [image](https://user-images.githubusercontent.com/92628033/137586170-d7591985-558e-445e-a544-21191a8fb081.png)

6. Ubah Folder Menjadi Repository
Setelah itu, ubah folder tersebut menjadi repository menggunakan perintah berikut:
$ git init
[image](https://user-images.githubusercontent.com/92628033/137586174-03173b00-80a7-4ff0-b6de-6ac4212e8b2d.png)

7. Tambahkan File ke Repository
Untuk bisa menambahkan file ke repository GitHub, Anda perlu menerapkan langkah-langkah di bawah ini:
•	Buat file di folder yang sudah dibuat (LatihanVCS). Contohnya, di sini kami membuat file tugaspemograman.docx
•	Buka GitBash lalu masukkan perintah berikut:
$ git add tugaspemograman.docx
Perintah tersebut tidak akan menghasilkan output apa pun.
8. Buat Commit 
Selanjutnya, Anda perlu membuat Commit. Commit berfungsi untuk menambahkan update file serta komentar. Jadi setiap kontributor bisa memberikan konfirmasi update file di proyek yang sedang dikerjakan. Masukkan perintah berikut untuk membuat Commit:
$ git commit -m "latihan"
Pada tutorial ini kami membuat first commit sebagai Commit latihan. Anda bebas membuat membuat nama Commit apa saja.
 [image](https://user-images.githubusercontent.com/92628033/137586191-db8e0ffa-24de-490e-a4b2-bba2921b5d62.png)

9. Remote Repository Github
Remote repository berfungsi untuk mengupload file yang telah Anda buat sebelumnya di local disk. Masukkan perintah berikut ini untuk melakukan remote repository:
$ git remote add origin git@github.com:UserNameGit/NamaRepository.git
Perintah di atas tidak akan menghasilkan output apa pun.
 [image](https://user-images.githubusercontent.com/92628033/137586199-4de8d8b5-bb60-4c47-853c-d6050c3256eb.png)

10. Push ke GitHub 
Langkah terakhir adalah push ke GitHub Push ini berfungsi untuk mengupload hasil akhir dari langkah-langkah di atas. Masukkan perintah berikut untuk melakukan push ke GitHub:
git push -u origin master
Perintah di atas akan menampilkan pop up sign in GitHub. Anda perlu login untuk melanjutkan proses push ke GitHub. 
Jika proses login berhasil, akan muncul tampilan Command Prompt seperti di bawah:
[image](https://user-images.githubusercontent.com/92628033/137586204-ced18dfb-7e0f-4b4f-aad1-c7dd53d7f419.png) 

11. Cek File 
Setelah itu, cek repository yang telah Anda buat. Anda akan mendapati file-file yang telah ditambahkan sebelumnya. Pada tutorial ini kami menambahkan tugaspemograman.docx file
[image](https://user-images.githubusercontent.com/92628033/137586332-a99c4a2d-877e-4ce4-9ade-e41de3790613.png)
