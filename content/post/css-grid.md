---
title: "Css Grid"
date: 2021-10-17T02:36:17Z
draft: true
slug: css-grid

tags:
    - 

categories:
    - 


image: https://lorempixel.com/720/380
thumbnail: https://lorempixel.com/320/160
---

# CSS GRID
1. apa
	- modul css baru untuk mendefnisikan sstem layout berbentuk grid dalam dua dmensi (baris & column)
2.prasyarat
	- menggnakan dsplay grid

# Terminologi atau istilah
- grid container
- grid item 
- grid line
- grid cell
- grid area 
- grid track
- grid gap

## grid container : 
	- element pembungkus grid
	- di definisikan dengan display grid

## grid item
	- element yang berada (1 level) di dalam grd contianer

## grid line 
- garis horizontal / vertikal yang memisahkan grid menjadi beberapa bagian dan di tandai dengan angka
- lebih dari kolom atau barisnnya

## grid cell
	- perpotongan / pertemuan antara bars dan kolom di dalam grid

## grid area
	- kumpulan lebih dari satu rid cell yang membentuk kotak

## grid track
- ukuran atau jarak antara 2 grid line, bisa horizontal atau vertikal.

## grid gap
	- jarak antara grid track / cell

## browser support 
- valid

# properti css grid
## poperti mengatur column dan baris di dalam container
- grid-template-column (track-size:px, %, fr, line-name:nama)
- grid-template-rows 
- grid-auto-column (mengatur ukuran grid track)
- grid auto-rows
- grid -auto-flow (mengatur penempatan cell)

- grid-template-areas
- grid-template
- grid-column-gap
- grid-row-gap
- grid-gap
- grid

# grid aligment

- justfy-items : mensejajarkan grid item pada horizontal
- algn-items : vertikal
- place-items : keduannya
- justyfy-content :mengatur sluruh grid
- align-content
- place-content

### explicit & impicit grid
 explicit : menentukan dengan jelas column dan baris
 impicit : grid secata otomatis menentukan sisa 

### special kewyords
- reape()
- min-content & max content 
- minmax() : menentukan minimal dan maximal grid track
- auto fill & auto fit : menentukan jumlah item untuk berada pada grid track

# grid area & gap

# grid aligment

# grid item poperti
- grid-column-start
- grid-column-end
- grid-row-start
- grid-row-end

- grid-column
- grid-row 
- grid-area
- jusify-self
- align-self
- place-self 