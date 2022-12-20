# Laravel Student Test (based on Laravel 8.x)

- Application to manage and take the quiz online.
- Admin can create test, manage tests and students.
- Students can apply for the test and view results and answer sheets.

# Installation

1. **Clone or download this repo https://github.com/niral21/student-test.git**
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

## Admin

![image](https://user-images.githubusercontent.com/119964141/208668239-a454134d-2b1f-4dcd-a342-ea91a4f9b5db.png)
![image](https://user-images.githubusercontent.com/119964141/208668856-ca4682de-a10f-442f-b5b9-439de24602d3.png)

## Student

![image](https://user-images.githubusercontent.com/119964141/208670291-0b1c7294-ac96-4b5e-a816-54f7402e1921.png)
![image](https://user-images.githubusercontent.com/119964141/208671224-e3a66c5e-15f9-4cb8-9bdf-b0a36c68e217.png)
![image](https://user-images.githubusercontent.com/119964141/208671436-764f61fd-da49-48ee-9ba2-b75614e067bd.png)

# Login Credentails

**Admin** 
```
email : admin@gmail.com
password : password
```

**Student** 
```
email : student@gmail.com
password : password
```



