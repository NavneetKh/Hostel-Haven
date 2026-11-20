# 🏠 Hostel Haven – Hostel Management System

A modern, responsive, full-stack **Hostel Management System** developed using PHP, MySQL, HTML, CSS, and JavaScript. Hostel Haven simplifies hostel administration by providing a centralized platform for managing students, rooms, fees, complaints, attendance, and daily hostel operations.

## 🚀 Features

- **User Authentication:** Secure registration, login, logout, and role-based access.
- **Admin Dashboard:** Hostel statistics, occupancy analytics, and activity monitoring.
- **Room Management:** Room allocation, availability tracking, and occupancy management.
- **Student Management:** Student profiles, academic records, and accommodation details.
- **Fee Management:** Payment records, outstanding balances, and fee tracking.
- **Complaint Management:** Complaint submission, status updates, and resolution tracking.
- **Mess Management:** Weekly meal schedules and menu management.
- **Attendance & Leave:** Student attendance records and leave applications.
- **Visitor Management:** Visitor registration and check-in/check-out records.
- **Staff Management:** Staff profiles and assigned responsibilities.
- **Notifications:** Hostel announcements and important updates.

## 🛠️ Technology Stack

| Component | Technology |
|---|---|
| Frontend | HTML5, CSS3, JavaScript |
| Backend | PHP |
| Database | MySQL / MariaDB |
| Server | Apache (XAMPP) |
| Database Tool | phpMyAdmin |
| Development Environment | Visual Studio Code |

## 📂 Project Structure

```text
hostel_haven/
├── index.php
├── app/
├── assets/
├── config/
├── database/
│   └── hostel_haven.sql
├── views/
└── README.md
```

## ⚙️ Installation and Setup

### 1. Install XAMPP

Download and install XAMPP from:

https://www.apachefriends.org/

### 2. Start the Servers

Open the XAMPP Control Panel and start:

- Apache
- MySQL

### 3. Set Up the Project

Extract the project folder into:

```text
C:\xampp\htdocs\hostel_haven
```

### 4. Create the Database

Open phpMyAdmin:

http://localhost/phpmyadmin

Create a database named:

```sql
CREATE DATABASE hostel_haven;
```

### 5. Import SQL File

1. Select the `hostel_haven` database.
2. Click **Import**.
3. Choose `database/hostel_haven.sql`.
4. Click **Import** to create the required tables.

### 6. Run the Website

Open your browser and visit:

http://localhost/hostel_haven/

Register an account or log in using an account configured in the database.

## 👥 User Roles

**Admin:** Manages students, rooms, applications, fees, complaints, and hostel operations.

**Student:** Views accommodation details, submits complaints, checks fees, and accesses hostel services.

**Warden:** Supervises students, attendance, leave requests, and hostel activities.

**Staff:** Handles assigned responsibilities and maintenance-related tasks.

## 🎯 Project Objectives

- Digitize hostel administration.
- Reduce paperwork and manual errors.
- Simplify room allocation and student management.
- Improve record accuracy and accessibility.
- Provide an organized and user-friendly management platform.

## 🔐 Security

- Password hashing
- PHP session-based authentication
- Role-based access control
- Prepared SQL statements
- Server-side input validation

## 🔮 Future Enhancements

- Online payment gateway integration
- Email and SMS notifications
- QR-based attendance
- Mobile application
- Advanced analytics and reporting

## 📜 License

No open-source license has been assigned yet. An MIT License may be added if the project owners choose to release it under those terms.

---

**Hostel Haven – Making Hostel Management Smarter, Simpler, and More Efficient.**
