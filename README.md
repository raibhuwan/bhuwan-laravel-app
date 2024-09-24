# Simple Laravel App

## Installation

### Prerequisites
You will need Git, Composer, PHP, Node and NPM

1. Clone the repository
    ```
    git clone https://github.com/raibhuwan/bhuwan-laravel-app.git
    cd bhuwan-laravel-app
    ```

2. Setup environment files
    ```
    cp .env.example .env
    ``` 

3. Install external dependencies (alternatively see Laravel Sail)
    ```
    composer install
    nvm install
    nvm use
    npm run dev
    ``` 

4. Setup application
    ```
    php artisan key:generate
    php artisan breeze:install blade
    php artisan migrate
    php artisan serve
    ```