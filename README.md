<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

## About eCanteen

eLibrary is a web-based platform designed to facilitate e-commerce for local canteens. Our goal is to streamline transactions, eliminating unnecessary steps and providing people with a quick and convenient way to order and enjoy their meals.

The project created with Laravel framework and Tailwind CSS for the css framework.

## Installation Guide
Prerequsite :

Create database named `ecanteen`


Installation Commands :
- composer install
- cp .env.example .env
- php artisan storage:link
- php artisan key:generate
- php artisan migrate:fresh --seed


In one line cmd :

`composer install && cp .env.example .env && php artisan storage:link && php artisan key:generate && php artisan migrate:fresh --seed`


Additional command :
- npm install
- npm run dev, or
- npm run build


Login Credentials :

Email : admin@example.com

Password : password

*Make sure that XAMPP/Laragon is turned on

## Screenshots

<p align="center"><a target="_blank"><img src="https://i.postimg.cc/tp8WTMN8/ecanteen1.png" width="800"></a></p>
<p align="center"><a target="_blank"><img src="https://i.postimg.cc/W37WJ9v2/ecanteen2.png" width="800"></a></p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.
