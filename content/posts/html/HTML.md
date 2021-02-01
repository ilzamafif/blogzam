---
title: "HTML"
date: 2020-08-07T08:06:04Z
draft: true
categories:
  - "html"
---

### HTML
#### Belajar HTML : Pengenalan HTML Dasar
pada materi kali ini kita akan mebahas HTML mulai dari definisi konsep sejarah samapai kita akan membuat web sederhana menggunakankon HTML

---

##### pengertian HTML 
HTML singkatan dari hypertext markup language, merupakan bahasa standar markup untuk membuat halaman halaman web.elemen HTML berfungsi untuk memberi tahu browser cara menampilkan kontent.
element html yaitu di tentukna oleh tag awal konten dan tag akhir
```html
<tag awal>kontent</tag akhir>
```
---

##### sejarah HTML
html di temukan pada tahun 1980 oleh seorang ahli fisika ,Tim-berners Lee

---

dalam pengembangan website html tidak sendiri html di bantu css dan javascript sebagai teknologi utama.

teknologi utama membuat website

* html di ciptakan untuk membuat halamandan menyajikan konten
* css untuk menghias halaman agar halaman tsb lebik baik lebih bagus
* javascript untuk interaktifitas websete contoh punya animasi slideshow dan sebagainya yang lebih pawerfull.

kalo di ilustrasikan
html seperti orang
css seperti baju
javascript seperti otak karena JavaScript merupakan bahasa pemrograman

perkrmbangan teknologi intrnet lebih lanjut
www.evaluationoftheweb.com

---

##### struktur HTML
```HTML
<!DOCTYPE html>
<html>
  <head>
    <title></title>
  </head>
  <body>
    
  </body>
</html>
```

* `<!DOCTYPE html>` di gunakan untuk mendeklarasikan bahwa dokument merupakaan HTML5
* `<html>` merupakan elemn akar HTML
* `<head>` di gunakan untuk berisi informasi tentang halaman web
* `<body>` sebagai temepat kontent yang akan di tampilkan seperti gamabr dll.
* `<title>` element yang menentukan judul pada halaman web (tersedia di bar atas browser)

--- 
####  peralatan untuk belajar html
untuk membuat website kita juga perlu alat .tools yang di gunakan code editor dan web browser
##### 1.code editor
code editor yaitu jenis program kompirer(sistem oprasi) untuk menulis kode

##### 2.web browser 
web browser sering disebut browser yaitu aplikasi perangkat lunak untuk menampilkan kontent ke browser

--- 
membuat dokument pertama HTML
1.buka code editor
contoh 
[Visual Studio Code](https://code.visualstudio.com),
[subileme text](www.sublimetext.com)
atau yang lainya
2.tulis beberapa HTML atau salin kode berikut
```html 
<!DOCTYPE html>
<html>
  <head>
    <title>Hello world!</title>
  </head>
  <body>
    <h1>hello world!</h1>
  </body>
</html>
```
3.simpan file

4.buka di browser

---
---

#### Tag, Atribut, &  Element
##### Tag
pada kesepatan kali kita akan membahas tag html mulai dari cara menbuat strukturnya dan tag tag apa saja yang terdapat pada html

tag adalah kode dalam html bagaimana kita menuliskan `<nama tag>` tag ada yang berpasangan dan tidak.

biasanya tag berpasangan memiliki tag pembuka dan penutup
```html 
<head></head>
```
yag penutup ada garis miring di depan nama tagnya

tag apa saja yag yang ada di dalam head dan ada tag yang berada di dalam body

kita bahas dulu yang berada di tag head 
* `<title></title>` sebagai judul halaman 
* `<link>` untuk menghubungkan file css
* `<script` untuk menghubungkan file javascript
* `<meta>` untuk mendeskripsikan websete kita 

tag yang ada dilama body
* `<p>` tag paragraf
* `<br>` unuk mengganti baris
* `<hr>` menambah garis horizontal di bawahnya
* `<img>` mengubungkan gambar
* `<a>` menghubungkan link
* `list` membuat list
* `<table>` membuat table
* `<form>` membuat formulir
* `<script>` menghubungkan fule javascript`
* `<div>` 
* `<span>`
* `<strong>` sebai penekanan tebal
* `<em>` sebagai penekanan miring
* `<!-- -->` sebagai komentar


struktur tag
```html
<namatag artibut= "value">
```
contoh : 
```html
<body id"body">
```
sebuah tag boleh memiliki lebih dari satu atribut

##### apa itu atribut?
atribut global
<namatag accsekey="">
<naamtag class="">
<namatag id="">
<namatag dir="">
<namatag lang="">
<namatag style"">
<namatag title="">

cara pembuatan
tag apa saja yang di dalam tag head dan body?

tang berada di head dan penjelasan
tag yang berada di di body dan penjelasan
struktur tag
atribut global


---


##### tag paragraf 
 tag paragraf di tentukan denagan tag `<p>`
```html
<p>ini adalah paragraf</p>
```
##### tag br
tag br di tentukan dengan tag`br`
```html
<p>ini paragraf</p>
<br>
<p>ini juga paragraf</p>
```
##### tag hr
tag br di tentukan dengan tag`hr`
```html
<p>ini paragraf</p>
<hr>
<p>ini juga paragraf</p>
``` 
##### tag b i u
`b` untuk menjadkan teks tebal
`i` untuk menjadikan teks inline
`u` untuk menjadikan teks garis bawah
`strong` sebagai penenkana garis tebal
`em` sebagai penekanan garis miring

##### tag div 
`<div> sebagai pemmbungkus`
##### tag pre 
`<pre>` membuat paragraf dengan format yang todak di tentukan
---


##### heading 
heading yaitu sebuah judul yang biasaya ada pada sebuah halaman
di tentukan dengan tag `h1` sampi `h6`
```html
<h1>ini adalah heading 1</h1>
<h2>ini adalah heading 2</h2>
<h3>ini adalah heading 3</h3>
<h4>ini adalah heading 4</h4>
<h5>ini adalah heading 5</h5>
<h6>ini adalah heading 6</h6>
```

---

##### list 
###### jenis list dan penjelsan 
unorderlist


##### atribut list dan tipe

---


##### link 
link pada html yaitu element yang berfungsi menghubungkan halaman satu ke halaman lainya
link di tentukan denagn tag `<a>`
```html
<a href="https://blogzam.js.org">ini adalah link</a>
```
internal & ekstrenal link
relative link
page anchor
atribut

---



gambar
gamabar di tantukan denagn tag `<img>`
```html
<img src="blogzam.jpg" alt="blogzam">
```
file sumber (src) 
teks alternatif (alt)
internal resource
eksternal resource
atribut
hyperlink + image


---


tabel 
berfungsi
struktur tabel
tabel simpel dan table komplex 
atribut


---


form
apa itu form
struktur

























