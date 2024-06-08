# Laravel React Chat App

[![image](https://github.com/akashsagar2805/laravel-chat-app/assets/55270400/f068ed13-07a1-4ad7-b4d4-75f4ec57f4ae)](https://github.com/akashsagar2805/laravel-chat-app/assets/55270400/e23c876d-f8a3-4bf7-a5a5-5b0505386d3c)


## Introduction

Laravel React Chat App is a real-time chat application that allows users to send and receive text messages, audio messages, video messages, emojis, and attach files. The application leverages Laravel for the backend and React for the frontend to deliver a seamless and interactive user experience.

## Prerequisites

- PHP >= 7.3
- Composer
- Node.js and npm (optional, for asset compilation)
- MySQL or another supported database

## Installation

Follow these steps to set up the project:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/akashsagar2805/laravel-chat-app.git
   cd laravel-chat-app

2. **Install PHP dependencies, copy .env file, and generate application key**

    ```bash
   composer install
   cp .env.example .env
   php artisan key:generate
   
3. **Configure environment variables**
     ```bash
   Add database name and all required variables in .env

4. **Run migrations and seeders**
     ```bash
    php artisan migrate
    php artisan db:seed

5. **Run reverb installation and link storage**
    ```bash
   php artisan reverb:install
   php artisan storage:link

6. **Install Node.js dependencies and compile assets**
    ```bash
   npm install
   npm run dev

7. **Start the websocket server and serve the application**
     ```bash
   php artisan reverb:start
   php artisan serve
   The application will be available at http://localhost:8000








    
