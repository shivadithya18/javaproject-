# javaproject-
java lab project 
Hospital Management System
Project Title
Hospital Management System - Java JDBC Application

Project Description
This Java Hospital Management System is a complete project that demonstrates a real-time healthcare management use case. It supports patient registration, doctor appointment booking, billing generation, and medical record storage. The project uses JDBC for database connectivity, collections for data assembly, and a simple Swing GUI interface as well as a console-based menu.

Features
Patient registration
View registered patients
Doctor appointment booking
Automatic database initialization for doctor records
Medical record insertion and retrieval
Billing invoice generation and bill history view
Console and GUI run modes
Concepts Demonstrated
Inheritance: Person, PatientEntity, DoctorEntity
Collections: List, ArrayList, BillItem collection
JDBC: MySQL connectivity, CRUD operations, prepared statements
GUI: Swing interface in HospitalManagementGUI
Software Requirements
Java JDK 11 or later
MySQL Server
MySQL JDBC driver (mysql-connector-java) on the classpath
A database named hospital
Database Setup
The project automatically creates the required tables if they are missing:

patients
doctors
appointments
medical_records
bills
bill_items
The application also seeds sample doctor data during the first run.

Steps to Run the Project
Install MySQL and create a database named hospital.

Update the database credentials in src/HospitalManagementSystem/HospitalManagementSystem.java if needed.

Compile the project using your Java compiler and the MySQL connector jar:

javac -cp ".;path\\to\\mysql-connector-java.jar" src\\HospitalManagementSystem\\*.java
Run the console application:
java -cp ".;path\\to\\mysql-connector-java.jar;src" HospitalManagementSystem.HospitalManagementSystem
Run the Swing GUI version:
java -cp ".;path\\to\\mysql-connector-java.jar;src" HospitalManagementSystem.HospitalManagementSystem gui
Notes
Make sure the MySQL server is running before starting the application.
If you use a different database name, update the JDBC URL in HospitalManagementSystem.java.
The project runs as a package under HospitalManagementSystem.
