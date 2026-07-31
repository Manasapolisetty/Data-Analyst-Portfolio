# 📘 Excel Lookup Functions - VLOOKUP, HLOOKUP & XLOOKUP

## 📌 Project Overview

This project demonstrates the implementation of Excel Lookup Functions used in real-world business scenarios. It includes practical examples of **VLOOKUP**, **HLOOKUP**, and **XLOOKUP** for retrieving data from employee and sales datasets.

This project is part of my **90-Day Data Analyst Placement Preparation Bootcamp**.

---

## 🎯 Objectives

- Learn the concept of Lookup Functions.
- Retrieve data using **VLOOKUP**.
- Retrieve horizontal data using **HLOOKUP**.
- Use **XLOOKUP** for flexible lookups.
- Understand the differences between all three lookup functions.
- Practice real-world business scenarios.

---

## 📊 Dataset 1 – Employee Information

| Employee ID | Name | Department |
|------------:|------|------------|
| 101 | Ravi | HR |
| 102 | Priya | IT |
| 103 | Sunil | Sales |
| 104 | Meena | HR |
| 105 | Rahul | IT |

### Salary Table

| Employee ID | Salary |
|------------:|-------:|
| 101 | 30000 |
| 102 | 45000 |
| 103 | 40000 |
| 104 | 42000 |
| 105 | 55000 |

---

## 📊 Dataset 2 – Monthly Business Report

| Category | Jan | Feb | Mar | Apr | May |
|----------|----:|----:|----:|----:|----:|
| Sales | 500 | 650 | 700 | 800 | 900 |
| Profit | 50 | 70 | 90 | 120 | 150 |
| Expenses | 300 | 350 | 400 | 450 | 500 |

---

# 🔍 VLOOKUP

### Purpose

Searches for a value in the **first column** of a table and returns the corresponding value from another column.

### Syntax

```excel
=VLOOKUP(lookup_value, table_array, col_index_num, FALSE)
```

### Tasks Performed

- Display Salary of Employee ID **103**
- Display Salary of Employee ID **105**
- Display Salary of Employee ID **101**

### Skills Learned

- Exact Match Lookup
- Searching Between Two Tables
- Employee Record Retrieval

---

# 🔍 HLOOKUP

### Purpose

Searches for a value in the **first row** of a table and returns a value from a specified row.

### Syntax

```excel
=HLOOKUP(lookup_value, table_array, row_index_num, FALSE)
```

### Tasks Performed

- Find Sales for March
- Find Profit for April
- Find Expenses for May

### Skills Learned

- Horizontal Data Lookup
- Monthly Report Analysis
- Row-Based Searching

---

# 🔍 XLOOKUP

### Purpose

Searches one range and returns the corresponding value from another range.

### Syntax

```excel
=XLOOKUP(lookup_value, lookup_array, return_array, "Not Found")
```

### Tasks Performed

- Find Salary of Employee ID **104**
- Find Department of Rahul
- Find Employee ID of Priya
- Display **"Not Found"** when Employee ID 110 is searched

### Skills Learned

- Dynamic Lookup
- Right-to-Left Lookup
- Error Handling
- Flexible Searching

---

# 📈 Business Applications

These lookup functions are commonly used for:

- Employee Management
- Payroll Systems
- HR Reports
- Inventory Management
- Sales Reporting
- Product Price Lookup
- Customer Information Retrieval

---

# 🛠 Skills Demonstrated

- Microsoft Excel
- VLOOKUP
- HLOOKUP
- XLOOKUP
- Data Retrieval
- Business Reporting
- Lookup Functions
- Excel Formula Writing
- Data Analysis

---

# 📷 Project Screenshot

Add your Excel project screenshot here.

Example:

```
03_Excel_Lookup_Functions/
│
├── Employee_Lookup_Functions.xlsx
├── Screenshot.png
└── README.md
```

---

# 📚 Learning Outcomes

After completing this project, I learned to:

- Use VLOOKUP to retrieve data from another table.
- Use HLOOKUP for horizontally arranged datasets.
- Use XLOOKUP for advanced and flexible lookups.
- Understand the differences between VLOOKUP, HLOOKUP, and XLOOKUP.
- Apply lookup functions to solve business problems efficiently.

---

# 🚀 Future Improvements

- INDEX + MATCH
- Data Validation
- Named Ranges
- Dynamic Drop-down Lists
- Employee Dashboard
- Interactive Excel Reports

---

## 👨‍💻 Author

**Manasa Polisetty**

### GitHub

https://github.com/Manasapolisetty

---

⭐ If you found this project helpful, feel free to explore my GitHub repository for more Data Analyst projects.
