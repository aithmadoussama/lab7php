# 🎓 Student Management System – LAB8

![PHP](https://img.shields.io/badge/PHP-8.x-blue)
![Architecture](https://img.shields.io/badge/Architecture-MVC-green)
![Security](https://img.shields.io/badge/Security-CSRF%20Protected-red)
![Status](https://img.shields.io/badge/Status-Academic%20Project-orange)
![License](https://img.shields.io/badge/License-Educational-lightgrey)

---

## 📌 Overview

This project is a **Student Management Web Application** developed in **PHP** using a custom **MVC architecture**.

It provides a secure system for managing students and departments (filières), including authentication and protected routes.

---

## ✨ Features

- 🔐 Secure Authentication (Login / Logout)
- 👨‍🎓 Student Management (CRUD)
- 🏫 Department / Filière Management
- 🛡️ CSRF Protection
- 🔎 Data Validation & Sanitization
- 🧭 Custom Router
- 🗃️ DAO Pattern for Database Access
- 📝 Logging System

---

## 🏗️ Project Architecture

```
lab8/
│
├── public/              # Application entry point (index.php)
├── src/
│   ├── Container/       # Application Factory
│   ├── Controller/      # MVC Controllers
│   ├── Core/            # Router, Request, Response, View
│   ├── Dao/             # Database Access Layer
│   └── Security/        # Authentication & Security
│
├── views/               # PHP Views
├── logs/                # Log files
└── docs/                # Documentation
```

---

## ⚙️ Technologies Used

- PHP (OOP)
- MySQL
- MVC Architecture
- DAO Design Pattern
- HTML / CSS
- Web Security Best Practices

---

## 🚀 Installation Guide

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/lab8.git
```

### 2️⃣ Database Setup

- Create a MySQL database
- Update credentials in:

```
src/Dao/DBConnection.php
```

### 3️⃣ Run the Application

- Place project inside `htdocs` (XAMPP)  
  OR
- Configure a Virtual Host

Access via:

```
http://localhost/lab8/public
```

---

## 🔐 Security Implementation

The system includes:

- CSRF Token Protection
- Input Validation
- Data Sanitization
- Authentication Middleware
- Logging System

---

## 👨‍💻 Main Components

### 🔄 Router
Handles:
- URL Parsing
- Controller Dispatching
- Method Execution

### 🗄️ DAO Layer
Encapsulates SQL operations:

- `EtudiantDao.php`
- `FiliereDao.php`
- `AdminDao.php`

---

## 📷 Screenshots

_Add screenshots of your application here for better presentation._

Example:

```
![Dashboard Screenshot](docs/screenshot1.png)
```

---

## 📚 Educational Purpose

This project was developed as part of **LAB8** for academic purposes.

---

## 📌 Future Improvements

- Role-based access control
- REST API integration
- Improved UI with Bootstrap
- Unit testing implementation

---

## 🧑‍🎓 Author

Developed as part of a university lab project.

---

## 📄 License

Educational use only.

## Vidéo de démonstration montrant la réussite du test

 https://github.com/user-attachments/assets/4ea46a31-de86-4527-bdcb-3bde47659364
