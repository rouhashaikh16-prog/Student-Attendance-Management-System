1️⃣ Project Overview

This is a console-based Java application that manages student records and tracks attendance using Object-Oriented Programming principles.
The system allows adding students, marking attendance, viewing student details, and generating attendance reports with percentage and status.

2️⃣ Technologies Used

Java
OOP (Object-Oriented Programming)
ArrayList (Java Collections Framework)
Scanner (User Input Handling)
Exception Handling

3️⃣ Core Concepts Implemented
🔹 Class & Object

Student class acts as a blueprint.
Multiple student objects are created and stored in an ArrayList.

🔹 Encapsulation

All student fields are declared private.
Data is accessed using public getter methods.
Attendance is updated only through methods (markPresent(), markAbsent()).

🔹 Constructor

Used to initialize student data.
Constructor overloading is implemented for flexibility.

🔹 ArrayList

Stores all Student objects dynamically.
Grows automatically when new students are added.

🔹 Methods

markPresent()
markAbsent()
getPercentage()
display()

4️⃣ Features

Add New Student
Show All Students
Mark Attendance
Generate Attendance Report
Exit System

5️⃣ Attendance Calculation Logic

Attendance percentage is calculated using: (presentCount / totalClasses) * 100
Typecasting to double is used to avoid integer division.

6️⃣ How to Run the Project

Save file as AttendanceSystem.java
Open terminal in project folder

Compile:
AttendanceSystem.java

Run:
java AttendanceSystem
