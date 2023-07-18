# Laravel 10 - Toko Online

## Screenshots

### Home

![preview img](/previewHome.png)

### Admin

![preview img](/previewAdmin.png)

## Donwload

1. Clone this project

```bash
  git https://github.com/reynaldomarchell/FinalProject-BackendDevelopment-2022.git project_name
```

2.  Go to the directory of your project

```bash
  cd project_name
```

3. Rename .env.example with .env then edit database and api key

4.

```bash
    composer install --ignore-platform-req=ext-gd
```

5.

```bash
    php artisan key:generate
```

6.

```bash
    php artisan migrate:fresh --seed
```

7.

```bash
    php artisan storage:link
```

8.

```bash
    npm install
```

9.

```bash
    npm run dev
```

10.

```bash
    php artisan serve
```

#### Login

-   email = admin@admin.com
-   password = 123

    NOTES: After you log in with admin account, you will be redirect to home page.
    If you want go to admin panel just type the directory

```bash
    http://127.0.0.1:8000/admin/dashboard
```
