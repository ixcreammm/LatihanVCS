## Latihan 1
## TUTORIAL MENGGUNAKAN GIT

<p align="center">
 <img src="https://user-images.githubusercontent.com/92713510/137738729-7baeb34d-e472-4485-8c70-6ee9d4bfa1fd.gif"/>
</p>

# Requirements
- [Git](https://git-scm.com/download)

# Informasi
Pengertian itu Git?
<p>
Git merupakan software berbasis Version Control System (VCS) yang bertugas untuk mencatat perubahan seluruh file atau repository suatu project. Developer software biasa menggunakan Git untuk distributed revision (VCS terdistribusi), hal ini bertujuan untuk menyimpan database tidak hanya ke satu tempat.
</p>

# Tutorial
- Pada saat pertama kali menggunakan Git, perlu dilakukan konfigurasi
Username dan Email.
```bash
> git config --global user.name "username"
> git config --global user.email "email"
```
<img src="https://user-images.githubusercontent.com/92713510/137739987-ed54a98e-e765-43d9-ad1f-e30a017361ae.png">

- Jalankan perintah git init. untuk membuat repository local
```bash
> git init
```
<img src="https://user-images.githubusercontent.com/92713510/137740137-8c9bc7b3-dfa8-491b-9c03-335949d60edc.png">

- Untuk membuat file dapat menggunakan Text Editor, Lalu menyimpan
filenya pada repository. Sebagai contoh disini saya akan membuat file README.md dengan perintah berikut
```bash
> echo "# Latihan2" >> README.md
```
<img src="https://user-images.githubusercontent.com/92713510/137740279-db41107e-1e22-4142-ac4d-f969b924aef5.png">

- Untuk menambahkan file yang sudah kita buat, maka gunakan perintah git add (Nama File) atau bisa menggunakan git add . (Jika file nya ada banyak)
```bash
> git add README.md
> git add .
```
<img src="https://user-images.githubusercontent.com/92713510/137740500-3422f50d-5979-4ef0-a500-8dd6f41d3f10.png">

- Untuk menyimpan perubahan yang ada kedalam database repository
local, maka gunakan perintah git commit -m "nama project"
- Dan yang ada di dalam tanda kutip " " itu nama project kita dan jangan sampai sama setiap kali kita mengupload project
```bash
> git commit -m "First Project"
```
<img src="https://user-images.githubusercontent.com/92713510/137740720-4e78dee4-d78c-4722-a478-21bf3049b248.png">

- Untuk menyimpan setiap perubahan pada repository local, gunakanlah perintah git remote add origin (url)
```bash
> git remote add origin https://github.com/kyuurazz/LatihanVCS.git
```
<img src="https://user-images.githubusercontent.com/92713510/137741175-f34678f0-804e-4b85-b679-c611df65f901.png">

- Untuk mengirim perubahan pada repository local ke server, gunakanlah perintah git push
- Perintah ini akan meminta Username dan Password pada akun github mu
```bash
> git push -u origin master
```
<img src="https://user-images.githubusercontent.com/92713510/137741523-70b69118-f472-45ea-89df-f5509e458fdd.png">

- Selesai

# TERIMAKASIH
