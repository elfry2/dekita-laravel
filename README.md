# dekita-laravel
A to-do list app built with Laravel 10, which I use as a template for my other Laravel projects.

![A screenshot of task list](https://github.com/elfry2/dekita-laravel/assets/47256917/271355bd-d927-471e-bfa4-a1b33d9b8e50 "A screenshot of task list")



## Installation
1. Create a database
2. Copy the ```.env.example``` file and rename it to ```.env```
3. Edit the ```.env``` file to match your environment configuration
4. Execute
```bash
composer update
npm install
npm run build
php artisan migrate:fresh --seed
php artisan key:generate
php artisan storage:link
```
## Usage
Execute
```bash
php artisan serve
```
then visit http://localhost:8000 (or whichever port ```artisan``` serves on) on your browser.

## To Do
See [TODO.md](TODO.md).
