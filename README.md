CARA MEMBUAT REPOSITORY LOCAL DAN REPOSITORY PADA GITHUB SERTA CARA MEMBUAT FILE README.md
Yang kalian butuhkan :
1. Akun GitHub
2. Software atau Program Git

DAFTAR AKUN GitHub

1. Buat akun GitHub dengan cara membuka laman https://github.com
2. Masukan Username, Email dan Password yang akan kalian gunakan pada akun GitHub kalian.
![pic1](https://user-images.githubusercontent.com/56994174/67594724-300c3080-f78f-11e9-8ab0-792e04497d71.png)
3. Lalu buka email yang anda masukan tadi dan lakukan verifikasi.
![pic2](https://user-images.githubusercontent.com/56994174/67594794-55993a00-f78f-11e9-8f6b-bd9f401da879.png)
4. Setelah melakukan verifikasi, kalian akan di alihkan ke laman GitHub untuk selanjutnya membuat Repository baru, lalu masukan nama        Repository kalian dan klik "create repository".
![pic asli dah](https://user-images.githubusercontent.com/56994174/67594900-8f6a4080-f78f-11e9-8c0e-5bfe60c0ce58.png)
5. Seperti inilah tampilan Repository baru.
![pic aslinya](https://user-images.githubusercontent.com/56994174/67595580-34d1e400-f791-11e9-8924-7d1b22934e35.png)

DOWNLOAD SOFTWARE Git

1. Untuk mendownload software Git kita harus masuk ke laman https://git-scm.com
![download git](https://user-images.githubusercontent.com/56971806/67517048-ee668180-f6cb-11e9-8f7e-999a25a197c2.png)
2. Pilih download dan sesuaikan dengan operating system dan spesifikasi laptop atau komputer kalian.
![git download](https://user-images.githubusercontent.com/56971806/67517709-61242c80-f6cd-11e9-8023-c3e408500952.png)
3. Lakukan instalasi Git pada laptop atau komputer kalian.
![install git](https://user-images.githubusercontent.com/56971806/67518320-c593bb80-f6ce-11e9-8bec-2d7f431b16ec.png)
4. Pastikan software atau program Git sudah terinstall 100%.
![git install complete](https://user-images.githubusercontent.com/56971806/67518391-ebb95b80-f6ce-11e9-97ed-37038b021405.png)
5. Pastikan program Git sudah dapat di gunakan di perangkat kalian dengan cara membuka Command Prompt lalu ketik "git
  --version"
   jika sudah muncul berarti Git sudah dapat di gunakan.
![pic5](https://user-images.githubusercontent.com/56994174/67595249-672f1180-f790-11e9-972e-72cc559770d5.png)

MEMBUAT REPOSITORY LOKAL DAN MEMBUAT FILE README.md

  1. Buatlah "folder" baru di directory kalian lalu "klik kanan" pada folder tersebut dan pilih "Git Bash Here"
    ![git bash](https://user-images.githubusercontent.com/56971806/67519128-620a8d80-f6d0-11e9-80e8-53ea3f21054c.png)
  2. Lalu konfigurasi dengan menggunakan perintah "git config --global
    ![abcd](https://user-images.githubusercontent.com/56994174/67595375-b07f6100-f790-11e9-9b74-a1c9dbe14a5c.png)
  3. Buatlah direktori baru dengan menggunakan perintah "mkdir latihan01" dan pindah ke direktori tersebut dengan menggunakan
  perintah "cd tutorialusegit1"
  ![abcde](https://user-images.githubusercontent.com/56986904/67592162-3b5c5d80-f789-11e9-8c50-dc11bfc7615e.png)
  4. Buat file kosong berformat .git dengan cara menjalankan perintah "git init".
  ![abcdef](https://user-images.githubusercontent.com/56986904/67592338-a3ab3f00-f789-11e9-9cb5-2d8dc91fed05.png)
  5. Buat file README.md dengan menggunakan perintah echo "#tutorialusegit1" >> README.md"
  ![abcdefg](https://user-images.githubusercontent.com/56986904/67592509-203e1d80-f78a-11e9-9832-ea30fc5b6acb.png)
  6.Untuk melihat File, gunakan perintah ls -l
  ![abcdefgh](https://user-images.githubusercontent.com/56986904/67592654-7317d500-f78a-11e9-9ea1-991f0acd41bc.png)
  7.Memasukan File README.md ke repository lokal dengan menggunakan perintah "git add README.md"
  ![abcdefghi](https://user-images.githubusercontent.com/56986904/67592778-ca1daa00-f78a-11e9-883e-bd87698db1e9.png)
  8.Simpan perubahan kedalam database repository dengan menggunakan perintah "git commit -m"
  ![abcdefghij](https://user-images.githubusercontent.com/56986904/67592940-2c76aa80-f78b-11e9-8253-0d98e9e4d8e6.png) 
  9.Kirim perubahan local repository ke GitHub dengan menggunakan perintah "git push -u origin master"
  ![finish](https://user-images.githubusercontent.com/56986904/67593709-ff2afc00-f78c-11e9-9e38-b164590ace0b.png)
  10.Cek kembali repository di laman GitHub.
