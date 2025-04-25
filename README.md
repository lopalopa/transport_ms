# transport_ms
A simple and efficient system to manage transport operations digitally.
# 🚚 Transport Management System (TMS)

A web-based PHP application for managing transportation logistics such as vehicles, drivers, routes, and users. This system provides role-based access for administrators and drivers to streamline the entire transport process from scheduling to reporting.

---

## 📌 Project Overview

The Transport Management System is designed to automate and digitize the operations of a transport organization. It allows admins to manage users, assign drivers, track vehicles, manage routes, and generate reports — all in one place.

---

## ✨ Features

- 🔐 Secure login/logout system
- 👥 User management with roles (Admin/Driver)
- 🚘 Vehicle management
- 👨‍✈️ Driver management
- 🛣️ Route management
- 📊 Reporting system
- 🧾 Clean UI with Bootstrap
- 🗂️ Session-based and role-based access

---

## 🛠️ Technologies Used

- **Frontend**: HTML, CSS, Bootstrap
- **Backend**: PHP (Core PHP)
- **Database**: MySQL
- **Server**: XAMPP (Apache + MySQL)

---

## 🚀 Getting Started

### Prerequisites

- XAMPP (or any server with PHP >= 7.4)
- MySQL
- Web browser

---

### 📥 Installation Steps

1. **Move to XAMPP `htdocs` folder**

   C:\xampp\htdocs\transport-system
Create Database

Open phpMyAdmin

Create a new database (e.g., transport_db)

Import the transport_db.sql file from the project folder

Update Database Configuration

Open includes/db.php and update the connection details:


<?php
$conn = new mysqli("localhost", "root", "", "transport_db");
?>
Start the Application

Start Apache and MySQL from XAMPP

Open your browser and visit:

http://localhost/transport-system/

👨‍💻 Usage
Admin Login
Access all features: user, vehicle, driver, and route management

Driver Login
View assigned routes and vehicles

Submit trip reports

Use default credentials or create new ones in the database (users table).

📂 Folder Structure
transport-system/
├── assets/
│   └── css, js, images
├── includes/
│   └── db.php
│   └── header.php
│   └── sidebar.php
│   └── footer.php
├── manage_users.php
├── manage_vehicles.php
├── manage_drivers.php
├── manage_routes.php
├── edit_user.php
├── edit_driver.php
├── login.php
├── logout.php
├── dashboard.php
├── view_reports.php
└── README.md
📣 Future Improvements
📩 Add SMS/Email notification system

📍 Real-time GPS tracking integration

🔧 Maintenance scheduling for vehicles

🔎 Search and pagination on listing pages

🧑‍🏫 Developed For
Educational purposes (BCA, MCA projects)

Small transport agencies looking to digitize operations

📝 License
This project is open-source and free to use for educational or non-commercial purposes.

📧 Contact
Developer: Rashmi Prava Mishra
Email: your.lopalopa2007@gmail.com.com
GitHub: lopalopa2007

