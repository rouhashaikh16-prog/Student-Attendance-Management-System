📘 Student Attendance Management System

📌 Project Overview

The Student Attendance Management System is a console-based Java application designed to digitally manage student records and track attendance efficiently.
This project demonstrates practical implementation of core Object-Oriented Programming concepts and simulates a real-world academic attendance system using a menu-driven interface.
It is built completely in Java without any external libraries, focusing on strong programming fundamentals and clean architecture.

🎯 Project Objectives

Digitally manage student data
Implement attendance tracking system
Calculate percentage automatically
Categorize performance status (Good / Average / Low)
Demonstrate OOP concepts clearly for interview preparation

🏗 Project Architecture

The project consists of:

🔹 1. Student Class
Acts as a data model (Blueprint)
Attributes:
rollNo
name
division
totalClasses
presentCount

Methods:
markPresent()
markAbsent()
getPercentage()
display()
getter methods

🔹 2. AttendanceSystem Class

Acts as the controller (Main class)
Manages ArrayList<Student>
Contains menu logic
Handles user input
Controls program flow

⚙ Core Concepts Implemented
✅ Object-Oriented Programming
Class and Object creation
Encapsulation
Constructor overloading
Method abstraction

✅ Collections Framework
Dynamic storage using ArrayList
For-each loop iteration

✅ Exception Handling
Handles invalid numeric input using try-catch

FEATURES=
Add Student       =	Adds a new student after duplicate roll number validation
Show Students     =	Displays complete student list
Mark Attendance   =	Marks Present (P) or Absent (A)
Attendance Report =	Generates formatted report with percentage
Performance Status=	Automatically assigns Good / Average / Low
Exit System       =	Clean program termination

📊 Attendance Calculation

The attendance percentage is calculated using: (double) presentCount / totalClasses * 100
To prevent:
Integer division errors, Division by zero

🔮 Future Enhancements
File handling for permanent storage
Database integration (MySQL)
GUI implementation using Java Swing / JavaFX
Role-based login system (Admin / Teacher)
