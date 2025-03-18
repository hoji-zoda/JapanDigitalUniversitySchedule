# Japan Digital University Schedule

This repository is for managing and scheduling courses at Japan Digital University. It is primarily written in PHP and Blade.

## Description

Japan Digital University Schedule is a web application designed to help manage and schedule university courses efficiently. The application allows administrators to create, update, and delete schedules, and provides students with an easy-to-use interface to view their schedules.

## Installation

To install this project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/hoji-zoda/JapanDigitalUniversitySchedule.git
    ```
2. Navigate to the project directory:
    ```bash
    cd JapanDigitalUniversitySchedule
    ```
3. Install the dependencies:
    ```bash
    composer install
    npm install
    ```
4. Set up the environment variables by copying the `.env.example` file to `.env` and updating the necessary fields:
    ```bash
    cp .env.example .env
    ```
5. Generate the application key:
    ```bash
    php artisan key:generate
    ```
6. Run the migrations to set up the database:
    ```bash
    php artisan migrate
    ```

## Usage

To start the development server, run the following command:
```bash
php artisan serve
