# Unistock

Unistock is a single page web application built using Laravel, Vue.js, Inertia.js and Tailwind CSS. This platform was developed as a project during our graduation at Unicentro and is an simple and efficient inventory management that helps small to medium businesses manage their stock efficiently.

## Project History

Unistock was developed as part of a major project for our graduation. The project was made in pairs by us, Gabriel Marochi Schmidt and Gabriel do Nascimento de Lima, and it represents the culmination of our studies and shared passion for software development. Together, we designed and implemented a solution to address real-world challenges in inventory management, incorporating cutting-edge technologies and best practices.

## Tech Stack

- **Backend**: Laravel 10
- **Frontend**: Vue 3, Tailwind CSS, Element Plus, Flowbite
- **SPA Handling**: Inertia.js
- **Authentication**: Laravel Breeze
- **Database**: PostgreSQL
- **Tooling**: Composer, NPM, Vite

## Features

- **Inventory Management**: Easily add, edit, remove, and track stock items with quantity, category, and location.
- **Supplier Management**: Register, edit, and manage supplier data, linking them to specific inventory items.
- **User Authentication & Authorization**: Secure login using Laravel Breeze and policies.
- **Modern Frontend UI**: Built with Vue 3, Tailwind CSS, Element Plus, and Flowbite for a clean and responsive interface.
- **Inertia.js Integration**: Seamless single-page application (SPA) experience without building a separate API.
- **Responsive Design**: Optimized for desktop, tablet, and mobile use.
- **Seeders and Factories**: Seeders and Factories: Quickly populate the database for development and testing using seeders and factories.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/GabrielNLima/ProjetoIntegrador-III.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ProjetoIntegrador-III
   ```
3. Install dependencies:
   ```bash
   composer install
   npm install
   ```
4. Set up environment variables:
   ```bash
   cp .env.example .env
   ```
   Update the `.env` file with your database and other configurations.


5. Generate application key:
   ```bash
   php artisan key:generate
   ```
6. Run database migrations:
   ```bash
   php artisan migrate
   ```

## Usage

1. Start the development server:

   ```bash
   php artisan serve
   ```
2. In other terminal, start the frontend dev server:

    ```bash
    npm run dev
    ```
3. Access the application at `http://localhost:8000`.

## Contributing

Contributions are welcome! Please follow the [contribution guide](https://laravel.com/docs/contributions) and adhere to the [code of conduct](https://laravel.com/docs/contributions#code-of-conduct).

## License

This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
