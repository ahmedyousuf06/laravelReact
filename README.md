# 🚀 LaravelReact

This is a full-stack starter project using **Laravel** for the backend and **React** (via **Vite**) for the frontend.

The project demonstrates a modern, API-driven architecture, making it ideal for building scalable and reactive web applications.

---

## ✅ Requirements

Ensure the following tools are installed:

- PHP >= 8.1
- Composer
- Node.js >= 16 & NPM
- MySQL (or other supported database)
- Git

---

## 🛠️ Getting Started

Follow these steps to run the project locally:

---

### 1. Clone the Repository

```bash
git clone https://github.com/ahmedyousuf06/laravelReact.git
cd laravelReact

---

### 2. Install PHP Dependencies

```bash
composer install

---

### 3. Install JavaScript Dependencies

```bash
npm install
# or
yarn


### 4. Set Up Environment

```bash
cp .env.example .env

### 5. Generate App Key

```bash
php artisan key:generate

### 6. Run Migrations

```bash
php artisan migrate

### 7. Serve Laravel API

```bash
php artisan serve


### 8. Serve React Frontend

```bash
npm run dev
# or
yarn dev


### 🔗 API & React Integration
- Frontend React components are located in resources/js/.
- Laravel APIs are accessible via routes/api.php.
- Use axios or fetch inside React to communicate with Laravel's API.



