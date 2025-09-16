# LAPORAN POST-TEST 2 
# "Sistem Manajemen Rental Sepeda Listrik"

# Lanjutan-Post-Test-1-PBO

### Nama: Moreno Ferdinand Farhantino
### Kelas: C
### Angkatan 2024

# A. SELURUH DOKEMNTASI INPUT CODINGAN JAVA

## Package dan Class:

<img width="422" height="224" alt="image" src="https://github.com/user-attachments/assets/018bfd2a-e9f0-4258-a811-08ca0406de39" />

## Main (MainManga):
<img width="870" height="741" alt="image" src="https://github.com/user-attachments/assets/71c35f52-d50d-41c8-9e33-b47f39900b5b" />
<img width="870" height="337" alt="image" src="https://github.com/user-attachments/assets/77d6b338-9635-4231-b112-78b0a960bfc0" />

## Model (Manga):
<img width="869" height="700" alt="image" src="https://github.com/user-attachments/assets/d61a913c-1985-4464-84b9-cd97249da5db" />
<img width="868" height="157" alt="image" src="https://github.com/user-attachments/assets/e06912c3-0111-4d22-b5f3-4050b86249b9" />

## Service (MangaManager):
<img width="878" height="583" alt="image" src="https://github.com/user-attachments/assets/292b1069-5458-4d1f-b879-d41826baa179" />
<img width="880" height="385" alt="image" src="https://github.com/user-attachments/assets/4ddeafc5-746c-4b73-8a23-dadf946c36a5" />
<img width="878" height="493" alt="image" src="https://github.com/user-attachments/assets/00ecf756-8220-4aed-b207-ad8f8f3530fc" />
<img width="875" height="680" alt="image" src="https://github.com/user-attachments/assets/230c0a0c-0a2d-46a7-beca-bb0bab6820df" />
<img width="973" height="786" alt="image" src="https://github.com/user-attachments/assets/a94fcc5b-de53-4168-b54c-f82e1c86cd80" />

# B. DOKUMENTASI OUTPUT CODINGAN JAVA
<img width="313" height="177" alt="image" src="https://github.com/user-attachments/assets/146ea615-2305-4285-9250-f736ea8f96b5" />

# C. PENJELASAN INPUT
### MainManga
<img width="203" height="46" alt="image" src="https://github.com/user-attachments/assets/188a9e5a-acc0-47bb-ae81-bb04c0295cd7" />

Di dalam Package Main terdapat Class Main yang berperan sebagai titik awal eksekusi program. Kelas ini bertugas menampilkan menu utama kepada pengguna, membaca input yang dimasukkan, kemudian meneruskannya ke bagian service untuk menjalankan berbagai proses seperti menambah, mengubah, menghapus, maupun menampilkan data aset investasi.

### Manga
<img width="170" height="47" alt="image" src="https://github.com/user-attachments/assets/adc932cb-a5a8-49f0-92a3-98d994d80e28" />

Pada Package Model, terdapat Class Manga yang menjadi cetak biru objek manga. Kelas ini menyimpan atribut seperti judul, author, genre, dan tahun_rilis, serta dilengkapi constructor, getter, dan setter untuk inisialisasi, pengambilan, dan pengubahan data secara terstruktur dan terkontrol.

### Service
<img width="231" height="47" alt="image" src="https://github.com/user-attachments/assets/f43d55d8-e278-49ed-a1ad-988ad2cf71d8" />

Pada Package Service terdapat Class MangaManager yang berfungsi sebagai pengelola logika bisnis untuk operasi CRUD. Di dalamnya tersedia berbagai method, seperti input tahun, menambah manga, menampilkan daftar manga, memperbarui data manga, serta menghapus manga yang tersimpan dalam koleksi ArrayList. Kelas ini juga berperan sebagai penghubung antara Main dan Manga, sehingga alur pengolahan data dapat berjalan dengan baik.



### Penerapan Properties
<img width="335" height="90" alt="image" src="https://github.com/user-attachments/assets/c8864987-cdcb-4361-a7aa-5d79c93005b9" />

Pada bagian ini saya menerapkan 3 Properties yaitu: this.judul yang menandakan judul, this.author yang menandakan author, this.genre yang menandakan genre dari manga, dan this.tahunRilis yang menandakan tahun dirilisnya.

OUTPUT PROPERTIES
<img width="280" height="126" alt="image" src="https://github.com/user-attachments/assets/dc7afe69-05e9-4785-96c1-db47057fecfe" />

### Penerapan Constructor
<img width="745" height="138" alt="image" src="https://github.com/user-attachments/assets/6721301e-81e4-44eb-9605-3bcee7d27c57" />

Pada bagian Constructor, Constructor pada class Manga digunakan untuk memberikan nilai awal pada atribut judul, author, genre, dan tahunRilis ketika sebuah objek baru dibentuk. Proses ini berjalan otomatis saat objek sedang dibuat, sehingga setiap objek Manga langsung memiliki data sesuai parameter yang dimasukkan. Dengan demikian, constructor menjamin bahwa setiap manga sudah terdefinisi sejak pertama kali dibuat.

### Penerapan Access Modifier

<img width="288" height="118" alt="image" src="https://github.com/user-attachments/assets/c086f83c-3b65-4e18-a67f-1d0ed93cc95d" />

Pada bagian Access Modifier, digunakan access modifier private pada atribut nama, jenis, dan nilai. Modifier private berarti keempat atribut ini hanya bisa diakses di dalam class Manga saja dan tidak dapat diakses langsung dari luar class. Tujuannya adalah untuk menerapkan prinsip enkapsulasi dalam OOP, yaitu melindungi data agar lebih aman serta memaksa penggunaan getter dan setter atau method lain yang sesuai jika ingin mengakses atau mengubah nilai atribut tersebut.

### Penerapan Fitur Search
<img width="868" height="258" alt="image" src="https://github.com/user-attachments/assets/afcd6689-d2b7-4b02-a5e4-c159f8428df0" />

Fitur search (cari manga) pada kode di atas berfungsi untuk mencari data aset berdasarkan nama. Program meminta pengguna memasukkan kata kunci, lalu membandingkannya dengan setiap nama aset yang ada di dalam daftar menggunakan perulangan for. Apabila ada kecocokan, maka data aset akan ditampilkan beserta pesan "Ditemukan", sedangkan jika tidak ada yang sesuai maka muncul pesan "Manga dengan judul tersebut tidak ditemukan.".

OUTPUT FITUR SEARCH
<img width="302" height="169" alt="image" src="https://github.com/user-attachments/assets/4ff2e57f-7de5-4888-8cf8-792f342fd963" />

# D. HASIL OUTPUT SELURUH PROGRAM
<img width="658" height="764" alt="image" src="https://github.com/user-attachments/assets/64a605bf-2ff2-4849-acdb-822b110d4652" />
<img width="778" height="719" alt="image" src="https://github.com/user-attachments/assets/3f5741dd-61fc-4768-a1a5-1fabd0cd98b5" />
<img width="777" height="348" alt="image" src="https://github.com/user-attachments/assets/8ed071e0-4c86-4a34-b3a5-07e99131c58e" />
