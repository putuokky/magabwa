### Application Features

-   aaa
-   bbb

### Technology Features

-   Laravel 12
-   Filament 3.3

## Installation Guide

### Prerequisites

-   PHP >= 8.2
-   Composer

### Installation Steps

1. Clone the repository:
2. Navigate into the project directory:

    ```bash
    cd magabwa
    ```

3. Install PHP dependencies:

    ```bash
    composer install
    ```

4. Copy the `.env.example` file and rename it to `.env`:

    ```bash
    cp .env.example .env
    ```

5. Generate application key:

    ```bash
    php artisan key:generate
    ```

6. Run database migrations:

    ```bash
    php artisan migrate
    ```

    <!-- ```bash
    php artisan migrate:refresh --seed
    ``` -->

7. Start the development server:
    ```bash
    php artisan serve
    ```
