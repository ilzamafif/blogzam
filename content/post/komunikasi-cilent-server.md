---
title: "Komunikasi Cilent Server"
date: 2021-10-16T12:15:23Z
draft: true
slug: komunikasi-cilent-server

tags:
    - 

categories:
    - 


image: https://lorempixel.com/720/380
thumbnail: https://lorempixel.com/320/160
---

HTTP/HTTPS merupakan salah satu protokol yang dapat digunakan untuk berinteraksi dengan web server. Protokol tersebut terkenal dengan pola request-response, artinya untuk mendapatkan sesuatu (response) kita perlu melakukan permintaan terlebih dahulu (request).

Informasi pada request dapat mengandung

• Request line : berisikan method/verb seperti GET (mengambil data), POST (menambahkan/mengirim data), PUT (memperbaharui data), atau DELETE (menghapus data); path atau alamat yang diminta; dan versi HTTP yang digunakan.
• Header : memuat informasi yang dilampirkan terkait request seperti format dokumen (contoh application/json, text/html, dsb), kunci akses, dsb.
• Body (opsional) : mengandung data yang dibutuhkan oleh server, bisa dalam bentuk teks, JSON, dll. Body tidak wajib dilampirkan bila server tidak membutuhkan data apapun

informasi yang dilampirkan oleh respons
• Status line : berisikan HTTP versi yang digunakan; status code berupa tiga digit angka yang menandakan keberhasilan dari permintaan; reason phrase atau status text yang merupakan pesan berdasarkan status code dalam bentuk teks sehingga lebih mudah dimengerti.
• Header : mengandung informasi yang dilampirkan terkait response seperti format dokumen.
• Body (opsional, namun biasanya selalu dilampirkan) : memuat data yang dikirimkan oleh server. Data dapat berupa HTML, JSON, gambar, dsb