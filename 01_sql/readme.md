# 📊 SQL Basics - Day 6

## 📌 Project Overview

This project demonstrates the fundamentals of SQL using PostgreSQL.

It covers the creation of a database, creating tables, inserting records, updating data, and retrieving records using SQL queries.

This project is part of my **90-Day Data Analyst Placement Bootcamp**.

---

# 🎯 Learning Objectives

- Understand SQL fundamentals
- Create databases
- Create tables
- Insert records
- Update records
- Retrieve records
- Learn PostgreSQL Query Tool

---

# 🗂 Database

Database Name

```
data_analyst_db
```

---

# 📋 Table Structure

Table Name

```
student
```

| Column | Data Type |
|----------|-----------|
| stud_id | INTEGER |
| stud_name | VARCHAR |
| department | VARCHAR |

---

# 🛠 SQL Commands Used

## CREATE TABLE

```sql
CREATE TABLE student(
    stud_id INTEGER PRIMARY KEY,
    stud_name VARCHAR(50) NOT NULL,
    department VARCHAR(50)
);
```

---

## INSERT

Inserted multiple student records.

Example

```sql
INSERT INTO student
VALUES
(101,'Manasa','CSE'),
(102,'Sunil','Data Science');
```

---

## UPDATE

Updated department names using WHERE condition.

Example

```sql
UPDATE student
SET department='Computer Science'
WHERE stud_name='Sunil';
```

---

## SELECT

Retrieved all records.

```sql
SELECT * FROM student;
```

---

# 📷 Project Screenshot

```
06_SQL_Basics/
│
├── sql_basic.png
├── Day6_Queries.sql
└── README.md
```

---

# 📚 Concepts Learned

- Database
- Table
- Primary Key
- NOT NULL
- CREATE TABLE
- INSERT
- UPDATE
- SELECT
- WHERE Clause

---

# 💼 Business Applications

These SQL operations are commonly used in:

- Employee Management Systems
- Student Management Systems
- Hospital Databases
- Banking Applications
- E-Commerce Platforms

---

# 🧠 Skills Gained

- PostgreSQL
- SQL Syntax
- Table Creation
- Data Manipulation
- Data Retrieval
- Query Execution
- Database Fundamentals

---

# 🚀 Future Learning

Next topics in the SQL module:

- SELECT
- WHERE
- ORDER BY
- LIMIT
- DISTINCT
- Aggregate Functions
- GROUP BY
- HAVING
- JOINS

---

# 👨‍💻 Author

**Manasa polisetty**

GitHub

https://github.com/Manasapolisetty

---

⭐ This project is part of my journey toward becoming a Data Analyst by building hands-on SQL projects and maintaining a professional GitHub portfolio.
