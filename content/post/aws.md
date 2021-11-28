---
title: "Aws"
date: 2021-10-16T12:17:41Z
draft: true
slug: aws

tags:
    - 

categories:
    - 


image: https://lorempixel.com/720/380
thumbnail: https://lorempixel.com/320/160
---

# pemantauan dan analitik aws
Amazon CloudWatch. Ia dapat memantau infrastruktur dan aplikasi yang Anda jalankan di AWS secara real time. Layanan ini bekerja dengan cara melacak dan memantau metrik.
AWS CloudTrail. Ia adalah layanan audit API yang komprehensif. Dengan CloudTrail, Anda dapat melihat riwayat lengkap dari aktivitas pengguna dan panggilan API untuk aplikasi maupun sumber daya Anda.
AWS memiliki penasihat otomatis yang disebut dengan AWS Trusted Advisor. Ia adalah layanan web yang memeriksa lingkungan AWS Anda dan memberikan rekomendasi secara real time sesuai dengan praktik terbaik AWS.

Amazon CloudWatch dapat menyajikan informasi yang hampir real-time tentang bagaimana sistem Anda bekerja, termasuk memberi peringatan ketika terjadi sesuatu. Bahkan, Anda juga dapat melihat metrik tersebut dari waktu ke waktu.
AWS CloudTrail dapat membantu Anda untuk mengetahui dengan tepat tentang: Siapa melakukan apa, kapan, dan dari mana. Tentunya ia akan menjawab semua pertanyaan audit AWS Anda.
Terakhir, AWS Trusted Advisor dapat menampilkan dashboard yang berisi lebih dari 40 masalah umum seputar biaya, kinerja, keamanan, dan ketahanan yang dapat ditindaklanjuti.

# keamanan 
AWS Shield adalah layanan yang dapat melindungi aplikasi Anda dari serangan DDoS. 
AWS Key Management Service (AWS KMS) adalah layanan yang memungkinkan Anda untuk melakukan enkripsi menggunakan cryptographic key (kunci kriptografi). 
AWS Web Application Firewall alias AWS WAF memungkinkan Anda untuk dapat memantau request/permintaan jaringan yang masuk ke aplikasi web.
Amazon Inspector. Ia dapat membantu Anda untuk melengkapi pemahaman kita untuk meningkatkan keamanan dan compliance/kepatuhan aplikasi dengan menjalankan penilaian keamanan secara otomatis terhadap infrastruktur Anda.
GuardDuty. Ia adalah layanan yang menyediakan deteksi ancaman cerdas untuk infrastruktur dan sumber daya AWS Anda.

# concept
 Setiap Availability Zone adalah satu atau beberapa data center terpisah dengan daya, jaringan, dan konektivitasnya sendiri-sendiri.


# penyimpanan / teknologi 
 DocumentDB. Ia adalah layanan yang dapat membantu Anda untuk menangani manajemen konten, katalog, ataupun profil pengguna.
 Amazon Neptune dapat membantu Anda dalam hal tersebut. Ia adalah layanan graph database (database grafik) yang berguna untuk membuat dan menjalankan aplikasi dengan kumpulan data yang sangat terhubung, seperti social networking (jejaring sosial), recommendation engines (mesin pemberi rekomendasi), fraud detection (sistem pendeteksi penipuan), dan knowledge graph (grafik pengetahuan: kumpulan deskripsi yang saling terkait dari entitas).
blockchain? Yup, ia adalah sistem ledger (kumpulan catatan riwayat aktivitas) terdistribusi yang memungkinkan banyak pihak menjalankan transaksi dan berbagi data tanpa otoritas pusat.
Amazon QLDB adalah sistem pencatatan yang immutable di mana entri apa pun tidak akan pernah bisa dihapus dari audit. 
	s3
	S3 Standard hadir dengan daya tahan 11 sembilan. Artinya, objek yang disimpan akan memiliki 99,999999999% probabilitas tetap utuh setelah jangka waktu satu tahun.
	S3 Standard-Infrequent Access (S3 Standard-IA).Kelas penyimpanan jenis ini digunakan untuk data yang jarang diakses tetapi membutuhkan proses cepat saat dibutuhkan. A
	kelas penyimpanan S3 One Zone-IA menyimpan data hanya di satu Availability Zone.Pada kelas penyimpanan S3 Intelligent-Tiering, Amazon S3 memantau pola akses objek. Jika Anda tidak pernah mengakses objek selama 30 hari berturut-turut, Amazon S3 akan memindahkannya secara otomatis ke S3 Standard-IA.
	Opsi kelas penyimpanan ini ideal untuk data audit.
aws thures advisor : enter & bisniess
membuat etimasi biaya : pricing cakulator
pernyataan aws cost exploler : 6 bulan & penyelidikan

penggunaan komputasi yang kosisten : savinng


# biling pricing
membagi sumber daya berdasarkan departemen
perkiraan penggunaan untuk berapa bulan
admin memberikan laporan keamanaaan 
layanan di kelola aws
detail aktivitas  pengguna
penemuan data sensitif dalam skala besar
amazon guarduty
developer ke pengaturan fungsi aws
e2c memiliki akses s3 bucket
instasi group  di labeli Out of services
layanan aws melalui scipt
avaliability zone

# concept
praktik merancang sistem ebaik could
layanan yang menyediakan layanaan terpadu
stategi migrasi could native
aws waf mengelola penggunaan dinamis
maunted dai ec2
e2c dan amazon rds 2 bulan

# teknologi
key value
bjek di akses dan jarang
jarang di akses dan tak masalah menunggu 
s3 membantu pola akses 
pvc perring
teriolasi aws coluld
amazon route 53s
	