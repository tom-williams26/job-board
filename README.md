# 💼 Job Board

A modern job listing platform built with Laravel and Blade. This project was developed as part of a web development course, showcasing backend and frontend integration using PHP, MySQL, and the Laravel framework.

---

## 📖 Overview

The **Job Board** is a full-stack web application that allows users to view, create, and manage job listings. It features authentication, data validation, dynamic listing filtering, and clean, responsive UI powered by Laravel's Blade templating engine.

This project was built by following a course and extended with custom features and improvements to demonstrate practical understanding of Laravel and full-stack development concepts.

---

## 🌐 Live Demo

🚧 *Live demo not currently available* (Optional: Deploy to Laravel Forge, Render, or another hosting platform if you'd like to showcase it live)

---

## 🚀 Getting Started

To run this project locally:

### Prerequisites
- PHP >= 8.1  
- Composer  
- MySQL  
- Laravel CLI  
- Git Version Control  
- GitHub  
- Blade Templating  
- Tailwind CSS

### Installation

```bash
git clone https://github.com/tom-williams26/job-board.git
cd job-board

# Install dependencies
composer install

# Create environment file
cp .env.example .env

# Generate application key
php artisan key:generate

# Set up your database credentials in .env, then run:
php artisan migrate --seed

# Start the development server
php artisan serve

Then open http://localhost:8000 in your browser.

---

✨ **Features**

- Job listings homepage
- Create, edit, and delete listings (CRUD)
- User authentication (login)
- Filtering listings by keyword and category
- Form validation and user-friendly error messages
- Flash messaging and user feedback
- Protected routes and access control

---

🧭 **Roadmap**

Planned features and improvements:

- ✅ User login (implemented)
- 🔧 User registration functionality
- 📄 Pagination for job listings
- 🧹 Improved UI design and layout refinements
- 📸 Add screenshots to this README
- 🚀 Deploy project live using Forge or another platform

---

📌 **Project Status**

🚧 This project is under active development.

The core functionality is implemented, and additional features like registration, UI enhancements, and deployment are in progress. Contributions and feedback are welcome.
