# Aplikasi Blog

<p align="center">
  <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
</p>

<p align="center">
  <a href="https://filamentphp.com">
    <img src="https://backend.global-inovasi.com/storage/tb_news/01J4TYXBRT9FYKKKPTXFVSQE3T.png" width="400" alt="Filament Logo">
  </a>
</p>

<p align="center">
  <a href="https://spatie.be">
    <img src="https://candokendo.wordpress.com/wp-content/uploads/2020/09/laravel-spatie.png" width="400" alt="Spatie Logo">
  </a>
</p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Tentang Aplikasi Blog

Ini adalah aplikasi blog modern yang dibangun dengan framework Laravel, dengan fitur:

- Autentikasi dan otorisasi pengguna
- Operasi CRUD untuk artikel blog
- Editor teks kaya untuk artikel
- Sistem komentar
- Penandaan dan kategorisasi
- Desain responsif

## Fitur

- [Autentikasi Pengguna](https://laravel.com/docs/authentication)
- [Eloquent ORM](https://laravel.com/docs/eloquent) untuk manajemen database
- [Template Blade](https://laravel.com/docs/blade) untuk tampilan
- [Paginasi](https://laravel.com/docs/pagination) untuk artikel
- [Penyimpanan File](https://laravel.com/docs/filesystem) untuk gambar artikel
- [Sistem Antrian](https://laravel.com/docs/queues) untuk tugas latar belakang
- [Filament Admin Panel](https://filamentphp.com) untuk manajemen konten
- [Spatie Permission](https://spatie.be/docs/laravel-permission) untuk manajemen hak akses

Laravel adalah framework aplikasi web dengan sintaks yang ekspresif dan elegan. Kami percaya bahwa pengembangan harus menjadi pengalaman yang menyenangkan dan kreatif agar benar-benar memuaskan. Laravel menghilangkan kerumitan pengembangan dengan memudahkan tugas-tugas umum yang digunakan dalam banyak proyek web, seperti:

- [Mesin routing yang sederhana dan cepat](https://laravel.com/docs/routing).
- [Container dependency injection yang kuat](https://laravel.com/docs/container).
- Beberapa backend untuk penyimpanan [sesi](https://laravel.com/docs/session) dan [cache](https://laravel.com/docs/cache).
- [Database ORM](https://laravel.com/docs/eloquent) yang ekspresif dan intuitif.
- [Migrasi skema](https://laravel.com/docs/migrations) database yang agnostik.
- [Pemrosesan job latar belakang](https://laravel.com/docs/queues) yang kuat.
- [Penyiaran event real-time](https://laravel.com/docs/broadcasting).

Laravel mudah diakses, kuat, dan menyediakan alat yang diperlukan untuk aplikasi yang besar dan kokoh.

## Belajar Laravel

Laravel memiliki [dokumentasi](https://laravel.com/docs) dan pustaka tutorial video yang paling lengkap dan menyeluruh di antara semua framework aplikasi web modern, memudahkan untuk memulai dengan framework ini.

Anda juga dapat mencoba [Laravel Bootcamp](https://bootcamp.laravel.com), di mana Anda akan dipandu dalam membangun aplikasi Laravel modern dari awal.

Jika Anda tidak suka membaca, [Laracasts](https://laracasts.com) dapat membantu. Laracasts berisi ribuan tutorial video tentang berbagai topik termasuk Laravel, PHP modern, unit testing, dan JavaScript. Tingkatkan keterampilan Anda dengan mempelajari pustaka video komprehensif kami.

## Sponsor Laravel

Kami ingin mengucapkan terima kasih kepada sponsor berikut yang telah mendanai pengembangan Laravel. Jika Anda tertarik untuk menjadi sponsor, silakan kunjungi [program Laravel Partners](https://partners.laravel.com).

### Premium Partners

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[WebReinvent](https://webreinvent.com/)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[DevSquad](https://devsquad.com/hire-laravel-developers)**
- **[Jump24](https://jump24.co.uk)**
- **[Redberry](https://redberry.international/laravel/)**
- **[Active Logic](https://activelogic.com)**
- **[byte5](https://byte5.de)**
- **[OP.GG](https://op.gg)**

## Berkontribusi

Terima kasih telah mempertimbangkan untuk berkontribusi pada framework Laravel! Panduan kontribusi dapat ditemukan di [dokumentasi Laravel](https://laravel.com/docs/contributions).

## Kode Etik

Untuk memastikan bahwa komunitas Laravel terbuka untuk semua, harap tinjau dan patuhi [Kode Etik](https://laravel.com/docs/contributions#code-of-conduct).

## Kerentanan Keamanan

Jika Anda menemukan kerentanan keamanan dalam Laravel, silakan kirim e-mail ke Taylor Otwell melalui [taylor@laravel.com](mailto:taylor@laravel.com). Semua kerentanan keamanan akan segera ditangani.

## Instalasi & Pengaturan

### Prasyarat

Sebelum menginstal proyek ini, pastikan sistem Anda memenuhi persyaratan berikut:

- PHP >= 8.1
- Composer
- Node.js & NPM
- MySQL atau MariaDB
- Git

### Clone & Install

1. Clone repositori ini:
   ```bash
   git clone <repository-url>
   cd blog-app
   ```

2. Install dependensi PHP:
   ```bash
   composer install
   ```

3. Install dependensi JavaScript:
   ```bash
   npm install
   ```

4. Salin file environment:
   ```bash
   cp .env.example .env
   ```

5. Generate application key:
   ```bash
   php artisan key:generate
   ```

6. Konfigurasi database di file .env:
   ```env
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=blog_app
   DB_USERNAME=root
   DB_PASSWORD=
   ```

7. Jalankan migrasi database:
   ```bash
   php artisan migrate --seed
   ```

8. Compile assets:
   ```bash
   npm run dev
   ```

9. Jalankan aplikasi:
   ```bash
   php artisan serve
   ```

Aplikasi sekarang dapat diakses di `http://localhost:8000`

## Lisensi

Framework Laravel adalah perangkat lunak open-source yang dilisensikan di bawah [lisensi MIT](https://opensource.org/licenses/MIT).
