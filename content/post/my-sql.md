---
title: "My sql"
date: 2021-03-01T15:13:46+07:00
draft: false
---

# Pengenalan Database Management System
- DBMS adalah salah satu aplikasi yang di gunakan untuk me menege data
- tanpa DBMS untuk memenege data biasanya kita simpan dalam bentuk file(contoh ms.excel)
- DBMS biasanya berjalan sebagau aplikasi server, dan tinggal membari perintah ke DBMS nya untuk memenege datanya contoh CRUD
- contoh DBMS yang populer MYSQL, Oracle, PostgreSQL, MongoDB, dll


# Pengenalan Reational Database 
- ada banyak sekali jenis DBMS seoerti Reational Database, Document Database, Key-Value Database, dll
- yang paling populer adalah Rational Database
- karena cukup di mengerti dan di pelajari karena terbiasa menyimpan data dalm bentuk tabulas (contoh tabel di ms. excel)
- memiliki perintah standar menggunakan SQL


# cara  kerja Kerja DBMS 
- Database cilent -> DBMS -> Database file
  
# Databasw Cilent
- Database Cilent adalah aplikasi yang di gunakan untuk berkumunikasi dengan DBMS
- DBMS biasanya menyediakan database cilent digunakan untuk berkumunikai dengan DBMS
- atau kita bisa membuat aplikasi untuk berkumunikasi dengan DBMS , contoh aplikasi database cilent


# database file 
- mayoritas DBMS menyimpan datanya di file , walaupun ada yang menyimpan datanya di memori ram
- file database di simpan bukan berupa file seperti ms. excel, tapi jauh lebih komplex
- database file akan dioptimasi oleh DBMS agar daoat mempermudah me menege datanya
- tiap DBMS memiliki cara masing masing mengelola data filenya

# SQL 
- Structured query language
- merupakan bahasa yang digunakan untuk mengirim perintah ke DBMS
- berisi instruksi untuk CRUD mekalui DBMSt
- secara garis besar perintah SQL sama, namun setiap DBMS ada improvment yang membedakan hal hal kecil dalam perintah SQL

# My SQL
- DBMS rasiaonal, opem source, paling populer di dunia saat ini
- tidak hanya opem source tetapi jiga gratis
- th 1995 oleh David axmark dan michael widenius
- sangat populer di kalangan programmer php
- [my SQL](www.mysql.com)

## mysql community & enterprise
- jangan sampai salah download
- mysql enterprise merupakan versi berbayar merupakan improvement dari  mysql community, biasanya menambahkan monitoring dan suport
- mysql community gratis jika terjadi error di selesaikan sendiri , jika ingin monitoring biasanya monitoring sendiri

## mysql vs maria DB 
- 2008 mysql di akui sun microsistem
- 2009 sun diakuisisi oracle
- 2 founder mysql keluar dan membuat dbms yaitu maria DB 
- maria DB merupakam fork dari mysl
- [mariadb](www.mariadb.org)

# mengsintall mysql 
- download langsung dari offical website 
- stack XAMPP

## cek versi mysql 
```cmd 
mysql --version
```

## login mysql 
```cmd 
mysql -uroot -p
```

## menggunakan mysql cilent
- mysql cilent merupakan apk berbasis terminal yang di sediakan mysql untuk berkomunikai dengan mysql server
- karana berbasis terminal cocok untuk prdouction
- tidak oerlu install mydql cilent karena sudah tersedia di dalam mysql ketika kita menginsttallnya

## mysql workbennch
- aplikasi mysql cilent berbasis dekstop
- apk gratis
- [workbench](www.mysql.com/product/workbench)

## Jetbrains DataGrip
- database cilent berbayar
- mendukung banyak DBMS termasuk rasional, noSQL seperti mongoDB, cassandra
- [jerBrains](www.jetbrains.com/datagrip)

# database
- database adalah tempat menyimpan table
- misalkan di database, table adalah filenya dan database adalah foldernya
- biasanya kita akan membuat satu database untuk satu jenis aplikasi walaupun satu aplikasi bisa membutuhkan lebih dari satu database 

## melihat semua database 
```
show databases;
```
## membuat database 
```
create database nama_database
```
## menghapus database 
```
drop database nama_database
```
## memilih database
```
use nama_database
```

# tipe data
- saat kita membuat data di excel, kita bisa mene tukan tipe data yang kita masukkan ke kolom di excel
- di mysql kita juga dapat membuat tipe data pada kolom di dalam table
- ada banyak tipe data di mysql dari yang simple sampai komplex
- biasanya kita membuat tipe data yang sesuai pada kolom

# tipe data number
- secara garis besar tipe data number di mysql ada 2 jenis
- integer atau tipe number bilangan bulat
- floating point atau tioe data number pecahan

## decimal
- tipe data khusus yang bisa ditentukan jumlah presicion(angkanya) dan scalenya(coma)

# tipe data sting
- ini namanya sting atau text
- ada banyak tioe data sting di MySQL

## char atau varchar
- bisa menentukan jumlah panjang maksimal yang di tampung char
- misal CHAR(20) atau VARCHAR(10) artinya jumlah maksimal karakternya 10 karakter
- maksimum ukuran char dan varchar adalah 65535 karakter