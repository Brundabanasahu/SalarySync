# 💼 SalarySync - Employee Salary & Attendance Management System

A full-stack web application built to manage employees, attendance records, and salary payments efficiently.

### 📌 Tech Stack

| Layer       | Technology Used |
|------------|----------------|
| Frontend   | HTML, CSS, Bootstrap |
| Backend    | PHP (Core PHP + Server-side scripting) |
| Database   | MySQL / phpMyAdmin |
| Server     | Apache (XAMPP / WAMP) |

---

## 📝 Overview

**SalarySync** is a complete **Employee Salary and Attendance Management System**.  
The application allows the admin to perform CRUD operations on employees, track attendance, pay salaries, manage feedback, and more.  

This project demonstrates:
- User authentication (Admin & Employee roles)
- CRUD operations
- Database connectivity using PHP & MySQL
- Secure login flow
- Form validations
- Responsive UI with Bootstrap

---

## ✨ Features

- Admin Login & Employee Login Panels
- Add, View, Edit, and Delete Employee Records
- Attendance Management System
- Salary Calculation and Payment Tracking
- Employee Dashboard to view salary & attendance status
- Contact & Feedback System
- Fully responsive UI design

---

## 🗂️ Project Structure
SalarySync/
├─ index.php # Home / Login Page
├─ admin_login.php # Admin Login Page
├─ emp_login.php # Employee Login Page
├─ employee.php # Employee Management
├─ manage_attendance.php # Attendance Control
├─ pay_salary.php # Salary Payment Page
├─ view_employees.php # Show Employees
├─ view_feedback.php # User Feedback Records
├─ db.php # Database Connection File
├─ assets/
│ ├─ css/ # Stylesheets
│ ├─ img/ # UI Images & Logo
│ └─ js/ # Optional JS files
└─ database/
└─ salarysync.sql # Database Export File


---

## 🛢️ Database Setup

1. Start **XAMPP / WAMP** and enable **Apache** & **MySQL**
2. Go to:

3. Create a new database:

4. Click **Import**
5. Select `salarysync.sql` from the project folder
6. Click **GO**

---

## ⚙️ Configure Database Connection

Open `db.php` and confirm:


$host = "localhost";
$user = "root";
$pass = "";
$db   = "salarysync";

$conn = mysqli_connect($host, $user, $pass, $db);

if(!$conn){
 die("Database Connection Failed: " . mysqli_connect_error());
}


Run Instructions

Move project folder to:

C:\xampp\htdocs\


Start Apache & MySQL from XAMPP

Open browser and visit:

http://localhost/SalarySync/
