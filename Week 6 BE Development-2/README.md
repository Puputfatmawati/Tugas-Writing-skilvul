# Writing Week 6 (BE Development Week 2)

# Backend Development
Secara sederhana, back-end adalah bagian belakang “layar” dari sebuah website atau aplikasi. Secara teknologi, Back-end adalah segala macam teknologi yang ada di sisi server dari sebuah website atau aplikasi. Ada banyak teknologi Back-end yang berhubungan dengan pengembangan aplikasi web. Contoh di slide selanjutnya.
### Bahasa Pemrograman
Back-end developers dapat memilih dari sekian banyak bahasa pemrograman dan framework, tetapi itu semua tergantung pada jenis aplikasi apa yang dibuat.
![bahasa-pemrog](bahasa-pemrog.jpeg)

### Servers: The Machinery
Server adalah sebuah jaringan komputer yang menyediakan jenis layanan tertentu (service) pada komputer lain.Komputer server biasanya didukung dengan prosesor yang bersifat scalable dan RAM yang besar. Server juga dilengkapi dengan sistem operasi khusus, yang disebut sebagai Sistem Operasi Jaringan/Network Operating System. Secara sederhana, server bekerja atas permintaan dari sebuah klien.

### Databases: The Storage
Database dapat didefinisikan sebagai kumpulan data yang disimpan secara sistematis di dalam komputer yang dapat diolah dan dimanipulasi. Lebih singkatnya Database bisa juga disebut sebagai gudang penyimpanan data untuk diolah lebih lanjut.

### APIs: Application Programming Interfaces
API adalah sekumpulan instruksi program dan protokol yang digunakan untuk membangun aplikasi perangkat lunak. REST API bertugas sebagai penghubung/perantara antara Front-End dan Back-end untuk saling bertukar informasi(request dan response).

### MERN Stack
MERN adalah salah satu kombinasi teknologi antara front-end dan back-end untuk membuat aplikasi website. MERN adalah singkatan dari MongoDB, Express, React, dan NodeJS. Teknologi Full-stack yang menggunakan 1 bahasa yaitu Javascript.


# Database
## Database Introducion
Database adalah kumpulan informasi yang disimpan didalam komputer secara sistematik dan saling berelasi. Database merupakan sekumpulan tabel yang berisikan informasi untuk diolah yang kemudian data tersebut bisa digunakan di dalam sebuah sistem.

## Database Management System
DBMS adalah software yang dapat digunakan oleh user untuk berkomunikasi dengan data yang ada dalam media penyimpanan. </br>
![database](database.jpeg)</br>
Tipe utama pada Database management System antara lain, Hierarchical, Network, Relational, Non Relational, and Object Oriented.

## Istilah dalam Database
1. Table </br>
Table adalah kumpulan value yang dibangun oleh baris dan kolom, yang didalamnya berisikan atribut dari sebuah data.
2. Field </br>
Field adalah kolom dari sebuah tabel dimana masing-masing field memiliki tipe data masing-masing.
3. Record </br>
Record merupakan kumpulan nilai yang saling terkait. Record merupakan isi dari sebuah tabel.
4. SQL </br>
SQL atau Structured Query Language merupakan suatu bahasa (Language) yang digunakan untuk mengakses database. SQL adalah Bahasa Query yang digunakan untuk melakukan interaksi di RDMS (Relational Database Management System)

