# 💼 Job Board

A modern job listing platform built with Laravel and Blade. Developed as part of a web development course, this project demonstrates backend and frontend integration using PHP, MySQL, and Laravel.

---

## 📖 Overview

**Job Board** is a full-stack web application that enables users to view, create, and manage job listings. It includes:

- User authentication and access control  
- Data validation with user-friendly error messages  
- Dynamic filtering by keyword and category  
- Responsive UI built with Laravel Blade templates and Tailwind CSS  

Built to showcase practical Laravel and full-stack development skills, this project extends core concepts with custom features and improvements.

---

## 🌐 Live Demo

🚧 *No live demo available at the moment.*

(Optionally, deploy using Laravel Forge, Render, or similar platforms.)

---

## 🚀 Getting Started

### Prerequisites

- PHP 8.1 or higher  
- Composer  
- MySQL  
- Laravel CLI  
- Git  
- Tailwind CSS  

### Installation

```bash
git clone https://github.com/tom-williams26/job-board.git
cd job-board

composer install
cp .env.example .env
php artisan key:generate

# Configure database credentials in .env
php artisan migrate --seed

php artisan serve

Open http://localhost:8000 in your browser.
```

## ✨ Features

- Job listings homepage
- Create, edit, and delete listings (CRUD)
- User authentication (login)
- Filtering listings by keyword and category
- Form validation with error feedback
- Flash messaging
- Protected routes with access control

## 🧭 Roadmap

✅ User login (completed)

🔧 User registration (in progress)

📄 Pagination for job listings

🧹 UI/UX improvements

📸 Add screenshots to README

🚀 Deploy live

## 📌 Project Status

🚧 This project is under active development.

The core functionality is implemented, and additional features like registration, UI enhancements, and deployment are in progress.
