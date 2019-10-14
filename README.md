Langkah pertama Membuat repository baru di GitHub

Dalam menggunakan Version controll, anda akan selalu melakukan Commit pada Git, tempat tersebut dinamakan sebuah repository (a.k.a. “repo”). Dan untuk menyimpan project yang anda buat pada GitHub, anda perlu memiliki GitHub Repository. Berikut ini adalah cara untuk membuat repository pada GitHub.

Pilih New Repository
![gambar 1](https://github.com/arial17/Latihan-VCS/blob/master/Gambar/3.png)

Selanjutnya masukkan informasi tentang anda. jika sudah di isi, selanjutnya click “Create Repository.”

![gambar 2](https://github.com/arial17/Latihan-VCS/blob/master/Gambar/2.png)

Selamat! Sampai pada tahap ini, anda sudah memiliki Repo
Installasi Git pada komputer anda

Sistem operasi Windows
Jika anda pengguna Windows  anda harus mendownload aplikasi  github dari http://windows.github.com/

Membuat file README untuk repo.
File  README bukanlah bagian yang diperlukan dari repo GitHub, tapi kita akan membuat file tersebut untuk uji coba apakah repo dapat digunakan. File README adalah catatan yang bagus untuk menggambarkan proyek Anda atau menambahkan beberapa dokumentasi seperti cara menginstal atau menggunakan proyek Anda. Anda mungkin ingin menyertakan informasi kontak person – jika proyek Anda menjadi orang yang populer akan ingin membantu Anda suatu saat.

sekarang masuklah ke command prompt, lalu buat folder sesuai nama project :

```
mkdir ~/Hello-World  #Membuat direktori "Hello-World"
```

setelah itu, masuk ke folder tersebut:

```
cd ~/Hello-World #Masuk ke folder yang anda buat
```

setelah masuk, ketik perintah tersebut untuk meng initialize folder tersebut:

```
git init    #Sets up the necessary Git files
```

setelah masuk, ketik perintah tersebut untuk meng initialize folder tersebut:

```
touch README# Creates a file called "README" in your Hello-World directory
```

nah sekarang kita coba file README  di folder Hello-World tersebut menggunakan teks editor anda. tambahkan tulisan “Hello World!” di file tersebut, lalu di simpan .
