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
 
## Git dan GitHub

### Git dan Github tools yang wajib digunakan
    > Git dan GitHub adalah salah satu tool yang sering digunakan dalam proyek pengembangan software. Git dan juga GitHub adalah Pengontrol versi bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri. Git dan GitHub juga git digunakan untuk kolaborasi. Oleh karena itu Git dan Github sangat penting untuk Programmer.
    
### Perbedaan antara Git dan Github
- Git
  > Git merupakan software berbasis Version Control System (VCS) yang bertugas untuk mencatat perubahan seluruh file atau repository suatu project.
- GitHub
  > GitHub merupakan layanan cloud yang berguna untuk menyimpan dan mengelola sebuah project yang dinamakan repository (repo git). Cara kerja pada GitHub harus terkoneksi pada internet sehingga tidak perlu meng-install sebuah software ke dalam perangkat keras.
<br>Berikut Perbedaan Git dan GitHub
- Git :
<br>1. Meng-install software di penyimpanan lokal
<br>2. Dikelola oleh The Linux Foundation
<br>3. Berfokus pada version control dan code sharing
<br>4. Akses secara offline
<br>5. Tidak menggunakan fitur user management
<br>6. Menyediakan desktop interface bernama “Git GUI”
<br>7. Open sourced licensed
- GitHub :
<br>1. Host melalui layanan cloud
<br>2. Diakuisisi oleh Microsoft pada 2018
<br>3. Berfokus pada source code hosting terpusat
<br>4. Akses secara online
<br>5. Menggunakan user management
<br>6. Menggunakan nama desktop interface “GitHub Desktop”
<br>7. Pilihan bagi pengguna gratis dan pengguna berbayar

