<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

## Laravel Socialite Google Login

Installation

* Run `git clone`

* From the project root run `cp .env.example .env`

* Configure `.env` file

* Run `composer install`

* Run `php artisan key:generate`

* Run `php artisan migrate`

* Go to `https://console.developers.google.com/`

* Create `new project and app`

* Open `services.php` 

* Modify `'client_id' => 'your id here', 'client_secret' => ' your secret here',`

* Run `php artisan serve`