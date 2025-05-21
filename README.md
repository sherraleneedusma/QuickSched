# QuickSched: Appointment Scheduling Management System

## Overview
**QuickSched** is an appointment scheduling management system designed to digitize manual scheduling processes and improve digital healthcare access, particularly in underserved communities.

---

## Features

- **User Authentication**: Secure login access for administrators, doctors, and patients with role-based permissions.  
- **Appointment Booking**: Patients can easily schedule appointments with doctors through a simple online interface.  
- **Automated Reminders**: Sends email notifications to remind patients of upcoming appointments to reduce no-shows.  
- **Medical Notes Management**: Doctors can view and update patient notes tied to specific appointments.  
- **Smart Scheduling System**: Prevents scheduling conflicts and double bookings with real-time availability checks.  
- **Admin Dashboard**: Manage users, view schedules, and oversee system operations in a centralized control panel.  
- **Database Integration**: Stores all user, appointment, and medical data in a normalized MySQL database for efficient and accurate data retrieval.  
- **Responsive Web Design**: Accessible on various devices, offering a consistent and user-friendly experience.  
- **Improved Healthcare Access**: Tailored for rural and small hospitals to reduce travel burdens and enhance healthcare availability.

---

## Technology Stack

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: PHP  
- **Database**: MySQL  

---

## Installation Requirements

- [XAMPP](https://www.apachefriends.org/) (or any alternative with Apache, MySQL, and PHP support)  
- Modern Web Browser  

---

## System Installation / Setup

1. Open your **XAMPP Control Panel** and start **Apache** and **MySQL**.
2. Extract the downloaded source code `.zip` file.
3. Copy the extracted folder and paste it into the `htdocs` directory inside your XAMPP installation.
4. Open a browser and go to [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
5. Create a new database named `quicksched_db`.
6. Import the provided SQL file (`quicksched_db.sql`) located at the root of the project directory.
7. Access the system via the following URLs:
   - **Patient-side**: [http://localhost/QuickSched/index](http://localhost/QuickSched/index)
   - **Doctor-side**: [http://localhost/QuickSched/index-doctor](http://localhost/QuickSched/index-doctor)
   - **Admin-side**: [http://localhost/QuickSched/index-admin](http://localhost/QuickSched/index-admin)

---

## User Access Credentials

| Role    | Email              | Password     |
|---------|--------------------|--------------|
| User    | user@gmail.com     | User123      |
| Doctor  | doctor@gmail.com   | Doctor123    |
| Admin   | admin@gmail.com    | Admin123     |

---

## Developers

- **Jaykerd Sario**  
- **Sherralene Edusma**  
- **Jorry Gumera**

---

> © 2025 QuickSched Project. All rights reserved.
