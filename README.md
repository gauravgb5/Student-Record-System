# Student-Record-System
This is simple student management system desktop application for school project using jdbc driver and Jframe.

### Getting Started
Welcome to the VS Code Java world. Here is a guideline to help you get started to write Java code in Visual Studio Code.

### Folder Structure
The workspace contains two folders by default, where:

src: the folder to maintain sources
lib: the folder to maintain dependencies
Meanwhile, the compiled output files will be generated in the bin folder by default.

If you want to customize the folder structure, open .vscode/settings.json and update the related settings there.

### Dependency Management
The JAVA PROJECTS view allows you to manage your dependencies. More details can be found here. Certainly! Here's a basic README.md for your Student Management System project:

Certainly! Here's an updated README.md for your Student Management System project that includes the MySQL setup steps:

### Student Management System
A simple Java Swing application for managing student information. It allows you to add, delete, and search for student records.

### Features
Add student records with details such as name, ID, grade, date of birth, gender, contact, and email.
Reset form fields.
Delete student records.
Search for a student by ID.
Connects to a MySQL database to store and retrieve student data.

### Prerequisites
Before running the application, you need the following:

Java Development Kit (JDK)
MySQL Server
MySQL Connector/J library (JDBC driver)
A MySQL database named "student"
A MySQL user with the username "root" and password "user" (You can modify the database credentials in the code)


### MySQL Setup
1. Open a MySQL client (e.g., MySQL Workbench or the MySQL command-line client).

2. To list all databases, run the following command:
   
    SHOW DATABASES;

3. Create a new database named "student" if it doesn't already exist:
   
    CREATE DATABASE student;
   
4. Switch to the "student" database:

    USE student;
   
5. Verify that you're in the "student" database:

    SELECT DATABASE();

6. Create a table named "students" to store student records. The table structure should match the fields you have in your Java application (name, ID, grade, date of birth, gender, contact, and email). Here's an example table structure:

   CREATE TABLE students (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(255),
    student_id VARCHAR(255) UNIQUE,
    grade VARCHAR(255),
    date_of_birth DATE,
    gender VARCHAR(10),
    contact VARCHAR(20),
    email VARCHAR(255)

);

7. You can view the table structure with:

   DESCRIBE students;

8. Now you have the "student" database and the "students" table ready to use with your Java application.

## Installation