5. DDL (data definittion language) </br>
DDL merupakan kumpulan perintah SQL yang digunakan untuk membuat, mengubah dan menghapus struktur dan definisi metadata dari objek-objek Database.
6. Alter </br>
Alter digunakan untuk mengubah struktur dari tabel yang ada, seperti untuk menambahkan atau menghapus kolom/field.
7. Drop </br>
Alter digunakan untuk mengubah struktur dari tabel yang ada, seperti untuk menambahkan atau menghapus kolom/field.
8. DML (Data Manipulattion Language)
9. Select</br>
Perintah SELECT digunakan untuk menyeleksi data berdasarkan syarat yang diberikan
10. Insert </br>
INSERT	digunakan untuk memasukkan data ke kolom-kolom yang terdapat pada tabel/view.
11. Update </br>
UPDATE digunakan untuk melakukan editing pada isi dari kolom (field) yang dipilih. Hal ini dilakukan untuk memperbaiki data lama / terjadi kesalahan.
12. Delete </br>
DELETE digunakan untuk menghapus data dalam tabel yang menjadi target.
13. DCL (Data Control Language) </br>
14. Grant </br>
GRANT digunakan untuk memberikan hak akses pada user.
15. Revoke </br>
REVOKE digunakan untuk mencabut hak akses yang telah diberikan pada user.
16. Database Relationships </br>
Sederhananya, database relationship adalah relasi atau hubungan antara beberapa tabel dalam bahasa yang kita miliki. Relasi antar tabel dihubungkan oleh Primary key dan foreign key
- Primary key adalah atribut yang tidak hanya mengidentifikasi secara unik suatu kejadian, tapi juga mewakili setiap kejadian suatu entitas.
- Foreign key  adalah atribut yang melengkapi relationship dan menunjukan hubungan antara tabel induk dengan tabel anak

## Beberapa Beberapa tipe database relationships:
1. One To One Relationships
2. One to Many and Many to One Relationships
3. Many to Many Relationships
4. Self Referencing Relationships


## SQL Table Join
Join, adalah penggabungan tabel yang dilakukan melalui kolom/key tertentu yang memiliki nilai terkait untuk mendapatkan satu set data dengan informasi lengkap.</br>
![join](join.jpeg) </br>
- Inner Join menampilkan data hanya yang sesuai di kedua tabel
- Left Join : menampilkan semua data sebelah kiri dari tabel yang di joinkan dan menampilkan data sebelah kanan yang cocok dengan kondisi join. Jika tidak ditemukan kecocokan, maka akan di set NULL secara otomatis
- Right Join : menampilkan semua data sebelah kanan dari tabel yang di joinkan dan menampilkan data sebelah kiri yang cocok dengan kondisi join. Jika tidak ditemukan kecocokan, maka akan di set NULL secara otomatis.


## NoSQL
Database NoSQL adalah database yang tidak memiliki perintah SQL. Konsep penyimpanannya semi struktural atau tidak struktural, dan tidak harus memiliki relasi layaknya tabel-tabel MySQL.
Tujuan dari penggunaan database noSQL adalah untuk model data spesifik dan memiliki skema fleksibel dalam mengembangkan aplikasi modern, contoh: aplikasi yang bersifat real time.

### Kelebihan NoSQL di banding Relasional Database.
- NoSQL bisa menampung data yang terstruktur, semi terstruktur dan tidak terstruktur.
- Menggunakan OOP dalam pengaksesan/manipulasi data.
-NoSQL tidak mengenal schema tabel yang kaku.

## Document Database
Document adalah salah satu dari beberapa model database NoSQL.


# MySQL-Basic
MySQL adalah sistem manajemen basis data relasional open source berbasis SQL. Itu dirancang dan dioptimalkan untuk aplikasi web dan dapat berjalan di platform apa pun. Sebagai persyaratan baru dan berbeda muncul dengan internet, MySQL menjadi platform pilihan untuk pengembang web dan aplikasi berbasis web.
- Portabilitas </br>
MySQL dapat berjalan stabil pada berbagai sistem operasi seperti windows, Linux, MacOs dll.
- Open Source </br>
MySQL didistribusikan sebagai open source sehingga dapat digunakan secara gratis.
- Multi User </br>
MySQL dapat digunakan oleh beberapa pengguna dalam waktu yang bersamaan tanpa mengalami masalah / konflik.

## Data Type SQL
1. Number </br>
Tipe data Number adalah data yang berisi kumpulan karakter angka </br>
![number](number.jpeg)
2. String </br>
Tipe data string adalah tipe data berupa kumpulan karakter termasuk karakter simbol
![string](string.jpeg)
3. boolean </br>
Tipe ini hanya menyimpan 2 tipe data yaitu TRUE dan FALSE, dan dapat di convert menjadi int dengan representasi TRUE = 1, dan FALSE = 0
4. Data Time </br>
Tipe ini merupakan tipe data untuk menyimpan tanggal dan waktu </br>
![time](time.jpeg)
5. other data type </br>
![other](other.jpeg)

