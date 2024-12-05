# Lab-6

Tugas Praktikum 8 Mata Kuliah Program Komputer dan Praktek (Lab6)
===========================================================================================================

Program ini dirancang untuk mengelola data mahasiswa dalam bentuk sederhana. Program ini memungkinkan pengguna untuk:

1. Menambahkan data mahasiswa baru: Pengguna dapat memasukkan nama dan nilai mahasiswa baru, yang kemudian akan disimpan dalam sebuah list.


2. Menampilkan semua data mahasiswa: Program akan menampilkan daftar lengkap semua mahasiswa yang telah tersimpan, beserta nama dan nilainya.


3. Menghapus data mahasiswa: Pengguna dapat menghapus data mahasiswa tertentu dengan memasukkan nama mahasiswa yang ingin dihapus.


4. Mengubah nilai mahasiswa: Pengguna dapat mengubah nilai mahasiswa tertentu dengan memasukkan nama mahasiswa dan nilai baru.

**Penjelasan Detail:**

    List mahasiswa: 
    List ini digunakan untuk menyimpan data mahasiswa. Setiap elemen dalam list adalah sebuah dictionary yang berisi dua key: 
    'nama' (untuk menyimpan nama mahasiswa) dan 'nilai' (untuk menyimpan nilai mahasiswa).


    Fungsi tambah(): 
    Fungsi ini menambahkan data mahasiswa baru ke dalam list mahasiswa. Pengguna diminta memasukkan nama dan nilai, 
    kemudian data tersebut disimpan dalam bentuk dictionary dan ditambahkan ke list.


    Fungsi tampilkan(): 
    Fungsi ini mencetak semua data mahasiswa yang tersimpan dalam format yang mudah dibaca. 
    Jika list mahasiswa kosong, maka akan ditampilkan pesan bahwa data masih kosong.

    Fungsi hapus(nama): 
    Fungsi ini mencari mahasiswa dengan nama yang diberikan. Jika ditemukan, data mahasiswa tersebut akan dihapus dari list. 
    Jika tidak ditemukan, akan ditampilkan pesan bahwa data tidak ditemukan.


    Fungsi ubah(nama): 
    Fungsi ini mencari mahasiswa dengan nama yang diberikan. Jika ditemukan, pengguna akan diminta memasukkan nilai baru, dan nilai lama akan diganti dengan nilai baru. 
    Jika tidak ditemukan, akan ditampilkan pesan bahwa data tidak ditemukan.


    Loop Utama: 
    Loop while True menjalankan program secara berulang hingga pengguna memilih untuk keluar. Pada setiap iterasi, 
    program menampilkan menu pilihan dan meminta pengguna untuk memilih tindakan yang ingin dilakukan.


**Flowchart**
![391562349-0926f5a1-2c69-4e22-ab5c-a28f6c0d1a9a](https://github.com/user-attachments/assets/53f364fa-72fc-4d17-ae5c-17f512f16ed3)

**Kode Program**
![Cuplikan layar 2024-12-05 213113](https://github.com/user-attachments/assets/e7ab3c38-5644-4347-8a70-54770deb4039)
![Cuplikan layar 2024-12-05 213133](https://github.com/user-attachments/assets/ca07114f-7dac-4242-9f05-fc914a076ff3)

**Hasil Program**
![Cuplikan layar 2024-12-05 213011](https://github.com/user-attachments/assets/bfd60955-e39f-4e07-9f3c-5ce682e81fa6)
![Cuplikan layar 2024-12-05 213047](https://github.com/user-attachments/assets/a3ba3119-7cd9-4161-8a6d-f60e0cd2e45f)




