# Task-07

# Java JDBC – Employee Database App

## Objective
A Java console application that connects to a **MySQL database** using **JDBC** and performs CRUD (Create, Read, Update, Delete) operations on an Employee table.

## Features
- Add new employees to the database
- View all employees
- Update employee salary
- Delete employees by ID
- Uses `Connection`, `PreparedStatement`, and `ResultSet`

## Technologies Used
- Java
- MySQL
- JDBC Driver (MySQL Connector/J)
- VS Code

## Database Setup
1. Open MySQL and run:
   ```sql
   CREATE DATABASE testdb;
   USE testdb;
   CREATE TABLE employees (
       id INT AUTO_INCREMENT PRIMARY KEY,
       name VARCHAR(100),
       salary DOUBLE
   );
