Catering Management System

Overview

The Catering Management System is a web-based platform built using PHP, MySQL, HTML, and CSS that allows users to book catering services in advance. The system ensures smooth event planning by enforcing a minimum 3-day reservation policy to help caterers manage their schedules efficiently.

Features

✅ User-friendly interface for easy reservation booking
✅ Secure MySQL database for managing user and booking data
✅ Automated validation to ensure bookings are made at least 3 days in advance
✅ Responsive design for seamless access on different devices
✅ Admin panel to manage bookings and services

Tech Stack

Frontend: HTML, CSS

Backend: PHP

Database: MySQL


Installation & Setup

Prerequisites

Ensure you have the following installed:

XAMPP or any Apache server with PHP and MySQL

A web browser


Steps to Run the Project

1. Clone the Repository:

git clone https://github.com/your-username/catering-management.git
cd catering-management


2. Move the project to your server directory:

If using XAMPP, place it inside htdocs/



3. Import the Database:

Open phpMyAdmin

Create a new database (e.g., catering_db)

Import the provided SQL file (catering_db.sql)



4. Update Database Configuration:

Open config.php (or relevant database config file)

Modify the database credentials:

$host = "localhost";
$user = "root";
$password = "";
$database = "catering_db";



5. Run the Project:

Start Apache and MySQL in XAMPP

Open your browser and visit:

http://localhost/catering-management/




Usage

1. Users:

Register/Login

Select event date & catering services

Book reservation (only if the event is at least 3 days ahead)



2. Admin:

Manage bookings

Approve/reject reservations

Update services




Future Enhancements

🔹 Payment gateway integration
🔹 Email notifications for booking confirmation
🔹 Enhanced admin dashboard

Contributing

Pull requests are welcome! Feel free to open an issue for any suggestions or bugs.

License

This project is open-source and available under the MIT License.


---

You can customize this based on your project details. Let me know if you need any changes!

