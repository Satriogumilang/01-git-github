Cara Install Git di Windows
1. Download File Git
2. Install Git
3. Tentukan Lokasi Instalasi Git
4. Pilih Komponen Tambahan
Fungsi komponen ini adalah untuk memperlancar penggunaan Git dan mendukung file dengan kapasitas besar.
5. Tentukan Nama Aplikasi Git
6. Tentukan File Editor
7. Atur Path Environment
 Path Environment berfungsi untuk mengeksekusi perintah perintah pada Git. Pilih Git from the command line and also from 3rd-party software agar saat menjalankan perintah Git dapat dikenali di Command Prompt (CMD) pada Windows.
8. Pilih Aplikasi SSH
9. Pilih Line Ending
 pilih Checkout Windows-style, commit Unix-style line endings. Klik Next untuk melanjutkan instalasi.
10. Pilih Emulator Terminal
 Anda bisa menggunakan Command Prompt atau MinTTY. Karena ingin menggunakan Command Prompt, pilih Use Windows’ default console windows.
11. Tentukan Opsi ekstra
 Terdapat beberapa opsi ekstra yang bisa Anda pilih. Pertama, pilih Enable File System Caching agar Git memiliki fungsi system caching. Kedua, pilih Enable Git Credential Manager agar Git bisa dikombinasikan dengan aplikasi lain seperti Visual Studio, Android Studio, dan GitHub.
12. Mulai Proses Instalasi
13. Cek Versi Git
 untuk cek versi git dan cek apakah Git sudah terinstall di komputer ketik "git --version" pada CMD.

Penggunaan Git dan Github
1. Login Git
Untuk login ke Git, Anda bisa menggunakan akun GitHub, Gitlab, atau Bitbucket. Jika belum memiliki akun dari ketiga platform tersebut, 
2. Anda bisa mendaftarkan diri terlebih dahulu. 
3. Selanjutnya Anda bisa melakukan login awal pada Git  menggunakan Command Prompt  (Windows)
4. masukkan username GitHub Anda menggunakan perintah di bawah ini. Lalu tekan ENTER jika sudah benar.
 {$ git config --global user.name "UsernameAnda"}
5. Kemudian masukkan email yang terdaftar di GitHub Anda menggunakan perintah di bawah  ini. Lalu tekan ENTER jika sudah benar.
 {$ git config --global user.email IsiDenganEmailAnda@gmail.com}
6. Selanjutnya untuk memastikan proses login Anda berhasil, masukkan perintah berikut.
 {$ git config --list}
7. Buat Repository
 Setelah berhasil login ke GitHub, Anda bisa mulai membuat repository klik tombol New pada menu Repositories untuk membuat repository baru. Lalu isi infomasi untuk repository tersebut
8. Buat Folder pada Windows
 Fungsinya adalah untuk menyimpan update file dari repository GitHub yang telah Anda buat.
9. Buka folder tersebut dengan cara klik kanan lalu pilih Git Bash Here. Setelah itu, Command Prompt akan muncul
10. Setelah itu, ubah folder tersebut menjadi repository menggunakan perintah berikut:
 {$ git init}
11. Buat file di folder yang sudah dibuat, Buka GitBash lalu masukkan perintah {$ git add NamaFile.md}
12. Selanjutnya, membuat Commit. Commit berfungsi untuk menambahkan update file serta komentar. Jadi setiap kontributor bisa memberikan konfirmasi update file di proyek yang sedang dikerjakan. {$ git commit -m "first commit"}
13. Remote Repository Github, remote repository berfungsi untuk mengupload file yang telah Anda buat sebelumnya di local disk. {$ git remote add origin git@github.com:UserNameGit/NamaRepository.git}
14. Push ke GitHub. Langkah terakhir adalah push ke GitHub Push ini berfungsi untuk mengupload hasil akhir. {git push -u origin main}
15. Perintah di atas akan menampilkan pop up sign in GitHub. Perlu login untuk melanjutkan proses push ke GitHub. 
 
