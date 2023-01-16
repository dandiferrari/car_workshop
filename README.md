<!-- TODO: Complete the description and about the appropriate license. -->
# Workshop

Documents management application based on Laravel and vue. Includes the following integrations:

<!-- - Mailchimp newsletter subscription
- Sendgrid email marketing
- Cloudinary assets upload -->
- Entity Relationship Diagram https://drive.google.com/file/d/1nw-aUP0CrEMeV9axAjPWsffIq3RNEF_B/view?usp=sharing
- State Machine Diagram https://drive.google.com/file/d/10qNtqzvLEQks5Eaz2My9CbszZDnQWrZ7/view?usp=sharing

## Getting Started :rocket:

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites :clipboard:

The programs you need are:

-   [Composer](https://getcomposer.org/download/).
-   [Node.js](https://nodejs.org/en/download/).
-   Database and a web server with PHP.

### Installing 🔧

Duplicate the file .env.example as .env and set your credential for the database in.

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=database_name
DB_USERNAME=root
DB_PASSWORD=
```


Then install the PHP packages.

```
composer install
```

Generate the application key.

```
php artisan key:generate
```

Then install the JavaScript packages with npm.

```
npm install
```

Finally generate the database with fake data:

```
php artisan migrate --seed
```

## Running the project :computer:

First generate the public files with

```
npm run dev
```

Note: Each time SASS and JavaScript files are updated you need to run the past command, to make it easier run:

```
npm run watch
```

Finally run the serve

```
php artisan serve
```

## Built With 🛠️

-   [Laravel 9.0](https://laravel.com/docs/9.x/) - Framework PHP.

