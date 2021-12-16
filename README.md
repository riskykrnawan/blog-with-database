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



## Cara Penggunaan Aplikasi

  1. Pastikan bahwa anda sudah menginstall MongoDB. Jika belum, silahkan download terlebih dahulu.
  2. Download atau clone repository ini `git clone https://github.com/riskykrnawan/blog-with-database.git`.
  3. Jalankan Terminal.
  4. Jalankan Server mongoose anda. caranya: Buka 2 tab baru dan ketikkan `mongod` dan `mongo`. jika MongoDB terinstall dengan benar Seharusnya tidak ada masalah
  5. Change Directory `cd` ke directory dimana anda meletakkan repository ini. Jika anda menaruh di folder download, cukup ketikkan `cd Downloads` di Terminal
  6. Install npm di Terminal `npm i`
  7. Lalu jalankan `node app.js`

❗❗❗

Jika anda menggunakan NodeJS versi agak lama ( < v17.x ) maka untuk connect ke MongoDB anda perlu mengubah `127.0.0.1` menjadi `localhost`.   
`mongoose.connect('mongodb://localhost:27017/postDB', {useNewUrlParser: true})`

Jika anda menggunakan NodeJS versi Terbaru(v17.x) maka tidak ada yang perlu diubah, cukup seperti kode berikut:
`mongoose.connect('mongodb://127.0.0.1:27017/postDB', {useNewUrlParser: true})`

