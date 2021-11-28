---
title: "Git Github"
date: 2021-10-17T02:36:35Z
draft: true
slug: git-github

tags:
    - 

categories:
    - 


image: https://lorempixel.com/720/380
thumbnail: https://lorempixel.com/320/160
---

# Git dan Github

## Apa itu Git dan github

- Github
- git ? version control system(VCS) :
- vcs adalah sistem yang mengelola perubahan dari sebuah dokument, program komputer, website dan kumpulan informasi lain
  - mempermudah perubahan versi
  - sebuah sistem yang dpat menyimpan rekaman/snapshot pada source code
  - kolaborasi dengan lebih baik
  - mengetahui siapa dan kapan sebuah perubahan terjadi
  - memmungkinkan kita untuk kembali ke keadaan sebebelum perubahan (checkout)
  - git, svn, mercurial, cvs
- git : vcs yang terdistribusi untuk mengelola perubahan file di dalam folder
  - istilah dalm git
    - repositori : folder seteleah terinisialisai git
    - commit : riwayat rekaman / snapshot perbahan file ari repo
    - init : untuk menginisialisasi
    - hash : penanda unik untuk setiap commit
    - checkout : berpindah ke subuah commit
    - branch : cabang beebas dari sebuah commit
    - marge : menggabungkan cabang . branch
    - push : mengirim commit ke repo
    - pull : mengambil commit dari repo
    - remote : sumber yang mempiliki repo
    - clone : mengambil repo dari remote
- github : website ? layanan could untuk menyimpan & mengelola project / repositori git
  - instagramnya programmer
  - sama seperti git tetapi online
  - website yang di dlamnnya menggunakan git
- layanan selain github : bitbucket dan gitlab

## bekerja dengan Github

- github.com
- membuat akun
- membuat repo
- commit
- hash

## branch

- berjalan dengan commitnya sendiri (independent)
- membuat fitur baru
- teknik branch / branching
  - membuat git branch
  - membuat snapshot tanpa mengganggu jalur utama (master branch)
  - fitur experimental
  - 2 orang mengerjakan repo yang sama
- membuat branch
  - commit
  - marge (compire & pull request)
  - marge conflict : baris yang sama di ubah2 branch 2 berbeda

## fork

- fork/forking : membuat copy atau duplicate dari repo orang lain (beserta historynnya)
- jembatan antara repo original dengan duplikatnya
- memungkinakan modifikasi terhadap repo original
- kontribusi pada repo orang lain
- fork != clone
- cara :
  - fork
  - ubah & commit
  - new pull req

## bekerja dengan [git](git-scm.com)

- install
- perintah git
  - git init
  - git add (file/s)
  - git status
  - git commmit
  - git config
  - branch
  - git help
  - ...
  - git log -- (nama commit)
  - git checkout (5 digit hash commit)
- tiga area pada GIT
  - working tree
  - staging area
  - history

## branch & marge

- membuat branch : git branch <nama branch>
- graph : git log --all --decorate --oneline --graph
- alias / nama lain : alias graph="git log --all --decorate --oneline --graph"
- pindah branch : git checkout (nama branch)

### merge

- fast forward : branch brada pada jalus langsung / direct path
- three-way marge / merge commit : dan membuat commit baru
- merge : git marge (nama branch)
- menghapus branch : git branch -d (nama branch)
- mengetahuai branch yang di merged : git branch --merged
- menghapus branch paksa : git branch -D (nama branch)
- merge commit : git merge (nama branch)

## merge conflict

## git remote

- git clone https://github.com/repo
- git config --list
- remote : git remote
- cek remote : git remote -v
- membuat remote : git add remote (nama remote) https://github.com/repo.git
- push dengan remote : git push -u (nama remote)(branch)
- git pull
- mengecek commit di remote : git fecth

## github [pages](pages.github.com)

## multiple remotes

- mengambil commit : git fecth nama remote

## branch remote

- berkontribusi di repo orang lain dan melakukan pull requset

## .gitignore

- sebuah file yang tidak ikut terbawa
- kumpulan gitignore : (github.com/github/gitignore)
- kumpulan (gitignore.io)

## rebase

- cara lain tidak menggunakan merge
