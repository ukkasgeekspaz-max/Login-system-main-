# 🔐 Secure Login System (PHP + MySQL + JavaScript)

A secure authentication system built using:

- HTML5
- CSS3
- JavaScript (Fetch API)
- PHP (Backend)
- MySQL (Database - MySQL Workbench)
- Sessions
- Password Hashing

---

## 🚀 Features

✅ User Login Authentication  
✅ JavaScript Form Validation  
✅ Dynamic Error Messages  
✅ Secure Password Hashing (`password_hash`)  
✅ Password Verification (`password_verify`)  
✅ SQL Injection Protection (Prepared Statements)  
✅ Session Management  
✅ Protected Dashboard  
✅ Logout Functionality  

---

## 🗂 Project Structure

login_system/
│
├── index.html # Login Page
├── db.php # Database Connection
├── register.php # Create Initial User (Run Once)
├── login.php # Login Authentication Logic
├── dashboard.php # Protected Dashboard Page
├── logout.php # Logout Script
└── README.md # Project Documentation


---

## 🛠️ Database Setup (MySQL Workbench)

Run the following SQL:

```sql
CREATE DATABASE login_system;

USE login_system;

CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    email VARCHAR(100) NOT NULL UNIQUE,
    password VARCHAR(255) NOT NULL
);
👤 Create Default User
Open in browser:

http://localhost/login_system/register.php
Default credentials:

Email: admin@gmail.com
Password: 123456
⚠ After creating the user, delete register.php for security.

▶️ How to Run the Project
Install XAMPP / WAMP

Start Apache and MySQL

Place project folder inside htdocs

Open browser:

http://localhost/login_system/
🔐 Security Implemented
Password hashing using password_hash()

Password verification using password_verify()

Prepared statements to prevent SQL Injection

Session-based authentication

Protected routes

📚 Technologies Used
Technology	Purpose
HTML	Structure
CSS	Styling
JavaScript	Client-side Validation
PHP	Backend Logic
MySQL	Database
Sessions	Authentication Management
💡 Real-Time Usage
This system can be used as:

Web application authentication system

Admin login panel

College project submission

Internship project

Placement portfolio project

🧠 Interview Concepts Covered
Authentication Flow

Session Handling

Password Hashing vs Encryption

SQL Injection Prevention

AJAX Login Request

Full Stack Integration

👨‍💻 Author
Kapil Charan
B.Tech CSE (2027)

📌 Future Improvements
User Registration Page

Forgot Password Feature

Email Verification

JWT Authentication

Role-Based Authentication (Admin/User)

Deploy to Cloud (AWS / Render / Railway)

📜 License
This project is for educational purposes
