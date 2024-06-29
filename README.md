```markdown
# PHP Website Checker

## Deskripsi
Script PHP sederhana untuk memeriksa apakah sebuah website menggunakan PHP atau tidak. Script ini bekerja dengan memeriksa header HTTP dari website target untuk mencari indikasi penggunaan PHP.

## Fitur
- Memeriksa penggunaan PHP pada website target
- Mudah digunakan dan dapat disesuaikan

## Persyaratan
- PHP 5.4 atau lebih tinggi
- Akses internet untuk memeriksa website target

## Instalasi
1. Pastikan PHP sudah terinstal di sistem Anda.
2. Unduh file `check_php.php` ke direktori lokal Anda.

## Penggunaan
1. Buka file `check_php.php` menggunakan editor teks.
2. Ubah nilai variabel `$url` dengan URL website yang ingin Anda periksa.
3. Jalankan script melalui command line atau web server:
   ```
   php check_php.php
   ```
   atau buka melalui browser jika menggunakan web server.

## Contoh
```php
$url = 'https://www.example.com'; // Ganti dengan URL yang ingin Anda periksa
if (checkPHP($url)) {
    echo "Website menggunakan PHP.";
} else {
    echo "Website tidak menggunakan PHP atau tidak dapat dideteksi.";
}
```

## Catatan Penting
- Script ini hanya dapat mendeteksi penggunaan PHP jika server mengizinkan header 'X-Powered-By' ditampilkan.
- Beberapa server mungkin menyembunyikan informasi ini untuk alasan keamanan.
- Gunakan script ini dengan bijak dan hanya pada website yang Anda miliki izin untuk memeriksanya.

## Kontribusi
Kontribusi untuk meningkatkan script ini sangat diterima. Silakan fork repositori ini dan ajukan pull request dengan perubahan Anda.

## Lisensi
[MIT License](https://opensource.org/licenses/MIT)

## Kontak
Jika Anda memiliki pertanyaan atau saran, silakan buka issue di repositori ini.
```

