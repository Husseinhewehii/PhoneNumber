
## About Me

Hussein El-Hewehii, PHP Full-Stack Developer with 3 years experience:

- [LinkedIn](https://www.linkedin.com/in/hussein-el-hewehii-768b5a113/).

## Project Description

A Single Page Application That Lists Phone Numbers
- Categorized By: 
    -   Country Name, 
    -   Country Code, 
    -   State(Valid or InValid),
    -   Number
- Filtered By:
    - Country Name
    - State
- Pagination.


## Technologies

### Back-End

- **[PHP 7.4](https://www.php.net/docs.php)**
- **[Laravel 8](https://laravel.com/docs/8.x/installation)**

### Front-End

- **HTML**
- **CSS**
- **[Bootstrap 5](https://getbootstrap.com/)**
- **[JavaScript](https://www.javascript.com/)**
- **[VueJs 3](https://vuejs.org/)**
- **[Vuex](https://vuex.vuejs.org/)**

### Database

- **[SQLite](https://www.sqlite.org/docs.html)**


## Prerequisites

- **[PHP >= 7.3](https://www.php.net/downloads.php)**
- **[Composer](https://getcomposer.org/)**
- **[Node](https://nodejs.org/en/download/)**


## Installation


> Download Project 

``` bash
git clone https://github.com/Husseinhewehii/PhoneNumber.git
```

> Move To Project Directory

``` bash
cd PhoneNumber
```

> Install Composer Packages

``` bash
composer install
```

> Install Node Packages

``` bash
npm install
```

> Compile Node Packages

``` bash
npm run dev
```

> Create .env file

``` bash
cp .env.example .env
```

> Generate Key

``` bash
php artisan key:generate
```

> Create .env.testing file

``` bash
cp .env .env.testing
```

> Configure .env file

``` bash
APP_URL=http://localhost:8000
MIX_APP_URL="${APP_URL}"

DB_CONNECTION=sqlite
#DB_HOST=127.0.0.1
#DB_PORT=3306
#DB_DATABASE=laravel
#DB_USERNAME=root
#DB_PASSWORD=
```

> Configure .env.testing file

``` bash
DB_CONNECTION=sqlite
#DB_HOST=127.0.0.1
#DB_PORT=3306
DB_DATABASE=testing_database
#DB_USERNAME=root
#DB_PASSWORD=
```


> You Don't Need to Create Or Migrate Database Cause I allowed the Database files to be uploaded to Github
but you can seed. 

``` bash
php artisan db:seed
```

> Run On Local Machine

``` bash
php artisan serve
```
