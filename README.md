# Simple Blog With Database

Tema: Blog Website

Menggunakan:


1. HTML
2. CSS
3. Javascript
4. Bootstrap
5. NodeJS
6. EJS
7. MongoDB


## Fitur Dari Program:

| Fitur                        | Ket.           |
| ---------------------------- |:--------------:| 
| Create                       | ✔              |
| Update                       | ✔              |
| Delete                       | ✔              |
| System Login & Registrasi    | ❌             |



## Cara Penggunaan Aplikasi (Secara Offline)

  1. Pastikan bahwa anda sudah menginstall MongoDB. Jika belum, silahkan download terlebih dahulu.
  2. Download atau Clone repository ini & install the dependencies
  ```sh
  ~ git clone https://github.com/riskykrnawan/blog-with-database.git
  ~ cd Downloads/<Nama folder yang anda buat>
  ~ npm install
  ```     
  4. Jalankan Server mongoose anda di terminal. caranya: Buka 2 tab baru dan ketikkan `mongod` dan `mongo`. jika MongoDB terinstall dengan benar seharusnya tidak ada masalah.
  5. Jalankan `node app.js`
  6. Pergi ke URL `localhost:3000`


## Note ❗❗❗

#### Dikarenakan ada Update, mungkin program tidak berjalan di versi node yang sebelum (v17.x).

> Jika anda menggunakan NodeJS versi dibawah (v17.x) maka untuk connect ke MongoDB anda perlu mengubah `127.0.0.1` menjadi `localhost`.   
```sh
~ mongoose.connect('mongodb://localhost:27017/postDB', {useNewUrlParser: true})
```

> Jika anda menggunakan NodeJS versi (v17.x) Keatas. maka tidak ada yang perlu diubah, cukup seperti kode berikut:
```sh
~ mongoose.connect('mongodb://127.0.0.1:27017/postDB', {useNewUrlParser: true})
```
