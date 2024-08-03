### System Specifications

| Requirements | Versions |
| :----------: | :------: |
|   LARAVEL    |   10.x   |
|     PHP      |  8.2.22  |
|    MYSQL     |   1.6    |
|    XAMPP     |   3.3.0  |
|    Node      |   16.18  |
|  Composer    |   2.7.7  |

## Configuration

1.  Clone this repository.

    ```bash
        $   https://github.com/MindfulJourney/QA-Engineering-Exam---Danao.git
    ```
    note: Open the xampp first (apache and mySQL before running the code.)

2.  Recreate environment variable file.

    ```bash
        $   cp .env.example .env
    ```

3.  Install composer and npm.

    ```bash
        $   composer install && npm install
    ```

4.  Generate Application Key.

    ```bash
        $   php artisan key:generate
    ```

5.  Create your DB and update your DB configs in .env.

    ```bash
        $   DB_CONNECTION=mysql
        $   DB_HOST=127.0.0.1
        $   DB_PORT=3306
        $   DB_DATABASE=laravel
        $   DB_USERNAME=root
        $   DB_PASSWORD=
    ```

6.  Execute Database Migration and Seeders.

    ```bash
        $   php artisan migrate --seed
    ```
    note: to create dummy account:
    Dummy Admin Created:
    Email: ocie.hartmann@example.org
    Password: password

7.  Run local server.

    ```bash
        $   php artisan serve
    ```

8.  Front Build.

    ```bash
        $   npm run dev
        $   npm run build
    ```
