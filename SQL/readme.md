# Student Database SQL Analysis

## 📌 Project Overview

This project demonstrates basic SQL operations and data analysis using **PostgreSQL**.

The project uses a student database containing student IDs, names, departments, and marks. SQL queries are used to insert, update, retrieve, sort, and analyze student data.

The main purpose of this project is to practice SQL concepts that are commonly used by **Data Analysts**.

---

## 🛠️ Tools & Technologies

* PostgreSQL
* pgAdmin 4
* SQL

---

## 📊 Database Structure

### Student Table

| Column       | Data Type   | Description                     |
| ------------ | ----------- | ------------------------------- |
| `stud_id`    | INTEGER     | Unique student ID / Primary Key |
| `stud_name`  | VARCHAR(10) | Student name                    |
| `department` | VARCHAR(20) | Student department              |
| `marks`      | INTEGER     | Student marks                   |

---

## 👨‍🎓 Sample Student Data

| Student ID | Name     | Department       | Marks |
| ---------: | -------- | ---------------- | ----: |
|        101 | Manasa   | Data science     |    30 |
|        102 | Sunil    | Computer science |    50 |
|        103 | Padmaja  | EEE              |    60 |
|        104 | Lilly    | Fashion design   |    40 |
|        105 | Gheetika | CSE(AI)          |    60 |
|        106 | Sruthi   | CSc              |    50 |
|        107 | Manisha  | EEE              |    50 |
|        108 | Lasya    | EcE              |    55 |
|        109 | Janani   | System design    |    30 |
|        110 | Nissi    | CSE(AI)          |  NULL |

---

## 🔹 SQL Concepts Covered

### 1. CREATE TABLE

Created a student table with:

* Primary Key
* Integer columns
* VARCHAR columns
* Marks column

Example:

```sql
CREATE TABLE student (
    stud_id INTEGER PRIMARY KEY,
    stud_name VARCHAR(10) NOT NULL,
    department VARCHAR(20)
);
```

---

### 2. INSERT

Inserted multiple student records into the table.

```sql
INSERT INTO student
(stud_id, stud_name, department)
VALUES
(101, 'Manasa', 'CSE'),
(102, 'Sunil', 'Data science'),
(103, 'Padmaja', 'EEE');
```

Additional student records were also inserted later.

---

### 3. UPDATE

Updated department information for specific students.

Example:

```sql
UPDATE student
SET department = 'Data science'
WHERE stud_name = 'Manasa';
```

Another example:

```sql
UPDATE student
SET department = 'computer science'
WHERE stud_name = 'Sunil';
```

---

### 4. ALTER TABLE

Added a new `marks` column to the existing table.

```sql
ALTER TABLE student
ADD COLUMN marks INTEGER;
```

---

### 5. UPDATE Marks

Updated marks for a particular student.

```sql
UPDATE student
SET marks = 55
WHERE stud_id = 108;
```

---

### 6. SELECT

Retrieved student records using:

```sql
SELECT *
FROM student;
```

---

### 7. ORDER BY

Sorted student records by student ID.

```sql
SELECT *
FROM student
ORDER BY stud_id;
```

---

# 📈 Aggregate Functions

The project also demonstrates SQL aggregate functions.

## COUNT()

Counts the number of rows.

```sql
SELECT COUNT(*) AS total_students
FROM student;
```

---

## SUM()

Calculates the total marks.

```sql
SELECT SUM(marks) AS total_marks
FROM student;
```

---

## AVG()

Calculates the average marks.

```sql
SELECT AVG(marks) AS average_marks
FROM student;
```

---

## MAX()

Finds the highest marks.

```sql
SELECT MAX(marks) AS maximum_marks
FROM student;
```

---

## MIN()

Finds the lowest marks.

```sql
SELECT MIN(marks) AS minimum_marks
FROM student;
```

---

# 📊 GROUP BY Analysis

The project also performs department-wise analysis.

### Student Count by Department

```sql
SELECT
    department,
    COUNT(*) AS total
FROM student
GROUP BY department;
```

### Total Marks by Department

```sql
SELECT
    department,
    SUM(marks) AS total_marks
FROM student
GROUP BY department;
```

### Average Marks by Department

```sql
SELECT
    department,
    AVG(marks) AS average_marks
FROM student
GROUP BY department;
```

### Maximum Marks by Department

```sql
SELECT
    department,
    MAX(marks) AS maximum_marks
FROM student
GROUP BY department;
```

### Minimum Marks by Department

```sql
SELECT
    department,
    MIN(marks) AS minimum_marks
FROM student
GROUP BY department;
```

---

# 🎯 Key Learning Outcomes

Through this project, I practiced:

* Creating SQL tables
* Defining primary keys
* Inserting records
* Updating records
* Altering table structure
* Retrieving data using `SELECT`
* Sorting data using `ORDER BY`
* Using aggregate functions
* Using `GROUP BY`
* Performing department-wise analysis
* Working with NULL values
* Performing basic data analysis using SQL

---

# 📂 Project Structure

```text
student-sql-analysis/
│
├── student_queries.sql
├── README.md
└── screenshots/
    ├── student_table.png
    └── agg_group_having.png
```

---

# 🚀 Future Improvements

The project can be extended with:

* `WHERE`
* `HAVING`
* `JOIN`
* Subqueries
* CTEs
* Window Functions
* Student performance analysis
* Department ranking
* Top-performing students
* Data visualization

---

## 👨‍💻 Author

**Manasa polisetty**

Aspiring Data Analyst | SQL | Excel | Python | Data Science

---

## ⭐ Conclusion

This project demonstrates the fundamentals of SQL and provides practical experience in retrieving, modifying, and analyzing structured student data using PostgreSQL.

