**NAMA: NOBEL RAHMAT SANI**
**KELAS: 2A TRPL**
**NIM: 362358302075**

1.  Persiapan Lingkungan
   - Instalasi Laravel:
     ![image](https://github.com/user-attachments/assets/fe685ef9-0aaa-4e81-b779-682046e13a45)

   - Konfigurasi Database:
     ![image](https://github.com/user-attachments/assets/7f5347c1-da09-4660-a3d1-2000d5810f4c)

2. Instalasi dan Konfigurasi Laravel Sanctum
   - Migrasi Database:
     ![image](https://github.com/user-attachments/assets/5aaf5fb7-8738-4834-9191-d9b67166c442)

   - Konfigurasi Sanctum:
     ![image](https://github.com/user-attachments/assets/cae2a7f6-6090-4827-b6d6-58a1e487183e)

   - Konfigurasi User Model:
     ![image](https://github.com/user-attachments/assets/fef83728-18da-4d6f-ac88-a5d9cfd1d528)

3. Autentikasi API
   A. Registrasi Pengguna:
      - Buat controller untuk autentikasi:
        ![image](https://github.com/user-attachments/assets/e6f5772a-5758-4a29-8d23-6854b79256b3)

      - Tambahkan metode registrasi	di `AuthController`:
        ![image](https://github.com/user-attachments/assets/3d547b96-f929-48bb-b13b-4c9a28ab1718)

   B. Login Pengguna:
      - Tambahkan metode login di `AuthController`:
        ![image](https://github.com/user-attachments/assets/cae1f6aa-a04d-427b-b4a6-938963c7e1a6)

4. CRUD Data Siswa
   A. Model	dan	Migration:
      - Buat model dan migration untuk `Siswa`:
        ![image](https://github.com/user-attachments/assets/c116acc3-5f70-4a4d-82c4-2fd31c77bee0)

      - Definisikan	struktur tabel di migration:
        ![image](https://github.com/user-attachments/assets/ce32a58c-f7de-49ad-b1f0-f10f18633dcd)

      - Jalankan migrasi:
        ![image](https://github.com/user-attachments/assets/cad8290c-345e-4510-a6c7-40e893f68f62)

   B. Controller dan Route:
      - Buat controller	untuk `Siswa`:
        ![image](https://github.com/user-attachments/assets/b99c5808-a644-4dd1-ad79-7a2f837656aa)

      - Implementasikan	metode CRUD	di `SiswaController` dengan	error handling:
        ![image](https://github.com/user-attachments/assets/a428ad8b-bc00-45ae-b53e-e792de92965a)
        ![image](https://github.com/user-attachments/assets/ad03850b-55c9-409e-a12d-641697c1ab06)


      - Definisikan	route di `routes/api.php`:
        ![image](https://github.com/user-attachments/assets/6be2bf4c-a20b-40d9-8dcb-95ee01b67510)

5. Pengujian API
   A. Pengujian	dengan Postman:
      - Registrasi:
        ![1](https://github.com/user-attachments/assets/e3514255-ae81-465e-a43c-e3501df8590a)

      - Login:
        ![2](https://github.com/user-attachments/assets/4013e6da-decc-43ef-a9b9-d8fafd4f5ee3)

      - CRUD:
        ![5](https://github.com/user-attachments/assets/873be297-d150-4d20-8627-f6bcf66d0c44)
        ![6](https://github.com/user-attachments/assets/79f0bea8-0173-4dc7-b291-6970ca229649)
        ![8](https://github.com/user-attachments/assets/7d59cfb6-975e-4d40-8603-ed9392fff14b)
        ![7](https://github.com/user-attachments/assets/22a45c78-dbcf-4feb-99dc-b63f3a21a439)

6. Tugas Tambahan
   - Tambahkan validasi:
     ![5](https://github.com/user-attachments/assets/bb2661a3-d045-4493-ae2d-0882d1c59ba6)

   - Respons Error yang Lebih Informatif:
     ![4](https://github.com/user-attachments/assets/ae42f764-1e03-4835-af0e-59e85c648fe1)
