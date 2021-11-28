---
title: "Modularization Nodejs"
date: 2021-10-16T12:19:50Z
draft: true
slug: modularization-nodejs

tags:
    - 

categories:
    - 


image: https://lorempixel.com/720/380
thumbnail: https://lorempixel.com/320/160
---

Modularisasi dalam pemrograman merupakan teknik pemisahan kode menjadi modul-modul yang bersifat independen namun bisa saling digunakan untuk membentuk suatu program yang kompleks

Ada 3 jenis modul pada Node.js, Anda sudah mengetahui dua di antaranya. Berikut rinciannya:

local module : module yang dibuat secara lokal berlokasi pada Node.js project Anda.

core module : module bawaan Node.js berlokasi di folder lib di mana Node.js terpasang pada komputer Anda. Core module dapat digunakan di mana saja.

third party module : module yang dipasang melalui Node Package Manager. Bila third party module dipasang secara lokal, maka modul akan disimpan pada folder node_modules di Node.js project Anda. Bila dipasang secara global, ia akan disimpan pada folder node_modules di lokasi Node.js dipasang