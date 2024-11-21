[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/tbEHDGEc)
# Git and Github Introduction

| Nama  | Division        | Sub-Division  |
| ----- | ---------- | ---------- |
| Kaka Agastya HW   | PGR | WebDev |

## Early Procedure
#### Tahap ini adalah persiapan awal sebelum mulai bekerja dengan Git dan Github.
### 1. Install Git
    https://git-scm.com/downloads
### 2. Membuat akun Github
    https://github.com/join

![alt text](<picture/gambar 1.png>)
### 3. Konfigurasi Git
#### Setelah instalasi, konfigurasi nama dan email yang terhubung ke akun Github
    git config --global user.name "nama anda"
    git config --global user.email "email anda (email@example.com)"

![alt text](<picture/gambar 2.png>)
### 4. Membuat SSH Keys
### a. Buka laman Github -> Settings -> SSH and GPG keys -> New SSH key
![alt text](<picture/gambar 3.png>)
### b. Buat key terlebih dahulu (buka git bash)
### c. Ketik command line berikut
    ssh-keygen -t ed25519 -C "email anda (email@example.com)"
    * klik enter 2 kali *
### d. gunakan perintah cat untuk memunculkan SSH key
    cat ~/.ssh/id_anda.pub

![alt text](<picture/gambar 4.png>)
### e. Copy semua teks dan paste pada bagian key pada setting New SSH key (di github)
![alt text](<picture/gambar 5.png>)
## Create Repository
#### Repositori adalah tempat penyimpanan proyek Anda di Github.

### 1. Buka laman Github
    https://github.com/new
![alt text](<picture/gambar 6.png>)
### 2. Masukkan nama repository sesuai keinginan
### 3. Atur private atau public
### 4. Buka repository yang sudah dibuat
### 5. Hubungkan dengan file lokal

#### a. Manual
##### i. Buat folder dengan nama yang sama dengan di repository
##### ii. Klik kanan dan buka Git bash
##### iii. Masukkan command line berikut

    git init
    git remote add origin "link ssh"
    git branch -M main
    git pull origin "nama branch yang ingin didownload"
![alt text](<picture/gambar 7.png>)
##### b. Git Clone
###### i. Buka Git Bash pada folder parent yang diinginkan dan ketikkan

    git clone "link ssh"

##### ii. Folder akan muncul pada file explorer
##### iii. Buka foldernya
##### iv. klik kanan dan buka Git Bash
##### v. Masukkan command line

    git branch -M main
![alt text](<picture/gambar 8.png>)

## Push File from Local to Github
#### Ini adalah proses mentransfer file atau proyek dari komputer lokal ke repositori Github.
### 1. Buat folder repositori
### 2. Buat file atau folder baru
### 3. Klik kanan, buka Git Bash
### 4. Masukkan command line berikut 

    git add .
    git commit -m "deskripsi"
    git push origin "branch yang ingin diupload"

![alt text](<picture/gambar 9.png>)

## Create New Branch in Github 
#### Branch adalah salinan paralel dari proyek Anda, sebuah tempat untuk mengembangkan fitur baru tanpa mengganggu kode utama.
### 1. Buka folder yang telah terhubung ke Github
### 2. Klik kanan lalu klik Git Bash
### 3. Masukkan command line berikut
    git checkout -b "nama branch yang diinginkan"
### 4. untuk pindah dari branch satu ke branch lain
    git checkout "nama branch"

![alt text](<picture/gambar 10.png>)

## Delete Branch in Github
#### Menghapus branch yang sudah tidak digunakan
### 1. Pindah ke branch lain yang tidak dihapus
    git checkout "nama branch"
### 2. Hapus branch dengan command line berikut
    git branch -d "nama branch"

![alt text](<picture/gambar 11.png>)

## Merging Branch in Github
#### Merging adalah proses menggabungkan branch baru ke branch utama (main)
### 1. pindah ke branch yang ingin menampung hasil merge, gunakan command line
    git checkout "nama branch"
### 2. gabungkan branch dengan command line berikut
    git merge "nama branch"

## Other Procedure
