**Agriculture Management System
📌 Project Overview**

The Agriculture Management System is a web-based application designed to help manage agricultural activities efficiently. The system supports secure user authentication, data management, and monitoring of agricultural operations such as farmer records, crops, and production data.

It is built using PHP for backend processing, JavaScript for frontend interactions, and MySQL for data storage.

🚀 Features

Secure user registration and login

Password protection using hashing

Role-based access (Admin / User)

Manage agricultural data (e.g., crops, farmers, production)

Input validation on both frontend and backend

Responsive and user-friendly interface

🛠️ Technologies Used

Frontend: HTML, CSS, JavaScript

Backend: PHP

Database: MySQL

Security:

Password hashing (password_hash, password_verify)

Prepared SQL statements

Input validation

🔐 Security Features

Passwords are never stored in plain text

Strong password rules:

At least 8 characters

At least one uppercase letter

At least one number

At least one special character

Protection against SQL Injection using prepared statements

HTTPS recommended for deployment

📂 Project Structure
agriculture-system/
│
├── config/
│   └── database.php
│
├── auth/
│   ├── signup.php
│   ├── login.php
│   └── logout.php
│
├── dashboard/
│   └── index.php
│
├── assets/
│   ├── css/
│   └── js/
│
├── index.php
└── README.md

⚙️ Installation & Setup

Install XAMPP / WAMP / MAMP

Clone or download the project into the htdocs folder

Create a MySQL database (e.g., agriculture_db)

Import the provided SQL file into the database

Update database credentials in:

config/database.php


Start Apache and MySQL

Access the system via:

http://localhost/agriculture-system

🧪 Default User Flow

New users register via the Sign-Up page

Password is validated and securely hashed

Users log in using verified credentials

Authorized users access the dashboard

📈 Future Enhancements

Two-Factor Authentication (2FA)

Mobile-friendly UI improvements

Data analytics and reporting

SMS / Email notifications

API integration for external systems

👨‍💻 Author

Brian Muthama Mwololo
