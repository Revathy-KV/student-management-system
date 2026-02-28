Student Management System (Flask)
📌 Project Overview

The Student Management System is a web-based application developed using Python Flask that enables efficient management of student records.
This project implements CRUD operations (Create, Read, Update, Delete) through a simple and user-friendly web interface.

The application is designed for educational purposes, helping beginners understand how Flask works with HTML templates and a database (MongoDB) to build dynamic web applications.
---

🎯 Objectives

To understand Flask routing and template rendering

To perform CRUD operations using a web interface

To integrate Flask with MongoDB

To build a structured and maintainable web application
---
✨ Features

➕ Add new student records

✏️ Edit existing student details

❌ Delete student records

📋 View all students in a tabular format

🌐 Simple and clean user interface
---

🛠️ Technologies Used

Python – Backend logic

Flask – Web framework

MongoDB – Database for storing student records

HTML – Frontend structure

Jinja2 – Template engine for dynamic content
---

📂 Project Structure
student-management-system/
│
├── app.py
├── README.md
│
└── templates/
    ├── index.html
    ├── add.html
    └── edit.html
---
⚙️ How the Application Works

The home page displays all student records fetched from MongoDB.

Users can add new students using the "Add Student" form.

Existing student details can be updated using the "Edit" option.

Student records can be permanently removed using the "Delete" option.

All operations are handled through Flask routes connected to MongoDB.
---
▶️ How to Run the Project
Step 1: Install Required Packages
pip install flask pymongo
Step 2: Start MongoDB Server

Make sure MongoDB is running on your system.

mongod
Step 3: Run the Flask Application
python app.py
Step 4: Open in Browser
http://127.0.0.1:5000/
---

🚀 Future Enhancements

User authentication (login/logout)

Form validation

Search and filter functionality

Responsive UI using CSS/Bootstrap

Database migration to SQLite or MySQL
---
🎓 Learning Outcomes

Gained hands-on experience with Flask

Learned CRUD operations using MongoDB

Understood template rendering with Jinja2

Improved understanding of web application structure
---
📝 Conclusion

This project demonstrates a complete Flask CRUD application suitable for beginners and academic submissions. It provides a strong foundation for building more advanced web applications in the future
