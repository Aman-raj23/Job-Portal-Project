# 🧑‍💼 Job Portal System

A complete PHP & MySQL based Job Portal application that allows **job seekers** to find and apply for jobs, and **employers** to post and manage vacancies.

---

## 🚀 Features

- 👨‍💼 Employer login, job posting, and management  
- 🧑‍🎓 Job seeker registration, login, and job applications  
- 🔍 Job search with filters  
- 📄 Resume upload for applicants  
- 📢 Dynamic dashboard for both roles  
- 🔐 Secure login system (hashed passwords)  

---

## 📂 Project Structure

```
Job_Portal/
│
├── Jb_system/ # Main PHP application
├── Jb_database/ # Database dump (.sql)
├── assets/ # CSS, JS, images
├── uploads/ # User-uploaded resumes & images
├── index.php # Home page
├── README.md # Project guide
└── .gitignore
```


---

## 🛠️ Requirements

- **XAMPP** (or WAMP/MAMP/LAMP)
- PHP 7.4+  
- MySQL 5.7+  
- Web browser

---

## ⚙️ Setup Instructions

1. **Install XAMPP**  
   - Download from [https://www.apachefriends.org/download.html](https://www.apachefriends.org/download.html)  
   - Install and start **Apache** & **MySQL** from XAMPP Control Panel.

2. **Copy Project to htdocs**  
   - Extract this project and place the folder into:
     ```
     C:\xampp\htdocs\
     ```
   - Example:
     ```
     C:\xampp\htdocs\Job_Portal
     ```

3. **Import Database**  
   - Open **phpMyAdmin** by visiting:  
     [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
   - Create a new database (example name: `job_portal_db`).
   - Import the SQL file:
     ```
     Jb_database/job_portal.sql
     ```

4. **Update Database Connection**  
   - Open `Jb_system/config.php` (or equivalent DB config file).  
   - Update credentials:
     ```php
     $servername = "localhost";
     $username   = "root";
     $password   = "";
     $dbname     = "job_portal_db";
     ```

5. **Run the Project**  
   - Visit:
     ```
     http://localhost/Job_Portal
     ```
<!--
---
 
## 🖼️ Screenshots

### Home Page
![Home Page Screenshot](screenshots/home.png)

### Job Listings
![Job Listings Screenshot](screenshots/jobs.png)
You can viwe the listed job here
-->
---

## 📌 Notes

- Default admin credentials (change after first login):
  - **Username:** admin  
  - **Password:** admin123
- Uploaded resumes/images are stored in `/uploads/` folder.

---

## 👤 Credits

Developed with ❤️ by **Raj**

---

## 📜 License

This project is open-source and free to use for learning & development purposes.

