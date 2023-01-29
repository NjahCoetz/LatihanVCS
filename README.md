
# LatihanVCS
 - cara penggunaan git untuk membuat repository
 - Download **Git** melalui website resminya
 - Jika sudah berhasil terinstall di Windows, untuk mencobanya, silakan buka **CMD** atau **Powershell**, Kemudian ketik perintah >git --version
 - Pada saat pertama kali digunakan perlu dilakukan konfigurasi user.name dan user.email
  ![config user git](https://user-images.githubusercontent.com/123881225/215333491-88ddb993-ecf7-4ebd-8825-6f8a4edf4ae0.PNG)
  
 - buka directory file local misalnya D:\code
 - lalu klik kanan pada file tersebut kemudian pilih menu Git Bash here, sehingga muncul git bash command
 - buat directory praktikum dengan nama LatihanVCS![dirvcs](https://user-images.githubusercontent.com/123881225/215334098-1990c0bf-6f34-4228-a842-60ef5275cd42.PNG)
 - # membuat repository local 
 -  Hal selanjutnya yang harsu dilakukan adalah membuat repository local
 -  untuk membuatnya kita bisa menggunakan cara sebagai berikut 
 -  jalankan perintah **git init** 
 -  Repository baru berhasil di inisialisasi, dengan terbentuknya satu direktori hidden dengan nama .git
 - Pada direktori tersebut, semua perubahan pada working directory akan disimpan.
 - # Menambahkan file baru pada repository
 - kita bisa menambahkan file baru pada repository dengan cara 
 - ketik echo “# Latihan 1” >> README.md
 - ![echo git](https://user-images.githubusercontent.com/123881225/215335817-e855785b-057f-4ef8-9417-4744eb7dff4a.PNG)
 - file read me berhasil dibuat!!
 - Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah **git commit -m “komentar commit”**
