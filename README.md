# Laravel To-Do List

This is a simple To-Do list application built using the Laravel framework.

## Installation

1. a Clone the repository:
    ```bash
    git clone https://github.com/jkrajpootbdn94/todo-list-in-laravel
    ```
    OR
1. b Clone by Composer:
    ```bash
    composer create jugendra/laravel-todo
    ```
2. Install dependencies:
    ```bash
    composer install
    ```
3. **Update `.env` file** with the following:
    ```bash
    APP_NAME=YourAppName
    APP_ENV=local
    APP_KEY=base64:generated-key
    APP_DEBUG=true
    APP_URL=http://localhost

    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=your-database-name
    DB_USERNAME=your-database-username
    DB_PASSWORD=your-database-password
    ```
4. Run migrations:
    ```bash
    php artisan migrate
    ```
5. Start the development server:
    ```bash
    php artisan serve
    ```
---

## Requirements

- PHP >= 8.x
- Composer
- MySQL
- Node.js & NPM (if applicable)

---

## Usage

Once the server is running, visit [http://localhost:8000](http://localhost:8000) to start using the To-Do list.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


