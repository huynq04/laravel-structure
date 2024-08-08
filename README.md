# Cách khởi chạy 1 project laravel khi mới clone về
    1. composer install
    2. Tạo file .env từ file mẫu .env.example:
        cp .env.example .env
    3. Tạo key 
        php artisan key:generate
    4. chạy migration để tạo các bảng cần thiết
        php artisan migrate
    5. Khởi chạy ứng dụng
        php artisan serve
