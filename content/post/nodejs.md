---
title: "Nodejs"
date: 2021-10-16T12:21:12Z
draft: true
slug: nodejs

tags:
    - 

categories:
    - 


image: https://lorempixel.com/720/380
thumbnail: https://lorempixel.com/320/160
---

Node.js berhasil menjadi JavaScript Runtime yang dapat mengeksekusi kode JavaScript di luar browser

node js basic

NPM alias Node Package Manager merupakan JavaScript Package Manager bawaan dari Node.js. Melalui NPM ini kita dapat membuat Node.js package (proyek) dan mengelola penggunaan package eksternal yang digunakan. Kita akan membahas NPM lebih detail nanti.

membuat project nodejs

repl 
Node.js memiliki fitur REPL atau Read-Eval-Print Loop. Sesuai namanya, fitur ini berfungsi untuk membaca kode JavaScript, mengevaluasi kode tersebut, kemudian mencetak hasil evaluasinya ke console.

nodejs global object

Node.js, sebenarnya mereka hanya menambahkan beberapa objek saja
Objek tersebut dinamakan dengan ‘true globals’
global : Global namespace. Member apa pun di dalam object ini dapat diakses pada cakupan global.
process : menyediakan interaksi dengan proses Node.js yang berjalan.
console : menyediakan berbagai fungsionalitas STDIO.
setTimeout, clearTimeout, setInterval, clearInterval

pseudo-globals dapat diakses layaknya global objek.
Berikut adalah daftarnya:

module : digunakan untuk sistem modularisasi pada Node.js.
__filename : keyword untuk mendapatkan lokasi berkas JavaScript yang dieksekusi. Keyword ini tidak tersedia pada Node.js REPL.

__dirname : keyword untuk mendapatkan root directory dari berkas JavaScript yang dieksekusi.
require : digunakan untuk mengimpor module JavaScript.


# Belajar Node Js

## Rencana Belajar Node JS

1. Apa Itu Node Js
2. arsitektur Node js
3. instalsai kofigurasi & Menjalankan Node Js
4. node Js Module system
5. NPM
6. Membuat Aplikasi Node Js Sederhana

## 1. Apa Itu Node Js [node Js](http://nodejs.org)

- node js adalah javascript runtime yang di buat javascript engine V8 Google Chorme
- node js adalah sebuah runtim untuk membuat aplikasi ansyncronus
- runtime ? dimana kita dapat menjalankan / mengekskusi code
- fungsi js

  - maniplasi DOM
  - Event listener
  - interaktivitas
  - HTTP requests
  - dll.

- Node js di buat [ryan dahl](https://github.con/ry) pada 2009
- Node Js di luar browser / di dalam OS :

  - akses momori
  - akses file system
  - I/O
  - aktivitas Network
  - dll.

- karakteristik Node Js

  - Ansyincronus & event driven
  - non-blocking
  - single threded buy highy scalable
  - cross platform
  - open source / MIT licence
  - NPM

- [fitur Utama](https://nodejs.og/dist/latest-v14.x/api)

  - file system
  - buffer/ mengelola bin file
  - http & Https / aktivitas Network
  - REPL
  - console
  - Cripto
  - compresi /Zlib

- perbedaan NODE Js VS PHP

  - PHP
    - 1994
    - Zend engine
    - Single thred, ansyincronus
    - Apache / IIS
    - composer
  - Node Js
    - 2009
    - Google V8 Engine
    - Single thred, ansyincronus, non blocing
    - Berjalan di runtime sendiri
    - NPM

- Node js coco untuk :

  - Dynamic singe Page application (SPA)
  - Realtime app (Chat, Multiplayer)
  - API
  - Stremming app
  - microservices
  - commend line tool
  - MERN, MEAN, MEVN

- Pre Requisite

  - javascript dasar
  - ES 6(Modern Js)

- System & Software requiment
  - Windows / Linux / MacOS
  - code editor
  - terminal

## Arsitektur node js

- CaraKerja Node js
  - Single thred, ansyincronus, non blocing

## instalasi dan konfigurasi Node Js [node Js](http://nodejs.org)

- cara cek
  - node -v
  - npm -v

## REPL

- REPL (read-eval-print-loop)
- untuk men debug script
- untuk mengkeksekusi kode lewat command prompt
- menggunakan shortcart "node" pada terminal
- global. tab2x
- .help, .load, .save, .break, .clear, .editor
- vi (nama file), esc ->:wq, cat (.load "nama file")

## menjalankan file node

- terminal
- node 'nama file'
- node . (index)
- imidiate function expresion
- mengakses file bebrbeda di index.html
- menganut sistem module
- export / require

## node js [module system](https://nodejs.og/dist/latest-v14.x/api/modules.html)

- modules? sekumpulan kode yang dapat di gunakan kembali , dengan antarmuka yang terdefinisi
- node modules ? fungsionalitas yang simple atau komplex yang tersimpan di dalam sebuah file javascript, yang dapat di gunakan kembali pada aplikasi node js
- node js modeles
  - core modules (file system)
  - local modules (yang di buat sendiri dengan export / require)
  - third party modules (modul yang di buat orang lain yang dapat di pakai) / NPM
- require mencari modul dg ukuran sbb ;
  - core modules
  - file atau direktori (./ atau ../)
  - folder "node_modules" / NPM modules

## Node js [core modules](https://nodejs.og/dist/latest-v14.x/api/)

- file system : meniliskan ke file sistem / direktori
- read line : membaca apa yang di tuliskan di cmd

# NPM / Thirt parti modules (npmjs.com)

- node package managaer
- menyimpan projeck ooen source
- inisialisasi : npm init
- install package : npm i (nama package)
- uninstall pacjage : npm uninstall (nama package)
- install spesifik versi : npm i (nama package)@versi.x.x

## Menggunakan Package NPM

- validator
- chalk
- nodemon

## 10 membuatcontact app
