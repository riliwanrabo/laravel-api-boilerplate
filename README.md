This is a boilerplate for writing RESTful API projects using Laravel, a "Starter Kit" you can use to build your API in seconds.

##### Packages:

* JWT-Auth - [tymondesigns/jwt-auth](https://github.com/tymondesigns/jwt-auth)
* Laravel-CORS [barryvdh/laravel-cors](http://github.com/barryvdh/laravel-cors)

##### Require:
* PHP: ^8.0

## Features

* JWT Authentication
* Basic Features: Registration, Login, Update Profile & Password
* JSON API Format response.
* Unit/Feature Testing. (WIP)



## Installation
`composer create-project kennethtomagan/laravel-6-api-boilerplate myNewProject`;


#### Install Dependencies

```
$ composer install
```

#### Configure the Environment
Create `.env` file:
```
$ cat .env.example > .env
```
Run `php artisan key:generate` and `php artisan jwt:secret`

#### Migrate and Seed the Database
```
$ php artisan migrate:fresh --seed
```
