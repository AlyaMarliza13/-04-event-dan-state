This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.
# **Laporan Praktikum**

|  | Pemrograman Berbasis Framework 2024 |
|--|--|
| NIM | 2141720004 |
| Nama | Alya Marliza Koesnanto |
| Kelas | TI - 3A |
| | |


* ## **Jawaban Soal/Praktikum 1**
> **Hasil Langkah 1**

![Screenshot](assets-report/01.png)

![Screenshot](assets-report/02.png)

> **Hasil Langkah 2**

![Screenshot](assets-report/03.png)

![Screenshot](assets-report/04.png)

* ## **Jawaban Soal/Praktikum 2**

> **Hasil Praktikum 2**

![Screenshot](assets-report/05.png)

![Screenshot](assets-report/06.png)

> **Penjelasan:**
Terjadi penambahan tombol atau **_button_**. Yang awalnya hanya ada tombol bertuliskan **"Ini Tombol"** lalu ada tombol tambahan bertuliskan **"Pesan"** dengan cara menambahkan satu komponen _function_ tanpa default dengan menggunakan dua parameter sebagai nilai dinamis untuk tombol tersebut dan memanggil komponen tersebut pada bagian **"page.tsx"** dan memodifikasi kode tersebut agar komponen _function_ dapat digunakan/dipanggil.

* ## **Jawaban Soal/Praktikum 3**

> **Hasil Praktikum 3**
* Tampilan dari **Tombol 3**
![Screenshot](assets-report/07.png)

* Tampilan dari **Tombol 3 -  Propagation Tombol -1: Child Element**
![Screenshot](assets-report/08.png)

* Tampilan dari **Tombol 3 -  Propagation Tombol -1: Parent Element**
![Screenshot](assets-report/09.png)

* Tampilan dari **Tombol 3 -  Propagation Tombol -2: Child Element**
![Screenshot](assets-report/10.png)

* Tampilan dari **Tombol 3 -  Propagation Tombol -2: Parent Element**
![Screenshot](assets-report/11.png)

## **Jawaban Soal/Praktikum 4**

> **Hasil Praktikum 4**

![Screenshot](assets-report/12.png)

![GIF](assets-report/01.gif)

## **Jawaban 3 Soal di Praktikum 4**

1. Akan terjadi error, berikut buktinya,

![Screenshot](assets-report/13.png)

![GIF](assets-report/02.gif)

2. Berikut adalah hasil modifikasi dari **gallery.tsx**

![Screenshot](assets-report/14.png)

3. Berikut penambahan tombol **"Artikel Sebelumnya"**

![Screenshot](assets-report/15.png)

![Screenshot](assets-report/16.png)

![GIF](assets-report/03.gif)

## **Jawaban Soal/Praktikum 5**

>**Hasil Langkah 1**

![Screenshot](assets-report/17.png)

![GIF](assets-report/04.gif)

Dari hasil form yang telah dibuat diatas, jika kita memasukkan jawaban yang benar maka akan keluar tulisan **"Yay... Jawaban Benar!"**, namun ketika kita memasukkan jawaban yang salah, dibawah kolom teks jawaban akan keluar peringatan yang bertuliskan **"Tebakan yang bagus tetapi jawaban salah. Silahkan coba lagi!"**.

>**Hasil Langkah 2**

![Screenshot](assets-report/17.png)

![GIF](assets-report/04.gif)

Lalu pada _file_ **Form_2** membuat form yang dimana dapat mengisi nama depan dan belakang lalu menjadi satu yang dimana menjadi nama lengkap dengan 2 jenis _state_ atau kondisi.

* Kondisi _state fullName_ yang **redundan**

![Screenshot](assets-report/18.png)

![GIF](assets-report/05.gif)

* Kondisi _state fullName_ yang **tidak redundan** karena diganti dengan variabel biasa

![Screenshot](assets-report/18.png)

![GIF](assets-report/06.gif)

## **Jawaban 2 Soal di Praktikum 5**

1. Perbedaan pada fungsi pada _file_ **"Form_2"** terletak pada penggunaan _state_ yang dimana pada _state_ awal menggunakan struktur yang kurang baik, lalu pada _state_ kedua sudah menggunakan variabel biasa yang jauh lebih ringkas dan lancar.

2. _state fullName_ sendiri tidak perlu menggunakan struktur yang sama dengan _state firstName_ dan _state lastName_ karena bisa membuat kesalahan _(error)_ atau _bug_. Jadi, _state fullName_ dapat dipanggil dengan variabel biasa agar menghindari _error/bug_ serta meringkas variabel tersebut agar tidak terlihat rumit. 