### Membuat Repository Git
1. Buat folder di laptop/komputer
<br>![buat folder](https://user-images.githubusercontent.com/100120189/192084875-5267d4a7-fc2b-4b17-92e0-54d5e06489c4.png)
2. masuk ke folder tersebut, kemudian klik kanan pilih "Git Bash Here"
<br>![membuka git bash](https://user-images.githubusercontent.com/100120189/192084918-d1540374-b086-4236-8467-d248cc6a0ee2.png)
3. ketikan git init. Sekarang folder yang dibuat tadi sudahh menjadi repository
<br>![git init](https://user-images.githubusercontent.com/100120189/192085032-3023b79a-d206-4800-9695-90c4c8a66f6d.png)

### Melakukan commit pada Git
1. Buat satu atau dua file
<br>![membuat file](https://user-images.githubusercontent.com/100120189/192085394-c691958c-aa18-4b08-9861-712cc4082247.png)
2. Ketikkan "git add ." untuk melacak perubahan
<br>![git add .](https://user-images.githubusercontent.com/100120189/192085341-a09f7304-74bc-4a38-bc2f-77f46191ea5f.png)
3. Kemudian baru ketikkan "git commit -m "(pesan perubahan)" untuk melakukan commit
<br>![melakukan commit](https://user-images.githubusercontent.com/100120189/192085457-0023f22a-85f2-4f71-93b5-2163fb484d81.png)

### Mempublish aplikasi ke Github
1. Membuat repository di github
<br>![membuat repository](https://user-images.githubusercontent.com/100120189/192085907-f5c21a69-fdc9-4a51-a6ef-721a59416370.png)
2. Ketikkan "git remote add origin https://github.com/(username)/(repository yang dibuat).git" Untuk me-remote ke github
<br>![git remote add command](https://user-images.githubusercontent.com/100120189/192086110-fbcea64f-b151-49ca-b35f-3231485e802b.png)
3. Ketikkan "git push -u origin (branch yang dipakai)"
<br>![git push command](https://user-images.githubusercontent.com/100120189/192086193-9d2c28d5-c54c-4866-af6b-e48d3876e2e6.png)
4. Seleseai. File sudah ada di Github
<br>![mengecek file](https://user-images.githubusercontent.com/100120189/192086262-f192b2f9-b6bc-4159-a3be-e9e97108b79d.png) 

### Melakukan cloning Github ke local
1. buka repository yang ikin di cloning, kemudian klik code dan salin kode tersebut
<br>![image](https://user-images.githubusercontent.com/100120189/192086298-04dfd51e-67d1-443f-b773-1b381f00a095.png)
2. Tentukan penyimpanan lokal, kemudian klik kanan dan pilih "Git Bash Here"
<br>![menentukan penyimpanan lokal](https://user-images.githubusercontent.com/100120189/192086520-89471820-f852-4a42-a5e2-1a019a4b807c.png)
3. Ketikkan "git clone (link yang tadi dicopy)"
<br>![git clone command](https://user-images.githubusercontent.com/100120189/192086665-a0e07fd9-9101-4a13-9f2c-f9d6322fa504.png)
4. File yang ada di GitHub sudah selasai di cloning ke local
<br>![cek file](https://user-images.githubusercontent.com/100120189/192086750-587dcadb-f217-44c6-8e50-3d69a939c724.png)

## HTML

### Peran HTML
- HTML adalah singkatan dari Hypertext Markup Language.
- HTML digunakan untuk menampilkan konten pada browser.
- HTML bersifat statis. HTML hanya bertugas menampilkan konten yang diminta oleh developer.
- HTML bukanlah sebuah bahasa pemrograman, artinya HTML tidak bisa dinamis mengolah data.

### Tools pendukung dalam menggunakan HTML
    <br>Ada 2 tools pendukung dalam mengguna HTML, yaitu
    <br>1. Browser, contohnya Chrome, Microsoft Edge, Firefox, dan lain sebagainya.
    <br>2. Code Editor, contohnya Visual Studio Code(VSC).
    
### Membuat HTML sederhana 
- Kita bisa menuliskan HTML tanpa structure dan kita bisa tetap menjalankan nya tetapi untuk menjalankannya dengan baik kita perlu HTML Structure.
- HTML struktur :
  - Saat sebuah element berada di dalam element lain, maka disebut child element.
  - Element yang berada diatas element lain disebut parent element.
- HTML Anatomy
  ```
  <p>ini adalah paragraf</p>
  ```
    - code di atas merypakan sebuah elent
    - p adalah opening tag.
    - "ini adalah paragraf merupakan" content.
    - /p adalah closing tag.
- HTML Element
  > HTML element didefinisikan dengan opening tag, content, dan closing tag. Contohnya :
    ```
    <h1>Ini adalah Heading</h1> <!-- Elemen Heading -->
    <p>Ini adalah paragraf pertama</p> <!-- Elemen paragraph -->
    <a href="https://google.com">Google</a> <!-- Element Link -->
    ```
- HTML Attributes
  - Attribute adalah properties dari sebuah HTML Element.
  - Semua HTML Element memiliki attribute.
  - Contohnya :
    ```
    <h1 id="satu">Ini adalah Heading</h1> <!-- Elemen heading dengan attribute id -->
    <img src="kopi.jpg">Ini adalah paragraf pertama</p> <!-- Elemen image dengan attribute src -->
    <a href="https://google.com">Google</a> <!-- Element link dengan attribute href-->
    ```
- HTML Comment
  - Dengan menggunakan HTML Comment, kita dapat memberikan penjelasan maksud dari line code yang kita kerjakan.
  - Comment ini pasti selalu ada dalam bahasa pemrograman apapun.
  - Comment tidak akan dieksekusi oleh sistem.
  - Comment hanya untuk dibaca oleh sesama programmer.
  - Contohnya :
    ```
    <!--   Ini adalah comment   -->
    ```
- Berikut adalah contoh web sederhana :
  ```
  <!DOCTYPE html>
  <html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML</title>
  </head>
  <body>
    <!-- Elemen Heading dengan attribute id -->
    <h1 id="satu">Ini adalah Heading</h1>
    <!-- Elemen Image dengan attribute src dan style -->
    <img src="https://upload.wikimedia.org/wikipedia/id/thumb/7/7a/Manchester_United_FC_crest.svg/1200px-Manchester_United_FC_crest.svg.png" style="height: 40px;width        : 40px">
    <!-- Element Link dengan attribute href -->
    <br><a href="https://google.com">Google</a>
    <!-- Elemen Paragraf -->
    <p>Ini adalah paragraf pertama</p>
  </body>
  </html>
  ```
### Menjalankan HTML secara manual dan menggunakan live server dari VS Code
- Menjalankan HTML secara manual
  <br>1. Buka visual studio code.
  <br>2. Buat code HTML, kemudian disimpan.
  <br>3. klik kanan pada code editornya, kemudian pilih "Open in Default Browser"
      <br> ![image](https://user-images.githubusercontent.com/100120189/192125930-88b38bb8-8a7f-4063-86cc-5d4d3396f476.png)
  > Kita bisa juga menjalankan html secara manual dengan cara membuka file html yang sudah di buat dengan mencari lokasi file HTML
- Menjalankan HTML menggunakan live server
  <br>1. Klik extension di VSC, cari live server, kemudian install.
     <br>![install live server](https://user-images.githubusercontent.com/100120189/192126189-c97dca32-c8d6-4742-84bd-7fc9260cf042.png)
  <br>2. jika sudah berhasil, buka file htmlnya, kemudian klik kanan, dan pilih "Open with Live Server".
     <br>![membuka html menggunakan live srver](https://user-images.githubusercontent.com/100120189/192126211-884cbc92-9086-4832-a552-588e9d8c5c9c.png)
  <br>3. HTML otomatis akan terbuka di default browser dengan HTML akan auto reload. 

### Tag HTML yang populer
- IMG
  - Tag img digunakan untuk menampilkan gambar.
  - Tag img bisa menampilkan gambar melalui file lokal komputer kita atau menggunakan link dari internet dengan attribute src.
  - Bisa menambahkan attribute alt jika gambar tidak berhasil dimunculkan, agar user tahu keterangan gambar itu.
  - Contoh code img :
    ```
    <img src="https://google.com/kopi.png" alt="kopi"> //menggunakan link
    <img src="picture/kopi.jpg" alt="kopi"> //menggunakan> file lokal
    ```
- Video
  - Tag video digunakan untuk menampilkan video.
  - Video merupakan double closing tag sehingga kita menaruh konten di antara opening dan closing
  - Dalam tag video kita bisa menambahkan attribute controls yang berguna untuk kita bisa mengatur videonya di play / pause dan indikator menit.
  - Contoh code video :
    ```
    <video controls>
      <source src="janji-kamu.mp4" type="video/mp4">
    </video>
- Table
  - Tag table digunakan untuk menampilkan tabel.
  - Table pada html defaultnya tidak memiliki garis, jika ingin ada garisnya maka perlu attribute border dengan nilainya. 
  - Berikut contoh code table sederhana :
    ```
    <table border="1">
        <tr>
            <th>NAMA</th>
            <th>ASAL</th>
        </tr>
        <tr>
            <td>Budi Sudarsono</td>
            <td>Pemalang</td>
        </tr>
    </table>
    ```
 - HTML Form
   - Digunakan untuk membuat form registrasi atau login.
   - Berikut contoh code form sederhana :
     ```
     <form>
        <div>
            <label for="username"></label><br>
            <input type="text" placeholder="masukkan username" name="username" id="username">
        </div>
        <div>
            <label for="Email"></label><br>
            <input type="email" placeholder="email" name="email" id="email">
        </div>
        <div>
            <label for="password"></label><br>
            <input type="password" placeholder="masukkan password" name="password" id="password">
        </div>
        <div>
            <input type="submit" value="daftar">
        </div>
     </form>
     ```
     
### Semantic HTML
- Semantic artinya kita menggunakan element html yang sesuai dengan kebutuhan konten.
- Semantic HTML sangat membantu untuk developer supaya lebih “Easy to read and understand”
- Kegunaan semantic HTML
  - Meningkatkan Accessibility
  - Meningkatkan SEO
  - Lebih mudah di maintain
- Contoh penggunaan semantic HTML
  ```
  <section>
    <h1>WWF</h1>
      <p>The World Wide Fund for Nature (WWF) is an international organization working on issues regarding the conservation, research and restoration of the
          environment, formerly named the World Wildlife Fund. WWF was founded in 1961.</p>
  </section>
  ```
### Deploy HTML menggunakan Netlify
1. Daftar Netlify dengan menggunakan akun GitHub
2. Buat repository GitHub yang dalamnya berisi file HTML yang sudah dibuat tadi
3. 
