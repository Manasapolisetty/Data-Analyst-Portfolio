# 📊 Employee Department Analysis (Excel)

## 📌 Project Overview

This project demonstrates the use of basic and intermediate Microsoft Excel functions to analyze employee salary data. The project focuses on categorizing employee income, calculating department-wise salary statistics, and applying formatting to improve data readability.

---

## 📂 Dataset

The dataset contains the following columns:

- Employee ID
- Department
- Salary
- Income Status

Sample Data:

| Employee ID | Department | Salary | Income |
|------------:|------------|-------:|--------|
| 1010 | IT | 30000 | LOW |
| 1011 | HR | 70000 | HIGH |
| 1012 | IT | 50000 | HIGH |
| 1013 | Sales | 40000 | LOW |
| 1014 | HR | 60000 | HIGH |
| 1015 | Sales | 50000 | HIGH |
| 1016 | Non-IT | 60000 | HIGH |

---

## 🎯 Objective

- Classify employee income using the IF function.
- Calculate total HR salary.
- Count the number of employees in the IT department.
- Find the average salary of the Sales department.
- Format the worksheet for better readability.

---

## 🛠 Excel Functions Used

### IF()

Used to classify employee income.

```excel
=IF(D2>=50000,"HIGH","LOW")
```

---

### SUMIF()

Calculates the total salary of HR employees.

```excel
=SUMIF(C2:C8,"HR",D2:D8)
```

Result:

**130000**

---

### COUNTIF()

Counts the number of IT employees.

```excel
=COUNTIF(C2:C8,"IT")
```

Result:

**2**

---

### AVERAGEIF()

Calculates the average salary of Sales employees.

```excel
=AVERAGEIF(C2:C8,"Sales",D2:D8)
```

Result:

**45000**

---

## 📈 Analysis Summary

- Total salary paid to HR employees: **130000**
- Number of IT employees: **2**
- Average salary of Sales employees: **45000**

---

## 🎨 Formatting

- Excel Table formatting
- Header styling
- Conditional Formatting on Salary column
- Professional layout for summary section

---

## 📚 Skills Demonstrated

- Microsoft Excel
- IF Function
- SUMIF
- COUNTIF
- AVERAGEIF
- Conditional Formatting
- Data Analysis
- Report Formatting

---

## 📸 Project Screenshot

Add the project screenshot below.

```
Screenshot.png
```

---

## 🚀 Learning Outcome

Through this project, I learned how to:

- Organize employee data in Excel.
- Perform department-wise salary analysis.
- Use logical and conditional Excel functions.
- Build professional Excel reports suitable for business analysis.

---

**Author:** Manasa Polisetty

**GitHub:** https://github.com/Manasapolisetty
