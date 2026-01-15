# MySQL Student Database Project

## 📌 Project Overview
This project demonstrates basic **MySQL database operations** using **MySQL Workbench**.  
A database was created to store student information, and common SQL operations were performed such as creating tables, inserting data, and retrieving records.

This project is suitable for **beginners**, **internship practice**, and **learning SQL fundamentals**.

---

## 🗄️ Database Details
- **Database Name:** intern_training_db
- **Table Name:** students

---

## 📋 Table Structure

### students table
| Column | Data Type | Description |
|------|----------|------------|
| id | INT (Primary Key) | Unique student ID (Auto Increment) |
| name | VARCHAR(100) | Student full name |
| email | VARCHAR(150) | Student email (Unique) |
| age | INT | Student age |

---

## ⚙️ SQL Operations Performed

### 1️⃣ Database Creation
- Created a database to store student information.

### 2️⃣ Table Creation
- Created a `students` table with appropriate data types and constraints.

### 3️⃣ Data Insertion
- Inserted multiple student records using `INSERT INTO` statements.

### 4️⃣ Data Retrieval
- Retrieved all records using:
  ```sql
  SELECT * FROM students;
