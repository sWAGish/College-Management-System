# 🎓 College Management System

A simple and effective College Management System built using **HTML**, **CSS**, **PHP**, and **MySQL**. This project is designed to streamline various administrative operations such as student record management, course registration, department management, and more. It provides a web-based interface for admin, faculty, and students.

---

## 📌 Features

- 🧑‍🎓 Student Management (Add, Edit, Delete, View)
- 🧑‍🏫 Faculty & Department Management
- 📚 Course Enrollment
- 📝 Attendance Tracking (Basic)
- 💳 Fees Record (Optional Module)
- 🔐 Admin Login & Session Management
- 📋 Responsive User Interfaces using HTML & CSS
- 🗃️ Data stored in MySQL database

---

## 💻 Technologies Used

| Technology | Purpose              |
|------------|----------------------|
| HTML/CSS   | Front-end UI Design  |
| PHP        | Backend Development  |
| MySQL      | Database Management  |

---

## 🛠 Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sWAGish/College-Management-System.git
   cd College-Management-System


2. Import the database:

Open phpMyAdmin or your preferred MySQL client.

Create a database (e.g., college_db).

Import the college.sql file from the project directory.

3. Configure Database:

Open config.php or similar config file.

Set your database credentials:     
$host = "localhost";
$user = "root";
$pass = "";
$db   = "college_db";

4. Run the project:

Use a local server like XAMPP or MAMP.

Place project files in htdocs (XAMPP) or www (MAMP).

Visit: http://localhost/College-Management-System/

📂 Project Structure
College-Management-System/

├── config/
│   └── config.php
├── admin/
│   └── dashboard.php
├── student/
│   └── profile.php
├── faculty/
│   └── attendance.php
├── assets/
│   └── styles.css
├── college.sql
└── index.php
