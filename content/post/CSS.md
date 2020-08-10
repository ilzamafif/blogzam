---
title: "CSS Dasar"
date: 2020-08-07T08:11:03Z
draft: false
---

#### CSS
pada materi kali ini kita akan bahas CSS mulai dari definisi, cara membuatnya, sejarahnya dan sebagainya.

---

###### apa itu css?
singkatan dari cascading stylesheet di gunakan untuk membarikan warna, ukuran, posisi dsb.
css yaitu mekanisme sederhana yang mengatur gaya / style pada halaman web.
contoh 

css 
* atauran untuk menampilkan tag atau eleman html
* di gunakan untuk memisahkan anatara content dan presentasi style
* 1 cssdapat di gunakan untuk banyak html
* 1 halaman html dapat terlihat berbeda jika menggunakn css yang berbeda

contoh
[zengarden](https://csszengarden.com)

---

##### struktur CSS
```html
slector {poperti: value;}
```
contoh 
```html
h1{ font: sans-serif}
```
juga bisa tuliskan ke bawah 
```html
h1{
  text-align: center;
  color: red;
}
```
selector?
* di gunakan untuk memilih dan memanipulasi elemen html
* elemen bisa berdasarkan tag, id, class bahkan pola 
* semakin kompleks struktur html semakin kompleks juga selector 

jika kita memiliki code seperti ini 
```html 
h1{color: green}
```
bisa di baca
CSS tolong carikan seluruh `h1` lalu ubah seluruh warna menjadi hijau

popeeti & value ?
seluruhnya ada 350+ (lebih), yang kita bahas yang sering di gunakan 
untuk selengkapnya kalian bisa kunjungi website : 
* [mozilla](https://mozilla.org/en-/docs/CSS/reference)
* [css trick](http://css-tricks.com/almanac)

jadi silahkan kunjungi dan peljari

jadi kesimpulannya 1 deklarasi css memiliki selector, poperti, dan value
dan di bungkus kurung kurawal.

--- 

#### penempatan css
ada beberapa cara penempatan css bisa di satu file atau file yang berbeda dengan ekstensi .css (dot css) dan dengan hubungkan file html dan file css

1.embed 
dengantag `<style></style>` di dalam tag head
```html 
<!DOCTYPE html>
<html>
  <head>
    <title>Hello world!</title>
    <style>
    </style>
  </head>
  <body>
    <h1>hello world!</h1>
  </body>
</html>
```
2.inline
dengan menyisipkan popeeti dan value di tag
```html 
    <h1 style="color: blue">hello world!</h1>
```
3.eksternal
dengan cara membuat file css lalu di hubungkan dengan file html

```html 
<!DOCTYPE html>
<html>
  <head>
    <title>Hello world!</title>
    <link rel="stylesheet" href="namafile.css">
  </head>
  <body>
    <h1>hello world!</h1>
  </body>
</html>
```
---