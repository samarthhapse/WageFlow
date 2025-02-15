🚀 Employee Payroll System in Java

Welcome to the Employee Payroll System project! This repository showcases a well-structured, terminal-based payroll management system built using Java and follows Object-Oriented Programming (OOP) principles.

📌 Overview

This project demonstrates how to implement an Employee Payroll System with a strong focus on OOP concepts such as abstraction, inheritance, encapsulation, and polymorphism. It enables organizations to manage employee payroll efficiently, supporting full-time and part-time employees with automated salary calculations.

🔍 Project Highlights

Abstract Employee Class: Serves as the base class for different employee types.

FullTimeEmployee & PartTimeEmployee Subclasses: Extend the base class to implement salary calculations.

JDBC & MySQL Integration: Stores employee data in a database and retrieves it efficiently.

User-Friendly Terminal Interface: Provides an easy-to-use CLI for managing payroll details.

Encapsulation & Data Security: Private attributes with proper getter and setter methods.

Polymorphism in Action: Overridden methods for salary calculation based on employee type.

🏗️ Project Structure

📂 Employee-Payroll-System
 ├── 📁 src
 │   ├── 📄 Employee.java  # Abstract Employee class
 │   ├── 📄 FullTimeEmployee.java  # Class for full-time employees
 │   ├── 📄 PartTimeEmployee.java  # Class for part-time employees
 │   ├── 📄 PayrollManager.java  # Handles employee data and calculations
 │   ├── 📄 DatabaseHandler.java  # Manages database connections via JDBC
 │   └── 📄 Main.java  # Entry point of the application
 ├── 📂 sql
 │   ├── 📄 database.sql  # SQL script to create tables
 ├── 📄 README.md  # Project documentation
 ├── 📄 .gitignore  # Git ignore file
 └── 📄 LICENSE  # License file

🛠️ Tech Stack

Programming Language: Java (JDK 8+)

Database: MySQL

Database Connectivity: JDBC (Java Database Connectivity)

OOP Concepts: Encapsulation, Inheritance, Abstraction, Polymorphism

Development Tools: IntelliJ IDEA / Eclipse

Version Control: Git & GitHub

⚙️ Setup Instructions

Prerequisites

Install Java JDK 8+

Install MySQL and set up a database

Install IntelliJ IDEA / Eclipse for development

Steps to Run the Project

Clone the repository:

git clone https://github.com/your-username/Employee-Payroll-System.git

Import the project into IntelliJ IDEA or Eclipse.

Configure MySQL database by running the SQL script provided in the sql folder.

Update database credentials in DatabaseHandler.java.

Compile and run the Main.java file.

📁 Repository Contents

Source Code: Java implementation of the Employee Payroll System.

Database Script: SQL queries to create necessary tables.

README: Detailed project documentation and setup instructions.