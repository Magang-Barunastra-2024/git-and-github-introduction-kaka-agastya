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
#### setelah instalasi, konfigurasi nama dan email yang terhubung ke akun Github
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
![alt text](<picture/gambar 5.png>) [alt text](README.md)

## Create Repository
#### Repositori adalah tempat penyimpanan proyek Anda di Github.

## Push File from Local to Github
#### Ini adalah proses mentransfer file atau proyek dari komputer lokal ke repositori Github.

## Create New Branch in Github 
#### Branch adalah salinan paralel dari proyek Anda, sebuah tempat untuk mengembangkan fitur baru tanpa mengganggu kode utama.

## Delete Branch in Github
#### Menghapus branch yang sudah tidak digunakan

## Merging Branch in Github
#### Merging adalah proses menggabungkan branch baru ke branch utama (main)

## Other Procedure
