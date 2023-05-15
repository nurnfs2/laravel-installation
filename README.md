# laravel-installation
Laravel Installation and Folder Structure Assignment
<img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">

Part 1: Laravel Installation

To install Laravel using Composer, I followed these steps:
1. First, I made sure that I have Composer installed on my computer.
2. I opened a command prompt or terminal window and navigated to the directory where I wanted to install Laravel.
3. I opened Laravel official website and follow the documentation for installation the latest version of Laravel. 
4. Next, I ran the following command to install the latest version of Laravel:
composer create-project laravel/laravel myproject

5. After the installation process was complete, I navigated into the project directory by running the following command:
cd myproject

5. To verify that Laravel is installed and working correctly, I ran the development server by executing the following command:
php artisan serve

6. Then, I opened my web browser and visited the URL "http://localhost:8000". I should have seen the Laravel welcome page. Here's a screenshot of the running server:


<img src="https://github.com/nurnfs2/laravel-installation/blob/main/laravel-installl.jpg" width="800" alt="Laravel Logo">


 
Part 2: Laravel Folder Structure

Here's a brief description of each of the following folders in a Laravel project:
•	app: This folder contains the core application code, including models, controllers, views, and other classes that make up the application's functionality.

•	bootstrap: This folder contains the files that are responsible for bootstrapping the application, including the autoloaders, the application instance, and the service container.

•	config: This folder contains all of the application's configuration files, such as the database configuration, mail configuration, and app configuration.

•	database: This folder contains the application's database-related files, including migrations, seeders, and factories.

•	public: This folder contains the publicly accessible files for the application, including the index.php file that serves as the entry point for all requests.

•	resources: This folder contains the application's asset files, such as views, language files, and frontend assets.

•	routes: This folder contains the application's route files, which define the URLs and corresponding actions for the application's endpoints.

•	storage: This folder contains the application's temporary files, such as logs, cache files, and session files.

•	tests: This folder contains the application's automated tests, including unit tests, feature tests, and browser tests.

•	vendor: This folder contains all of the application's dependencies, which are installed via Composer.

To create a new route that displays a "Hello, World!" message, I opened the routes/web.php file and added the following code:

Route::get('/hello', function () {
    return 'Hello, World!';
});



Then, I visited the URL "http://localhost:8000/hello" in my web browser. Here's a screenshot of the running route:

<img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"> 



