# Laravel Student Test (based on Laravel 8.x)

- Application to manage and take the quiz online.
- Admin can create test, manage tests and students.
- Students can apply for the test and view results and answer sheets.



![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)


```
Admin login
email: admin@gmail.com
password : password
```

# Installation

1. **Clone or download this Repository.**
2. **Run the command**
   ```
   composer install
   ```
   if you get any problems while running above command then run the following command.
   ```
   composer install --ignore-platform-reqs
   ```

3. **Create `.env` file by copying the `.env.example`, or run the following command**
   ```
   cp .env.example .env
   ```

4. **Update the database name and credentials in `.env` file**  
   ```
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE="Your database name"
    DB_USERNAME="your database username"
    DB_PASSWORD="your database password"
   ```
5. **Run the following command**
   ```
   php artisan migrate:fresh --seed
   ```
6. **Run npm command**
   ```
   npm install
   ```
7. **Run the command to compile the theme**
    ```
    npm run dev
    ```
8. **Finally run the application**
   ```
   php artisan serve
   ```


# Screenshots

## Admin side

![image](https://user-images.githubusercontent.com/119964141/208668239-a454134d-2b1f-4dcd-a342-ea91a4f9b5db.png)
![image](https://user-images.githubusercontent.com/119964141/208668856-ca4682de-a10f-442f-b5b9-439de24602d3.png)



