# Student-Registration-System

# Student Registration System

The **Student Registration System** is a desktop application developed using **Python**, **Tkinter**, and **MySQL**. It provides an intuitive GUI to manage student registrations, allowing users to add, update, view, and delete student records efficiently.

## 🚀 Features
- **Add New Student:** Register students with their name, course, and fee details.
- **Update Records:** Modify existing student information with ease.
- **Delete Records:** Remove student data from the system.
- **View All Students:** Display all registered students in a clean, tabular format using Tkinter's Treeview.
- **Interactive UI:** User-friendly interface with real-time data updates.

## 🛠️ Technologies Used
- **Python**: Programming language for application logic.
- **Tkinter**: GUI toolkit for building the interface.
- **MySQL**: Database for storing student records.

## 💾 Database Setup
1. Install MySQL and create a database:
   ```sql
   CREATE DATABASE webgui;
   USE webgui;
   CREATE TABLE registration (
       id INT AUTO_INCREMENT PRIMARY KEY,
       name VARCHAR(255),
       course VARCHAR(255),
       fee DECIMAL(10, 2)
   );
