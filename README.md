# Instalasi Laravel dengan Laravel Live Chats

Ini adalah panduan langkah-demi-langkah untuk menginstal proyek Laravel Chatify Live Chats dari GitHub.

## Persyaratan

Pastikan Anda telah memasang perangkat lunak berikut sebelum memulai:

1. [Composer](https://getcomposer.org/download/): Untuk mengelola paket PHP.
2. [XAMPP](https://www.apachefriends.org/index.html) dengan PHP 8: Untuk mengelola database.

Pastikan Composer terpasang dengan menjalankan perintah:

```bash
composer -v
```

## Langkah-langkah Instalasi

1. Clone proyek dari repositori GitHub dengan menjalankan perintah berikut melalui terminal:

```bash
git clone https://github.com/SgtBagus/laravel-chatify-live-chats
```

2. Buka XAMPP dan nyalakan layanan Apache dan MySQL.

3. Buka PHPMyAdmin di browser Anda dan buat database baru dengan nama "laravel-live-chats".

4. Kembali ke terminal dengan direktori folder proyek dan jalankan perintah berikut untuk menjalankan migrasi database:

```bash
php artisan migrate:fresh
```

5. Install dependensi JavaScript dengan npm:

```bash
npm install
```

6. Kompilasi aset JavaScript dengan:

```bash
npm run dev
```

7. Setelah semua langkah di atas berhasil diselesaikan tanpa kesalahan, buka terminal dengan direktori folder proyek dan jalankan server Laravel dengan perintah:

```bash
php artisan serve
```

8. Sekarang, Anda dapat mengakses situs web melalui browser dengan URL [http://127.0.0.1:8000](http://127.0.0.1:8000).

Selamat menggunakan Laravel Chatify Live Chats! Jika Anda mengalami masalah selama instalasi, pastikan untuk memeriksa pesan kesalahan dan dokumentasi resmi Laravel.
```

Pastikan untuk mengganti URL proyek GitHub, nama database, dan URL situs web sesuai dengan proyek dan preferensi Anda.