## Key
### Primary Key
Secara sederhana, Primary Key disebut juga dengan Kunci Primer. Kunci Primer tersebut dipilih sebagai identifikasi untuk membedakan satu baris dengan baris lainnya dalam suatu tabel. Pada dasarnya, setiap tabel hanya memiliki satu primary key saja.
Bentuk perintah dasar untuk membuat Primary Key dalam SQL adalah :
```sql
Culumn data.type1 PRIMARY KEY
```
### Foreign Key
Foreign Key adalah sebuah atribut atau gabungan atribut yang terdapat dalam suatu tabel yang digunakan untuk menciptakan hubungan (relasi) antara dua tabel. 

### SQL Command
1. Database Command </br>
    ```sql
    SHOW DATABASES; 
    ```
    Command ini digunakan untuk menunjukkan seluruh list database di mysql kita</br>
    ```sql
    CREATE DATABASE bookstore;
    ```
    command ini digunakan untuk membuat database baru </br>
    ```sql
    USE bookstore;
    ```
    Command ini digunakan untuk menggunakan database yang sudah ada </br>
    ```sql
    DROP DATABASE bookstore;
    ```
    Command ini digunakan untuk menghapus / menghilangkan database yang dipilih dari MySQL kita

2. Table Command
    ```sql
    SHOW TABLES;
    ```
    Setelah masuk ke database yang dipilih, kita bisa menggunakan command untuk memodifikasi table di database tersebut, salah satunya adalah SHOW, untuk melihat semua ini table di database

# MySQL Lanjutan
### Tools
- Terminal
- Dbeaver

### Relations Di SQL
1. one to Many
   - Paling sering digunakan
   - satu baris dalam tabel dapat dimiliki beberapa baris di table relasinya</br>
![one](onetoone.jpeg)

2. Many to Many
Digunakan ketika kedua tabel yang berelasi dapat memiliki beberapa baris di tabel relasinya.</br>
![many](manytomany.jpeg)

3. One to one
   - Sangat jarang digunakan
   - Diimplementasikan dengan cara yang sama seperti One to Many tetapi dengan kondisi tambahan (foreign key merupakan primary key)
![one1](oneto1.jpeg)

### Database Normalization
- Pengertian Database Normalization </br>
Merupakan teknik analisis data yang mengorganisasikan atribut-atribut data dengan cara mengelompokkan sehingga terbentuk entitas yang non-redundant, stabil, dan fleksible.

- Tujuan Database Normalization
    1. Menghilangkan redundan data pada database.
    2. Memudahkan juka ada perubahan struktur table database.
    3. Memperkecil pengaruh jika ada perubahan dari struktur table database.

### Efek Jika Tidak Melakukan Database Normalization
- INSERT Anomali : Situasi dimana tidak memungkinkan memasukkan beberapa jenis data secara langsung di database.
- DELETE Anomali : Penghapusan data yang tidak sesuai dengan yang diharapkan, artinya data yang harusnya tidak terhapus mungkin ikut terhapus.
- UPDATE Anomali : Situasi dimana nilai yang diubah menyebabkan inkonsistensi database, dalam artian data yang diubah tidak sesuai dengan yang diperintahkan atau yang diinginkan.

### Bentuk Database Normalization
- First Normal Form (1NF) </br>
    1. Menghilangkan multiple value pada sebuah kolom table database
    2. Sebuah table memenuhi kaidah 1NF jika :
       - Setiap kolom bernilai tunggal (single value)
       - Setiap kolom memiliki nama yang unik
       - Urutan penyimpanan data tidak menjadi masalah
    3. Contoh Bentuk Unormalize (Penulis punya multiple value)</br>
    ![unormal](normali.jpeg)
    4. Contoh Bentuk 1NF
    ![inf](inf.jpeg)

