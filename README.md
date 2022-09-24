# Writing and Presentation
## Unix Command Line
### Shell
> Shell adalah processor makro atau penerjemah command language yang menerjemahkan perintah, yang ditulis oleh pengguna di terminal, ke dalam tindakan sistem yang dijalankan, yang juga dapat secara otomatis dijalankan dalam program yang disebut Shell Scripting.
### Filesystem
- Sebuah filesystem mengatur bagaimana data disimpan di dalam sebuah system
- Sistem operasi Windows & Unix-like menyusun file dan direktori menggunakan struktur yang bentuknya mirip tree
### Command Line Interface (CLI)
- Command Line Interface (CLI) adalah antarmuka pengguna berbasis teks ( UI ) yang digunakan untuk menjalankan program, mengelola file komputer, dan berinteraksi dengan komputer.

- Cara mengakses CLI menggunakan terminal di github
<br>1. Download dan install Github Bash.
<br>2. Buat folder di dalam local computer. <br>![membuat folder](https://user-images.githubusercontent.com/100120189/192078815-d7a10b51-12d8-4235-be0e-d3b660e96b7e.png)
<br>3. Klik kanan, kemudian klik GIT Bash Here. <br>![membuka GIT Bash](https://user-images.githubusercontent.com/100120189/192079383-6837f559-4f86-4a68-9f66-002024294a55.png)
<br>4. Terminal siap digunakan. <br>![Siap digunakan](https://user-images.githubusercontent.com/100120189/192079471-33843fc2-9019-4bcf-b6c2-67431c91afaf.png)

- Perintah - Perintah dalam CLI
  - pwd (command untuk melihat current working directory).
    ```
    pwd
    ```
    ![pwd command](https://user-images.githubusercontent.com/100120189/192079566-098e2cac-8b63-4de8-acee-ee6630106025.png)
  - ls (command untuk melihat isi sebuah directory).
    ```
    ls
    ```
    ![ls command](https://user-images.githubusercontent.com/100120189/192079725-f6032170-6b32-40dc-ab3d-637d741b2b98.png)

  - cd (command untuk berpindah directory).
    ```
    cd nama_folder
    ```
    ![cd command](https://user-images.githubusercontent.com/100120189/192079745-85bbe740-0673-45ad-a7bd-dc034246d044.png)
  - cat (command untuk melihat isi files).
    ```
    cat file_yang_ingin_dibuka
    ```
    ![cat command](https://user-images.githubusercontent.com/100120189/192079950-43ab425a-58fa-4420-a849-5898be6ca23e.png)
  - touch (command untuk membuat file).
    ```
    touch file_baru
    ```
    ![touch command](https://user-images.githubusercontent.com/100120189/192080414-e8d0bee3-712f-4683-bcd1-85b371bab2fc.png)
  - mkdir (command untuk membuat direktori).
    ```
    mkdir nama_folder_baru
    ```
    ![mkdir command](https://user-images.githubusercontent.com/100120189/192080468-8a292098-b19b-442b-858f-cbcd6a353200.png)
  - cp (command untuk menyalin file & direktori).
    - Untuk menyalin file.
      ```
      cp file lokasi_dituju
      ```
      ![cp command](https://user-images.githubusercontent.com/100120189/192080658-2542bcad-011f-49d9-9138-2c6ef5f6175b.png)
    - Untuk menyalin direktori dan Isinya
      ```
      cp -R direktori_yang_ingin_dicopy directory_tujuan
      ```
      ![cp -R command](https://user-images.githubusercontent.com/100120189/192080815-60da40c3-a586-4a3e-8f8f-3f6e6207d285.png)
  - mv (command untuk memindahkan atau me-rename file dan direktori).
    - Untuk memindahkan dan merename file.
      ```
      mv nama_file nama_file_baru (rename)
      mv file lokasi (move)
      ```
      Rename :
      <br>![mv command rename](https://user-images.githubusercontent.com/100120189/192080998-3995dff6-003e-4bd0-a141-17b0665d5032.png)
      <br>Move File :
      <br>![mv command move file](https://user-images.githubusercontent.com/100120189/192081142-2b5c7556-9b62-488b-8de3-c8e90b6dfcee.png)

    - Untuk memindahkan direktori dan Isinya
      ```
      mv direktori_yang_ingin_dicopy directory_tujuan
      ```
      ![mv command directory](https://user-images.githubusercontent.com/100120189/192081746-d9177d51-88d7-4dcc-8bcc-3d5cb2e2229f.png)
  - rm (command untuk menghapus file & direktori)
    - Untuk menghapus file
      ```
      rm -R file_yang_ingin_dihapus
      ```
      ![rm -R command](https://user-images.githubusercontent.com/100120189/192082038-d5775acf-b416-4410-b180-ffa6d801bccb.png)

    - Untuk Menghapus Folder
      ```
      rm -d direktori_yang_ingin_dicopy directory_tujuan
      ```
      ![rm -d command](https://user-images.githubusercontent.com/100120189/192082069-80b469a9-dd61-442f-8eb2-34bb2b46df2c.png)




      
    

