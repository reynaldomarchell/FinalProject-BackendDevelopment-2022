# Laravel 10 - Apparance

### Created By

    Reynaldy Marchell Bagas Adji
    Reynaldo Marchell Bagas Adji
    Stanislaus Kanaya Jerry Febriano
    Aaron Kenny Rijadi

## Screenshots

### Home

![preview img](/previewHome.png)

### Admin

![preview img](/previewAdmin.png)

## Deploy

1. Clone this project

```bash
  git https://github.com/reynaldomarchell/FinalProject-BackendDevelopment-2022.git apparance
```

2.  Go to the directory of this project

```bash
  cd apparance
```

3. Rename .env.example with .env then edit the database and api key

4. Open terminal and type

```bash
    composer install --ignore-platform-req=ext-gd
```

5. Generate key

```bash
    php artisan key:generate
```

6. Migrate the database

```bash
    php artisan migrate:fresh --seed
```

7. Create storage link to public

```bash
    php artisan storage:link
```

8. Install npm

```bash
    npm install
```

9. Run node server

```bash
    npm run dev
```

10. While node server running, open new terminal and type

```bash
    php artisan serve
```

#### Login

-   Email = admin@admin.com
-   Password = 123

NOTES: After you log in with admin account, you will be redirect to home page. If you want to open admin panel just type the directory

```bash
    http://127.0.0.1:8000/admin/dashboard
```