- Second Normal Form (2NF) </br>
    1. Harus sudah dalam bentuk 1NF untuk mendapatkan 2NF
    2. Menghapus beberapa subset data yang ada pada tabel dan menempatkan mereka pada tabel terpisah.
    3. Contoh Bentuk Unormalize (Subset info penerbit pada 1 table</br>
    ![unormalize](unor.jpeg)
    4. Contoh Bentuk 2NF :
    ![2nf](2nf.jpeg)

- Third Normal Form (3NF) </br>
Menghilangkan seluruh atribut atau field yang tidak berhubungan dengan primary key. Dengan demikian tidak ada ketergantungan transitif pada setiap kandidat key.</br>
Masih ada banyak bentuk database normalisasi, diantaranya :
    1. EKNF
    2. BCNF
    3. 4NF
    4. 5NF
    5. DKNF
    6. 6NF

### Key Di SQL
- super key</br>
    1. Kumpulan dari satu atau lebih dari satu key yang dapat digunakan untuk mengidentifikasi record secara unik dalam sebuah tabel.
    2. Super Key adalah superset dari Candidate Key.
    3. Contoh :</br>
    ![superkey](superkey.jpeg)
    Pada table ini yang menjadi super key adalah : 
        - ISBN dan Judul
        - ISBN dan Penulis
        - ISBN dan Penerbit
        - ISBN, Judul, dan Penulis
        - Dan masih banyak kombinasi lainnya.

### Candidate Key
- kumpulan satu atau lebih fields/columns yang dapat mengidentifikasi record secara unik dalam tabel.
- Bisa jadi ada beberapa Candidate Keys di dalam satu tabel
- Setiap Candidate Key bisa digunakan sebagai Primary Key.
- Candidate Key adalah super key yang tidak mempunyai value yang berulang
- Contoh :</br>
 ![candidate](candidate.jpeg)
 Pada table ini yang menjadi candidate key adalah ISBN karena tidak ada value yang berulang.

### Primary Key
- kumpulan satu atau lebih fields/columns dari sebuah tabel yang secara unik mengidentifikasi sebuah record dalam tabel database.
- Valuenya tidak boleh berupa null ataupun duplicate value.
- Hanya boleh salah satu Candidate Key yang bisa menjadi Primary Key.
- Contoh :
![primary](primarykey.jpeg)
Pada table diatas bisa dipilih antara id dan ISBN bisa menjadi primary key

### Alternate Key
- key yang bisa digunakan menjadi primary key.
- Pada dasarnya, Key ini merupakan candidate key yang tidak dijadikan  primary key.
- Contoh : 
![alter](alter.jpeg)
Jika kita sudah menentukan id sebagai primary key, maka ISBN menjadi alternate key

### Unique Key
- Kumpulan dari satu atau lebih fields/columns di sebuah table database yang secara unik mengidentifikasi sebuah record dalam table database tersebut.
- Hampir sama dengan Primary key, namun value dari Unique Key bisa berupa satu buah null value di dalam sebuah table database, dan Unique Key tidak bisa memiliki duplicate values

### Foreign Key
- Field di sebuah table database yang menjadi Primary Key di table database lain.
- Value dari Foreign key bisa menerima multiple null dan duplicate values.

### Join Multiple Tables
Mengambil records dari dua atau lebih table database yang memiliki relationship dan akan di sajikan dalam single result set.

### Inner Join
- Semua baris akan diambil dari kedua table yang akan di JOIN, selama columns cocok dengan kondisi yang sudah di tentukan.
- Memungkinkan baris dari salah satu tabel muncul di hasil jika dan hanya jika kedua tabel memenuhi kondisi yang ditentukan dalam klausa ON.

### Left Join
- Pada JOIN ini, semua records dari table di sisi kiri JOIN statement akan di pilih.
- Jika record yang di pilih dari table kiri tidak memiliki record yang cocok pada table JOIN yang kanan, maka record tersebut masih dipilih, dan kolom pada table yang kanan akan bernilai NULL. 

### Right Join
Pada JOIN ini, semua records dari table di sisi kiri JOIN statement akan di pilih, bahkan jika table di sebelah kiri tidak memiliki record yang cocok.

### Aggregate Functions
Mengambil satu nilai setelah melakukan perhitungan pada sekumpulan nilai
1. Type of Aggregate Functions
    - MAX</br>
    fungsi mengembalikan nilai terbesar dari kolom yang dipilih.
    - MAX</br>
    fungsi mengembalikan nilai terbesar dari kolom yang dipilih.
    - SUM</br>
    fungsi mengembalikan jumlah total kolom numerik.
    - COUNT</br>
    fungsi mengembalikan jumlah baris yang cocok dengan kriteria yang ditentukan
    - AVG</br>
    fungsi mengembalikan nilai rata-rata kolom numerik

### UNION
- Digunakan untuk menggabungkan kumpulan hasil dari dua atau lebih pernyataan SELECT.
- Setiap pernyataan SELECT dalam UNION harus memiliki jumlah kolom yang sama
- Kolom juga harus memiliki tipe data yang serupa
- Kolom dalam setiap pernyataan SELECT juga harus dalam urutan yang sama

### GROUP BY
- Mengelompokkan baris yang memiliki nilai yang sama ke dalam baris ringkasan
- Sering digunakan dengan fungsi agregat untuk mengelompokkan kumpulan hasil dengan satu atau lebih kolom.

### HAVING
HAVING ditambahkan ke SQL karena kata kunci WHERE tidak dapat digunakan dengan aggregate functions.

### LIKE & Wildcards
- Operator LIKE digunakan dalam klausa WHERE untuk mencari pola tertentu dalam kolom.
- Karakter wildcard digunakan untuk menggantikan satu atau lebih karakter dalam sebuah string
- Wildcard Characters di SQL
    - % Mewakili nol atau lebih karakter. </br>
    Contoh : %ja% akan cocok dengan belajar, javascript, & jangan
    - _ Mewakili satu karakter.
    Contoh : m_ster akan cocok dengan master & mister

# Authentication & Authorization in Express
## Authentication
 istilah ini sering ditemukan ketika hendak mencoba login atau masuk pada sebuah sistem atau aplikasi. Autentikasi adalah sebuah metode untuk mengkonfirmasi pengguna pada sebuah sistem.
## Authorization
 Authorization atau otorisasi adalah proses lanjutan setelah proses authentication. Dalam proses authorization, akun kembali diperiksa apakah memiliki izin untuk mengakses resource yang dimaksud. </br>
![author](authorization.jpeg)</br>
gambar di atas merupakan Hubungan antara client, server authentication dan authorization sistem


## Encryption
 Enkripsi adalah proses mengubah data menjadi format yang tidak dapat dibaca kecuali Anda memiliki kunci yang benar untuk mendekripsinya. Enkripsi datang dalam dua jenis utama:
 - Symmetric encryption
 - Asymmetric encryption </br>
 Tanggapan terhadap perintah autentikasi dapat dikategorikan ke dalam:
- Knowledge-Based: “Something You Know”
- Possession-Based: “Something You Have”
- Inherence-Based: “Something You Are”</br>
![encryption](encryption.jpeg)</br>

## Session VS Cookie VS LocalStorage
### Web session
mengacu pada serangkaian interaksi pengguna selama jangka waktu tertentu. Data sesi disimpan di sisi server dan dikaitkan dengan ID sesi.</br>
![web](websession.jpeg)</br>

### Session & Cookie
- Cookie </br>
Cookie adalah potongan kecil data — file teks berukuran maksimal 4kb — browser menyimpan yang secara otomatis dikirim dengan permintaan HTTP ke aplikasi web. Cookie disetel oleh header respons HTTP dalam pasangan nilai kunci:

### Cookie Security
Cookie sering menyimpan informasi sensitif, terutama saat digunakan dalam manajemen sesi. Cookie juga digunakan untuk menyimpan preferensi atau riwayat pribadi pengguna, yang juga harus tetap aman. Langkah pertama untuk mengamankan cookie adalah dengan menambahkan tanggal kedaluwarsa atau durasi sehingga cookie tidak bertahan lebih lama dari yang seharusnya. Kami dapat menentukan informasi itu melalui header Set-Cookie dalam respons HTTP seperti:
```sql
Set-Cookie: Key=Value; expires=Monday, 01-Des-2022 23:59:59 GMT
```
Atribut HttpOnly untuk header Set-Cookie memastikan bahwa data cookie tidak dapat diakses oleh skrip yang menjalankan sisi klien. Ini membantu mencegah serangan Cross-Site Scripting (XSS) yang mencoba mencuri cookie sesi dan mengambil alih sesi korban, yang sangat umum.
```sql
Set-Cookie: Key=Value; expires=Monday, 01-Des-2022 23:59:59 GMT: HTTPOnly
``` 
</br>

![sesi](sesi.jpeg)

### Token Based Authentication using JWT
JWT adalah singkatan dari JSON Web Token yaitu sebuah JSON Object yang digunakan untuk aktifitas transfer informasi antar platform. JSON Web Token dapat berfungsi untuk sistem otentikasi dan juga untuk pertukaran informasi. Token ini terdiri dari header, payload dan signature. Objek JSON harus diapit kurung kurawal dan dapat berisi satu atau lebih pasangan nilai kunci.
contoh:
```js
{
    "nama": "Putri",
    "umur": 21,
    "kota": "Bandung"
}
```

### Component JWT
1. Header </br>
Header biasanya terdiri dari dua bagian: jenis token, yaitu JWT, dan algoritma penandatanganan yang digunakan, seperti HMAC SHA256 atau RSA.
Contoh :
```h
{
  "alg": "HS256",
  "typ": "JWT"
}
```
2. Payload </br>
sebagai infomasi atau data yang ingin kita kirimkan. Dalam penerapannya di otentikasi atau pun otorisasi, biasanya data ini berupa data yang sifatnya unik bagi user, seperti: email, id/uuid, dan juga data yang berkaitan dengan otorisasi seperti role, karena data tersebut akan digunakan sebagai tanda pengenal si pengirim token.
contoh:
```h
{
  "sub": "1234567890",
  "name": "Putri",
  "admin": true
}
```
3. Signature </br>
adalah hasil dari Hash atau gabungan dari isi encode Header dan Payloadnya lalu ditambahkan kode secretnya. Signature ini berguna untuk memverifikasi bahwa header maupun payload yang ada dalam token tidak berubah dari nilai aslinya (karena untuk membuat payload dan header palsu itu cukup mudah).
contoh:
```h
HMACSHA256(
  base64UrlEncode(header) + "." +
  base64UrlEncode(payload),
  secret)
```
Token Based Authentication</br>

![token](token.jpeg )

### Password Authentication (Bcrypt)
Saat mempraktikkan konsep baru, kita mungkin menyimpan kata sandi plaintext di database lokal, tetapi ini sangat tidak aman. kita seharusnya tidak pernah melakukan ini di lingkungan produksi.

### bcrypt is hashing algorithm
![bcrypt](bycript.jpeg)
Hash berfungsi hanya bekerja one-way, yang berarti bahwa setelah nilai di-hash, tidak dapat di-unhash. Ini berarti kita tidak dapat dengan mudah mengambil kata sandi plaintext tanpa mengetahui garam, putaran, dan kunci (kata sandi). berbeda dengan enkripsi, karena, jika kita mengetahui algoritma mana yang digunakan untuk mengenkripsi suatu nilai, kita dapat menggunakan algoritma yang sama untuk mendekripsinya.

### Hash + Salt
- salt </br>
adalah nilai acak yang ditambahkan ke input fungsi hashing untuk membuat setiap hash kata sandi unik bahkan dalam contoh dua pengguna memilih kata sandi yang sama.salt membantu mengurangi serangan tabel hash dengan memaksa penyerang untuk menghitung ulang mereka menggunakan salt untuk setiap pengguna

### bcrypt is hashing algorithm + salt
![bcrypt](salt.jpeg)

## Javascript Authentication and with Passport JS
### Passport JS
Passport JS adalah middleware authentication untuk Node.JS. Passport JS sangat fleksibel dan modular.
Passport juga mendukung otentikasi menggunakan nama pengguna dan kata sandi, Facebook, Twitter dan lainnya.
- Installasi passport
        npm install passport

### Authenticate
Authenticating request di dalam passport dapat dilakukan dengan mudah, hanya dengan menggunakan passport.authenticate(). Secara default, Passport akan mengembalikan respond dengan 401 status, jika authentication gagal.

### Redirect
Redirect biasanya digunakan untuk melanjutkan setelah authentication request.</br>
![redirect](redirect.jpeg)</br>
Pada contoh diatas, secara default, setelah authentication success, user akan dilempar ke halaman homepage. Jika gagal akan dikembalikan ke login page.

### Flash Messages
Redirect biasanya dikombinasikan dengan Flash Messages, untuk menampilkan status informasi kepada User. Secara default, failure flash akan memiliki nilai true, untuk memberi informasi kepada user jika authentication gagal.

### Disable Sessions
Pada server API biasanya membutuhkan kredensial untuk diberikan dengan setiap permintaan. Kita dapat menonaktifkan session pada routes API.

### Strategies
Passport menggunakan “Strategy” untuk mengotentikasi permintaan. “Strategy” dapat memverifikasi nama pengguna dan kata sandi. Otentikasi yang didelegasikan menggunakan OAuth atau otentikasi gabungan.

## Sequelize
Sequelize adalah ORM (Object Relational Mapping) Node JS yang berbasis promise. Sequelize mendukung sebagian besar relational Database seperti MySQL, PostgresQL, MariaDB, SQLite dan Miscrosoft SQL Server.
Dengan fitur fitur di Sequelize, kita bisa mengelola dan mengatur data di database kita dengan cepat, dan efisien.

### ORM
ORM adalah suatu metode/teknik pemrograman yang digunakan untuk mengkonversi data dari lingkungan bahasa pemrograman berorientasi objek (OOP) dengan lingkungan database relational.  
- Installasi Sequelize
    - Install Sequelize-cli</br>
    Kita perlu menginstall sequelize cli agar dapat menjalankan generator menggunakan terminal sehingga lebih mudah.</br>
    
            npm install -g sequelize-cli
    database populer berikut daftar database yang di support serta cara installnya:</br>

            npm install --save pg pg-hstore 
            npm install --save mysql2 
            npm install --save sqlite3 
            npm install --save tedious // MSSQL

### Generate Sequalize
- Sequelize init</br>
Pertama kita perlu melakukan inisialisasi di project kita terlebih dahulu agar dapat melakukan generate code</br>
        npm sequelize-cli init
- setting Database</br>
```js
const { Sequelize } = require('sequelize');

// Option 1: Passing a connection URI
const sequelize = new Sequelize('sqlite::memory:') // Example for sqlite
const sequelize = new Sequelize('postgres://user:pass@example.com:5432/dbname') // Example for postgres

// Option 2: Passing parameters separately (sqlite)
const sequelize = new Sequelize({
  dialect: 'sqlite',
  storage: 'path/to/database.sqlite'
});

// Option 3: Passing parameters separately (other dialects)
const sequelize = new Sequelize('database', 'username', 'password', {
  host: 'localhost',
  dialect: /* one of 'mysql' | 'postgres' | 'sqlite' | 'mariadb' | 'mssql' | 'db2' | 'snowflake' | 'oracle' */
});
```
- Generate Model </br>
![generate](generate.jpeg) </br>
setelah itu Kita bisa melihat datanya menjadi sebuat class (OOP) dan dapat kita gunakan untuk membuat Rest API menggunakan express atau dapat memberikan behaviour di statenya</br>
Akhirnya kita dapat menggunakan generate dan kita bisa mengecek ke database sehingga dapat kita gunakan untuk penimpanan DB

        npx sequelize-cli db:migrate

Jika ada yang salah, kita bisa mengembalikan (undo) menggunakan :

         npx sequelize-cli db:migrate:undo

- Generate Seed </br>
Seed adalah data awal yang bisa kita gunakan untuk mengisi data di database untuk keperluan awal project menggunakan sequelize

        npx sequelize-cli send:generate --name demo-todo

Kita kemudian menjalankan generate seed menggunakan sequelize 

        npx sequelize-cli db:send:all

Jika ada yang salah, kita bisa mengembalikan (undo) menggunakan

        npx sequelize-cli db:send:undo





























