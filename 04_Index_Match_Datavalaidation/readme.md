# 📊 Excel INDEX(), MATCH() & Data Validation Project

## 📌 Project Overview

This project demonstrates the implementation of **INDEX()**, **MATCH()**, **INDEX + MATCH**, and **Data Validation** in Microsoft Excel.

The objective is to understand how advanced lookup functions work and how they are used to retrieve employee information dynamically in real-world business scenarios.

This project is part of my **90-Day Data Analyst Placement Preparation Bootcamp**.

---

# 🎯 Learning Objectives

- Learn INDEX() function.
- Learn MATCH() function.
- Combine INDEX() and MATCH() for dynamic lookups.
- Create Data Validation drop-down lists.
- Understand real-world business applications.

---

# 📊 Dataset 1 - Employee Information

| Employee ID | Name | Department | Salary |
|------------:|------|------------|-------:|
| 101 | Sunil | HR | 35000 |
| 102 | Rahul | IT | 45000 |
| 103 | Priya | Finance | 50000 |
| 104 | Kiran | Sales | 42000 |
| 105 | Meena | Marketing | 48000 |

---

# 📊 Dataset 2 - Employee Details

| Employee ID | Name | Gender | Department |
|------------:|------|--------|------------|
| 1010 | Johnsi | Female | HR |
| 1011 | Nissi | Female | Sales |
| 1012 | Haidi | Female | IT |
| 1013 | Dora | Female | Marketing |
| 1014 | Goldi | Female | IT |
| 1015 | Sammy | Female | Finance |

---

# 🔹 INDEX()

## Purpose

Returns the value located at a specific row and column in a selected range.

### Syntax

```excel
=INDEX(array,row_num,[column_num])
```

### Practice Completed

- Retrieved Meena's salary.
- Retrieved the employee name using Employee ID 103.

### Skills Learned

- Position-based data retrieval.
- Working with single-column and multi-column ranges.

---

# 🔹 MATCH()

## Purpose

Returns the position of a value within a selected row or column.

### Syntax

```excel
=MATCH(lookup_value,lookup_array,0)
```

### Practice Completed

- Retrieved the position of Sunil.
- Retrieved the position of Employee ID 103.

### Skills Learned

- Exact Match Search.
- Finding row positions dynamically.

---

# 🔹 INDEX + MATCH

## Purpose

Combines INDEX() and MATCH() to perform flexible and dynamic lookups.

### Syntax

```excel
=INDEX(return_range,MATCH(lookup_value,lookup_range,0))
```

### Practice Completed

- Retrieved the name of Employee ID 103.
- Retrieved Kiran's salary.
- Dynamic employee lookup.

### Advantages

- More flexible than VLOOKUP.
- Supports right-to-left lookups.
- Does not depend on column numbers.
- More reliable when columns are inserted or deleted.

---

# 🔹 Data Validation

## Purpose

Restricts user input by allowing only predefined values.

### Practice Completed

Created a drop-down list for:

- Male
- Female

### Business Applications

- Gender Selection
- Department Selection
- Employee Status
- Payment Status
- Country Selection

---

# 📈 Business Applications

These functions are widely used in:

- Human Resource Management
- Payroll Systems
- Employee Databases
- Inventory Management
- Sales Dashboards
- Financial Reporting
- Business Analytics

---

# 🛠 Excel Functions Used

- INDEX()
- MATCH()
- INDEX + MATCH
- Data Validation
- Drop-down Lists

---

# 📷 Project Screenshot

Add the screenshot of your Excel workbook.

```
04_INDEX_MATCH_DataValidation/
│
├── Employee_INDEX_MATCH.xlsx
├── Screenshot.png
└── README.md
```

---

# 📚 Learning Outcomes

After completing this project, I learned to:

- Retrieve values using INDEX().
- Find positions using MATCH().
- Perform dynamic lookups with INDEX + MATCH.
- Create Data Validation drop-down lists.
- Apply advanced Excel techniques to business datasets.

---

# 🚀 Future Improvements

- Named Ranges
- Conditional Data Validation
- Employee Dashboard
- Interactive Search Panel
- Pivot Tables
- Charts and Dashboards

---

# 👨‍💻 Author

**Manasa Polisetty**

## GitHub

https://github.com/Manasapolisetty

---

⭐ This project is part of my journey to become a **Data Analyst**, where I practice Excel concepts through real-world business scenarios and portfolio-ready projects.
