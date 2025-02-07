APLIKASI DETEKSI DIABETES

1.	Siapkan program, pada kali ini saya mengclone atau mengambil program pada github repositori
2.	Masuk kedalam repository project yang akan diambil, lalu bisa mendownload zip atau mengclone dengan perintah cmd
![Deskripsi Gambar](images/gambar_tugas15/Picture1.png)  
3.	Jika mendownload zip maka ekstrak menjadi sebuah folder
![Deskripsi Gambar](images/gambar_tugas15/Picture2.png) 
4.	Masuk kedalam folder lalu klik kanan, dan pilih open in terminal
![Deskripsi Gambar](images/gambar_tugas15/Picture3.png) 
5.	Ketik perintah code . untuk membuka VS Code
![Deskripsi Gambar](images/gambar_tugas15/Picture4.png) 
6.	Masuk kedalam extension dan cari dockerfile 
![Deskripsi Gambar](images/gambar_tugas15/Picture5.png) 
7.	Instal salah satu 
![Deskripsi Gambar](images/gambar_tugas15/Picture6.png) 
8.	Buat file Dockerfile
![Deskripsi Gambar](images/gambar_tugas15/Picture7.png) 
9.	Masukan Code
![Deskripsi Gambar](images/gambar_tugas15/Picture8.png) 
10.	Buat juga file docker-compose.yml, dan masukan Code
![Deskripsi Gambar](images/gambar_tugas15/Picture9.png)
11.	Buka Docker Desktop, jika belum menginstal nya, maka instal pada link ini https://www.docker.com/products/docker-desktop/
![Deskripsi Gambar](images/gambar_tugas15/Picture10.png) 
12.	Ikuti langkang langkah nya dengan login dan wsl update
13.	Buka Docker Desktop 
![Deskripsi Gambar](images/gambar_tugas15/Picture11.png) 
14.	Buka kembali CMD yang sebelumnya telah kita buka untuk mengetik code . 
![Deskripsi Gambar](images/gambar_tugas15/Picture12.png) 
15.	Jalanlan perintah docker-compose build, dan tunggu sampai selesai
![Deskripsi Gambar](images/gambar_tugas15/Picture13.png) 
16.	Jalankan perintah docker-compose up 
![Deskripsi Gambar](images/gambar_tugas15/Picture14.png)
![Deskripsi Gambar](images/gambar_tugas15/Picture15.png)
17.	Buka ip running nya pada web browser, jika tidak bisa maka stop terlebih dahulu dengan menekan CTRL + C
![Deskripsi Gambar](images/gambar_tugas15/Picture16.png) 
18.	Lalu buka app.py dan rubah host nya 
![Deskripsi Gambar](images/gambar_tugas15/Picture17.png) 
19.	Jalankan kembali dengan mengetik docker-compose up 
![Deskripsi Gambar](images/gambar_tugas15/Picture18.png) 
20.	Buka ling 127.0.0.1:5000 
![Deskripsi Gambar](images/gambar_tugas15/Picture19.png) 
21.	Modifikasi, namun sebelumnya ketik docker-compose down 
![Deskripsi Gambar](images/gambar_tugas15/Picture20.png) 
22.	Buka kembali dengan mengetik, docker-compose up 
![Deskripsi Gambar](images/gambar_tugas15/Picture21.png) 
23.	Upload project pada github, buat akun github, lalu buat repository baru 
24.	Jika menggunakan GIT, masuk kedalam folder lalu klik kanan dan pilih git base here
![Deskripsi Gambar](images/gambar_tugas15/Picture22.png) 
25.	Lalu ketik git init 
![Deskripsi Gambar](images/gambar_tugas15/Picture23.png) 
26.	Ketik git branch -M main 
![Deskripsi Gambar](images/gambar_tugas15/Picture24.png) 
27.	 Git add . 
28.	Git commit -m “Comment”
29.	Git remote add origin (link repository github)
30.	Git push -u origin main
 
DEPLOY DENGAN MENGGUNAKAN APLIKASI RAILWAY
1.	Masuk pada link ini https://railway.com/
![Deskripsi Gambar](images/gambar_tugas15/Picture25.png) 
2.	Pilih login dan continue dengan github 
![Deskripsi Gambar](images/gambar_tugas15/Picture26.png) 
3.	Pilih new dan pilih deploy from github repo
![Deskripsi Gambar](images/gambar_tugas15/Picture27.png) 
4.	Configuration dan pilih repo project 
![Deskripsi Gambar](images/gambar_tugas15/Picture28.png) 
5.	Tunggu sampai proses nya selesai 
![Deskripsi Gambar](images/gambar_tugas15/Picture29.png) 
6.	Buka link yang telah dibuat 
![Deskripsi Gambar](images/gambar_tugas15/Picture30.png) 
7.	Aplikasi telah sukses di deploy 
![Deskripsi Gambar](images/gambar_tugas15/Picture31.png)
![Deskripsi Gambar](images/gambar_tugas15/Picture32.png)
 

LINK APLIKASI : https://web-production-9ac9.up.railway.app/

  
