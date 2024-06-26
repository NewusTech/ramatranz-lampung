# Stisla x Laravel

Thanks for awesome free admin panel. Stisla is the most-awesome admin panel I've seen so far. As I love this template very much, I have implemented Stisla in a fresh Laravel 8 app. Simply clone this repo and start building your next Laravel project on top of the awesome Stisla.

This project use [livewire](https://laravel-livewire.com/) to build dynamic user interface and Spatie permission for Role and permission handling

## Installation

Clone the repo:

```shell
git clone https://gitlab.com/NewusTech/ramatrans-travel-lampung.git
```

Install composer packages:

```shell
composer update
```

Install npm packages:

```shell
npm update
```

Run npm dev if you wish to modifie stisla:

```shell
npm run watch
```

And edit or overide your css in resources/saas ans resources/js and it will automatically build your mix css and js

Copy and rename .env.example to .env, update the environmental variables and set an app key:

```shell
php artisan key:generate
```

After that, run all migrations and seed the database:

```shell
php artisan migrate
```

```shell
php artisan db:seed
```

Or if your database is fresh and you haven't done any work yet, then it's safe to call the commands in a single line:

```shell
php artisan migrate:refresh --seed
```

Note that seeding the database is compulsory as it will create the necessary roles and permissions for the user CRUD provided by the project.

Visit <div style="display: inline">http://yoursite.test/login</div> to sign in using below credentials:

### Demo

URL: https://yoursite.test

#### Superadmin Login

-   Email: superadmin@admin.com
-   Password: password

This project comes with a user CRUD and makes the use of [Spatie Roles and Permissions](https://github.com/spatie/laravel-permission) at a very basic level in order to give restricted access to the three roles provided above. You can move forward with the same logic to achieve more complex goals.

### Credits:

-   [Laravel](https://github.com/laravel/laravel)
-   [Stisla Bootstrap 4 Admin Panel Template](https://github.com/stisla/stisla)
-   [Spatie Laravel Roles and Permissions](https://github.com/spatie/laravel-permission)
-   [Laravel livewire](https://laravel-livewire.com/)

### Contribution:

Contribution is welcomed and highly appreciated. Fork the repo, make your updates and initiate a pull request. I'll approve all pull requests as long as they are constructive and follow the Laravel standard practices.
