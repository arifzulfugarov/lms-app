# Learning Management System (LMS) – Laravel Project

## 📘 Overview

This is a Laravel-based Learning Management System (LMS) application that supports two user roles: **Teacher** and **Student**. The application allows Teachers to manage subjects and tasks, while Students can enroll in subjects and submit solutions to tasks.

> ⚙️ Framework: Laravel 12  
> 🧩 Database: SQLite  
> 💻 UI: Tailwind CSS

---

## ✅ Features

### 🧑‍🏫 Teacher Features
- View and manage own subjects
- Create, edit, delete (soft delete) subjects
- View subject details including enrolled students
- Create and manage tasks under each subject
- View task details including submitted solutions
- Evaluate student submissions

### 🎓 Student Features
- Register and login (only as students)
- Take or leave subjects
- View subject and task details
- Submit solutions to tasks (multiple times allowed)

### 🔐 Authentication
- Laravel Breeze or Laravel UI can be used
- Only Students can register themselves
- Teachers are pre-seeded in the database

---

## 🛠️ Setup Instructions

Before starting, make sure you have PHP, Composer, Node.js, and SQLite installed.

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/lms-laravel.git
cd lms-laravel
