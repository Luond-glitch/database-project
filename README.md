# Clinic Booking System – MySQL Database Project

## 📌 Project Description

This is a complete database schema for a **Clinic Booking System**, built entirely in MySQL. It supports managing departments, doctors, patients, appointments, and system users (e.g., admins or staff). The project is designed to simulate real-world clinic operations such as booking and tracking appointments.

## 🎯 Objectives

- Create a relational database from scratch using MySQL
- Enforce referential integrity through proper constraints
- Design normalized tables with meaningful relationships

## 🛠️ Technologies Used

- MySQL (SQL syntax)
-ERD

## 🚀 How to Run This Project

1. Clone this repository
2. Open your MySQL client (e.g., MySQL Workbench or phpMyAdmin)
3. Run the provided `clinical.sql` file
4. You will have a complete set of tables ready for use



## 📂 Files Included

- `clinical.sql` – Complete schema with comments
- `README.md` – This documentation

## 👨‍⚕️ Entities & Relationships Overview

- **Department**: Each department can have multiple doctors (1-to-Many)
- **Doctor**: Each doctor can handle many appointments (1-to-Many)
- **Patient**: Each patient can book multiple appointments (1-to-Many)
- **Appointment**: Represents booking info, linked to both doctor and patient
- **User**: Staff/admin accounts for system access

---

✅ *Final Submission for Question 1 – MySQL Only DBMS Project*
