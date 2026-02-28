Student Attendance Management System

-  Project Overview

The Student Attendance Management System is a console-based Java application designed to digitally manage student records and track attendance efficiently.
This project demonstrates practical implementation of core Object-Oriented Programming concepts and simulates a real-world academic attendance system using a menu-driven interface.
It is built completely in Java without any external libraries, focusing on strong programming fundamentals and clean architecture.

-  Project Objectives

It digitally manages student's data by adding or removing the data. We can track the attencdance of the students and also it can calculate the percentage of the attendance automatically. 
It also categorizes the performance of students e.g. Good, Average, Low. The main objective of this project is to make attendance management simple and digital instead of using paper records. It helps to easily add students, mark their attendance, and calculate their attendance percentage automatically. This system reduces manual work and mistakes in calculation. It also helps in practicing and improving basic Java and OOP concepts in a practical way.


-  Project Architecture

The Attendance Management System is designed as a menu-driven console program where the user interacts with different options like adding students, marking attendance, viewing records, and generating reports. The system stores student details in memory during program execution and manages them in an organized way. When the program starts, it displays a main menu and waits for the user’s choice. Based on the selected option, it performs the required task such as saving student information, updating attendance records, or calculating attendance percentage automatically. The system runs continuously in a loop until the user chooses to exit. This structure makes the program simple, user-friendly, and easy to understand while maintaining proper flow and logical control.

-  Core Concepts Implemented

This project mainly implements core Java and Object-Oriented Programming concepts in a practical way. The system uses Encapsulation by keeping student data secure and managing it through controlled access. Abstraction is applied by separating the internal data handling from user interaction. The program makes use of Collections (ArrayList) to dynamically store and manage multiple student records. Loops are used to repeatedly display the menu and allow continuous operations until the user exits. Conditional statements control the program flow based on user choices.
Additionally, basic input handling using Scanner is implemented to take user inputs from the console. The attendance percentage is calculated using a logical formula, ensuring automatic and accurate results. Overall, the project demonstrates how fundamental programming concepts work together to build a complete, functional system

-  FEATURES
Add Student        =	Adds a new student after duplicate roll number validation
Show Students      =	Displays complete student list
Mark Attendance    =	Marks Present (P) or Absent (A)
Attendance Report  =	Generates formatted report with percentage
Performance Status =	Automatically assigns Good / Average / Low
Exit System       0 =	Clean program termination

-  Attendance Calculation

The attendance percentage in this system is calculated based on the number of classes a student has attended compared to the total number of classes conducted.
                                               AttendancePercentage=(PresentClasses/TotalClasses)×100

Each time attendance is marked, the total class count increases, and if the student is present, the present count also increases. The system then automatically calculates the percentage using this formula and displays it in the attendance report. This automatic calculation reduces manual errors and ensures accurate results.
To prevent: Integer division errors, Division by zero

-  Future Enhancements
File handling for permanent storage
Database integration (MySQL)
GUI implementation using Java Swing / JavaFX
Role-based login system (Admin / Teacher)
