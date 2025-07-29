<p align="center">
  <img src="https://img.shields.io/badge/Status-Completed-blue?style=flat-square" alt="Status"/>
  <img src="https://img.shields.io/github/license/GabrielNLima/ProjetoIntegrador-III?style=flat-square&color=blue" alt="License"/>
</p>

# 📦 Unistock - Inventory Management System

Unistock is a Single Page Application (SPA) built with Laravel, Vue.js, Inertia.js, and Tailwind CSS. This platform was developed as a university project and serves as a simple and efficient inventory management system to help small and medium-sized businesses manage their stock.

---

## 📜 Project History

Unistock was developed as part of a major project for our undergraduate degree at UNICENTRO. The project was created by me, Gabriel Marochi Schmidt, and Gabriel do Nascimento de Lima, and it represents the culmination of our studies and our shared passion for software development. Together, we designed and implemented a solution to address real-world challenges in inventory management, incorporating modern technologies and best practices.

---

## 🛠️ Tech Stack

- **Backend:** Laravel 10
- **Frontend:** Vue 3, Tailwind CSS, Element Plus, Flowbite
- **SPA Handling:** Inertia.js
- **Database:** PostgreSQL
- **Tooling:** Vite, Composer, NPM

[![My Skills](https://skillicons.dev/icons?i=laravel,php,vue,js,tailwind,postgres,vite,npm)](https://skillicons.dev)


---

## ✨ Features

- ✅ **Inventory Management**: Easily add, edit, remove, and monitor stock items, including quantity, category, and location.
- ✅ **Supplier Management**: Register, edit, and manage supplier data, linking them to specific stock items.
- ✅ **User Authentication & Authorization**: Secure login using Laravel Breeze and access policies.
- ✅ **Modern User Interface**: Built with Vue 3, Tailwind CSS, Element Plus, and Flowbite for a clean and responsive UI.
- ✅ **Inertia.js Integration**: A fluid Single Page Application (SPA) experience without the need to build a separate API.
- ✅ **Responsive Design**: Optimized for use on desktops, tablets, and mobile phones.
- ✅ **Seeders & Factories**: Quickly populate the database for development and testing using seeders and factories.

---

## 🚀 Getting Started

### Installation

1.  Clone the repository:
    ```bash
    git clone [https://github.com/GabrielNLima/ProjetoIntegrador-III.git](https://github.com/GabrielNLima/ProjetoIntegrador-III.git)
    ```
2.  Navigate to the project directory:
    ```bash
    cd ProjetoIntegrador-III
    ```
3.  Install dependencies:
    ```bash
    composer install
    npm install
    ```
4.  Set up environment variables:
    ```bash
    cp .env.example .env
    ```
    Update the `.env` file with your database settings and other necessary information.

5.  Generate the application key:
    ```bash
    php artisan key:generate
    ```
6.  Run the database migrations:
    ```bash
    php artisan migrate
    ```

### Usage

1.  Start the development server:
    
    ```bash
    php artisan serve
    ```
2.  In another terminal, start the frontend development server:
    
    ```bash
    npm run dev
    ```
3.  Access the application at `http://localhost:8000`.

---

## 🤝 Contributing

Contributions are welcome! Please follow the [contribution guide](https://laravel.com/docs/contributions) and adhere to the [code of conduct](https://laravel.com/docs/contributions#code-of-conduct).

---

## 📄 License

This project is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT). See the [LICENSE](LICENSE) file for more details.
