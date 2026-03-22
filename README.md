# Student Management System

## Description
A Java-based student management system with MySQL database backend, command-line interface, and JavaFX desktop GUI for managing students, courses, and course enrollments.

---

## About This Project

This project was created to further develop and enhance my Java programming skills, particularly in:
- Object-Oriented Programming (OOP) principles and design patterns
- Database design and JDBC integration
- Building both console and GUI applications
- Implementing the DAO (Data Access Object) pattern
- Working with MySQL for persistent data storage
- JavaFX for modern desktop applications

---

## Features

✨ **User Interfaces:**
- Console-based menu system (MainDriver.java)
- JavaFX desktop application (StudentManagementGUI.java)


📚 **Core Functionality:**
- **Student Management** - Add, view, update, and delete student records
- **Course Management** - Add, view, update, and delete course information
- **Enrollment Management** - Enroll students in courses, manage grades, track enrollments

🔧 **Technology Stack:**
- **Language:** Java
- **Database:** MySQL
- **GUI Framework:** JavaFX
- **JDBC Driver:** MySQL Connector/J 9.6.0

---

## Project Structure

```
01-Student_DBMS/
├── Core Classes
│   ├── DBConnection.java
│   ├── Student.java
│   ├── Course.java
│   └── Enrollment.java
│
├── DAO Layer
│   ├── StudentDAO.java
│   ├── CourseDAO.java
│   └── EnrollmentDAO.java
│
├── User Interfaces
│   ├── MainDriver.java                (Console menu)
│   └── StudentManagementGUI.java      (JavaFX GUI)
│
├── Database
│   └── student_management.sql
│
└── Dependencies
    └── mysql-connector-j-9.6.0.jar
```


## Getting Started

1. Set up MySQL database: `mysql -u root -p < student_management.sql`
2. Update credentials in `DBConnection.java`
3. Compile: `javac --module-path "C:\javafx-sdk-26\lib" --add-modules javafx.controls -cp "mysql-connector-j-9.6.0.jar" *.java`
4. Run: `java --module-path "C:\javafx-sdk-26\lib" --add-modules javafx.controls -cp ".;mysql-connector-j-9.6.0.jar" StudentManagementGUI`

