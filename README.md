# Laravel10 with WebpackMix, Bootstrap5, and jQuery

This is a starter template for a Laravel 10 project with WebpackMix, Bootstrap5, and jQuery. It provides a solid starting point for building modern web applications with Laravel and popular front-end tools.

## Features

- Laravel 10
- WebpackMix for building assets
- Bootstrap5 for styling
- jQuery for DOM manipulation
- Easy to customize and extend

## Installation

1. Clone this repository: `git clone https://github.com/your-username/laravel10-webpackmix-bootstrap5-jquery.git`
2. Navigate to the project directory: `cd laravel10-webpackmix-bootstrap5-jquery`
3. Install dependencies: `composer install && npm install`
4. Create a new `.env` file: `cp .env.example .env`
5. Generate a new application key: `php artisan key:generate`
6. Configure your database settings in `.env`
7. Run migrations: `php artisan migrate`
8. Build assets: `npm run dev`
9. Start the development server: `php artisan serve`

## Usage

This project provides a basic structure for building web applications with Laravel and front-end tools. You can customize and extend it to fit your specific needs.

### Front-end

All front-end assets are located in the `resources/assets` directory. WebpackMix is used to build and compile assets, which are then stored in the `public` directory.

To build assets for development, run:

```
npm run dev
```

To build assets for production, run:

```
npm run production
```

### Back-end

All back-end code is located in the `app` directory. Laravel follows the MVC pattern, so you'll find models, controllers, and views in their respective directories.

## Contributing

Thank you for considering contributing to this project! Please feel free to submit issues and pull requests.

## License

This project is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).
