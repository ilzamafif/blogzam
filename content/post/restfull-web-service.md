---
title: "Restfull Web Service"
date: 2021-10-16T12:16:34Z
draft: true
slug: restfull-web-service

tags:
    - 

categories:
    - 


image: https://lorempixel.com/720/380
thumbnail: https://lorempixel.com/320/160
---

REST atau REpresentational State Transfer adalah salah satu gaya arsitektur yang dapat diadaptasi ketika membangun web service.

REST API 
API atau Application Program Interface merupakan antarmuka yang menjadi perantara antara sistem aplikasi yang berbeda. API tak hanya dalam bentuk Web Service, bisa saja berupa SDK (Software Development Kit) ataupun lainnya.

sifat yang menjadi kunci pada REST API

Client-Server : Ini merupakan hal yang paling mendasar dalam membangun REST API. Server harus bisa merespons permintaan yang dilakukan client, baik itu respons berhasil ataupun gagal. Komunikasi client dan server dilakukan melalui protokol HTTP.

Stateless : REST API tidak boleh menyimpan keadaan (state) apa pun terkait client. Seluruh state harus tetap disimpan di client. Artinya, tidak ada session di REST API. Permintaan yang dilakukan client harus mengandung informasi yang jelas. Jangan berharap RESTful API akan menyimpan informasi dari permintaan sebelumnya untuk digunakan di permintaan selanjutnya.

Cacheable : Agar dapat merespons permintaan dengan cepat, sebaiknya REST API menerapkan prinsip cache. Sehingga setiap permintaan tidak melulu mengambil dari database.

Layered : Ketika REST API server memiliki arsitektur yang kompleks, client seharusnya tidak perlu tahu bagaimana server melayaninya.

konsep-konsep penting yang harus diterapkan dalam membangun arsitektur 

ketika membangun REST API kita harus memperhatikan empat poin berikut:

Format request dan response.
JSON merupakan salah satu format standar dalam transaksi data, pastikan setiap respons terdapat properti Content-Type dengan nilai application/json.

HTTP Verbs/Methods.
GET untuk mendapatkan data, POST untuk mengirimkan data baru, PUT untuk memperbarui data yang ada, dan DELETE untuk menghapus data. Verbs tersebutlah yang umum digunakan dalam operasi CRUD.

HTTP Response code.
200 (OK) - Permintaan client berhasil dijalankan oleh server.
201 (Created) - Server berhasil membuat/menambahkan resource yang diminta client.
400 (Bad Request) - Permintaan client gagal dijalankan karena proses validasi input dari client gagal.
401 (Unauthorized) - Permintaan client gagal dijalankan. Biasanya ini disebabkan karena pengguna belum melakukan proses autentikasi.
403 (Forbidden) - Permintaan client gagal dijalankan karena ia tidak memiliki hak akses ke resource yang diminta.
404 (Not Found) - Permintaan client gagal dijalankan karena resource yang diminta tidak ditemukan.
500 (Internal Server Error) -  Permintaan client gagal dijalankan karena server mengalami eror (membangkitkan Exception).

URL Design.
URL, Path, atau Endpoint merupakan salah satu bagian terpenting yang harus diperhatikan ketika membangun REST API. 

aturan umum atau convention agar penggunaan API kita memiliki standar yang diharapkan oleh banyak developer 

Gunakan Kata Benda daripada Kata Kerja pada Endpoint Path
/getArticles => /articles

Gunakan Kata Jamak pada Endpoint untuk Resource Collection 
/articles/:id

Gunakan Endpoint berantai untuk resource yang memiliki hirarki/relasi
GET /articles/:id/comments