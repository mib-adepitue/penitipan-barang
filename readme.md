Aplikasi ini adalah aplikasi penitipan barang dengan sistem Penitip akan menitipkan barangnya ke petugas, lalu sistem akan memberi tegihan atas penitipannya sebanyak (jumlah_barang*jumlah_hari*45000)+10%. aplikasi ini di kelola oleh superadmin, admin, kasir.

1. ini merupakan aplikasi inventaris menggunakan laravel 5.7, dan menggunakan ajax
2. aplikasi ini menggunakan database mysql
3. pastikan anda telah menginstal composer atau apapun untuk menjalankan laravel
4. akses folder project dan jalankan `composer install`

Konfigurasi

1. Download atau clone file ini
2. pastikan step no. 2 diatas sudah di laksanakan.
3. buka cmd lalu aktifkan direktori/folder yang telah Anda download.
4. di aplikasi ini saya menggunakan yajra Datatables maka perlu Anda tambahkan yajra di folder project Anda, masuk ke folder project Anda lalu ketik sebagai berikut di cmd
5. ubah .env.example menjadi .env
6. set pada bagian berikut menjadi informasi database Anda
    > DB_CONNECTION=mysql
    > DB_HOST=127.0.0.1
    > DB_PORT=3306
    > DB_DATABASE=homestead
    > DB_USERNAME=homestead
    > DB_PASSWORD=secret
7. akses folder project di cmd atau terminal lalu jalankan perintah `php artisan serve`
8. jika selesai,silakan login dengan mengetik di browser localhost:8000, atau sesuai server Anda
9. untuk melihat gambar dari sistem, maka ketikkan di cmd `php artisan storage:link`
10. selamt menikmati
