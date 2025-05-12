# Laravel Blog API

A RESTful API built with Laravel 12 for managing blog posts, tags, and comments.

## 🚀 Features

- User authentication (via Laravel Sanctum)
- Create, read, update, delete (CRUD) for:
  - Posts
  - Comments
  - Tags
- Associate tags with posts (many-to-many)
- Comment on posts
- JSON responses for all endpoints

---

## 📦 Tech Stack

- **Backend:** Laravel 12
- **Database:** MySQL (or any Laravel-supported DB)
- **Authentication:** Laravel Sanctum

---

## 📁 Installation

```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan db:seed # Optional
