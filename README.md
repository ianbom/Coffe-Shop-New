<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# Laravel 9 E-Commerce

This repository is made for beginners to learn Laravel 9 MVC.

## Installation

Install all the dependencies using composer

    composer install

Copy the example env file and make the required configuration changes in the .env file

    cp .env.example .env

Generate a new application key

    php artisan key:generate

Run the database migrations and database seeding (**Set the database connection in .env before migrating**)

    php artisan migrate --seed
    
Create a symbolic link from public/storage to storage/app/public to make files accessible from the web

    php artisan storage:link

Start the local development server

    php artisan serve

You can now access the server at http://localhost:8000

Homepage
![intro2](https://github.com/user-attachments/assets/b3d9e073-e57d-4ef9-b5ff-0a55e1b77dbf)



Menupage
![FireShot Capture 009 - Coffee BOM - 127 0 0 1](https://github.com/user-attachments/assets/f270b5ef-b28c-4863-be58-33eb64e2065a)



Loginpage
![FireShot Capture 007 - Daily UI - Day 1 Sign In - 127 0 0 1](https://github.com/user-attachments/assets/44b58df7-c60a-4106-a57a-1740bd6e8125)



Registerpage
![FireShot Capture 008 - Daily UI - Day 1 Sign In - 127 0 0 1](https://github.com/user-attachments/assets/fc1de73a-23be-403e-8692-97be67b207c2)



Dahsboard
![FireShot Capture 020 - Product dashboard - 127 0 0 1](https://github.com/user-attachments/assets/845a3ae9-7979-4d23-abe2-111c11e0a099)







