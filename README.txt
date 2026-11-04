Modul 9 - Laravel & MVC. Salin folder app, routes, resources ke proyek Laravel:
  composer create-project laravel/laravel praktik-web
  cd praktik-web
  php artisan make:model Buku
  php artisan make:controller BukuController
Timpa file dari zip ini, lalu: php artisan serve
Uji: /buku, /buku?cari=Laravel, /buku/BK004, /buku/BK999
