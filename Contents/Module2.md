<div align="center">

# 📗 Module 2

# Data Management & Logical Functions

### **Day 2 | Duration: 4 Hours**

**Microsoft Excel for Civil Engineering Applications**

Department of Civil Engineering  
Guru Nanak Dev Engineering College, Ludhiana

<br>

**🏠 [Home](../README.md) | 📚 [Contents](Contents.md) | ⬅️ [Module 1](Module1.md) | ⏭️ [Module 3](Module3.md)**

</div>

---

# 🎯 Learning Objectives

Upon successful completion of this module, students will be able to:

- Organize large datasets efficiently.
- Sort and filter data based on different criteria.
- Validate user input using Data Validation.
- Create drop-down lists.
- Apply logical functions for decision making.
- Retrieve information using lookup functions.
- Build automated worksheets with minimal manual effort.

---

# 📖 Module Contents

## Session 1 – Managing Data in Excel

As the amount of data increases, organizing it properly becomes essential. Excel provides several tools that allow engineers to efficiently manage, search, and analyse large datasets.

---

## Session 2 – Sorting Data

### What is Sorting?

Sorting arranges data in a specific order.

Common types include:

- Ascending Order (A → Z)
- Descending Order (Z → A)
- Smallest to Largest
- Largest to Smallest

### Example

| Student | Marks |
|----------|------:|
| Aman | 78 |
| Rahul | 92 |
| Simran | 85 |

Sort the data according to marks.

---

## Session 3 – Filtering Data

Filtering displays only the records that satisfy specified conditions.

### Example

Display only students who scored more than **80 marks**.

---

## Session 4 – Data Validation

Data Validation restricts users from entering invalid data.

Applications include:

- Gender
- Department
- Grade
- Material Type
- Unit

### Example

Allow only:

```
Present
Absent
```

in an Attendance column.

---

## Session 5 – Creating Drop-down Lists

Drop-down lists improve data consistency and reduce typing errors.

Example:

| Material |
|-----------|
| Cement |
| Sand |
| Aggregate |
| Steel |

Students will learn to create custom lists using **Data Validation**.

---

## Session 6 – Flash Fill

Flash Fill automatically recognizes patterns and fills data accordingly.

### Example

Convert

| First Name | Last Name |
|------------|-----------|
| Rahul | Sharma |

into

```
Rahul Sharma
```

automatically.

---

## Session 7 – Find & Replace

Useful for modifying repeated values quickly.

Example:

Replace

```
CE
```

with

```
Civil Engineering
```

throughout the worksheet.

---

# Logical Functions

Logical functions allow Excel to make decisions based on specified conditions.

---

# Session 8 – IF() Function

### Syntax

```excel
=IF(Logical_Test, Value_if_True, Value_if_False)
```

### Example

If marks are greater than or equal to 40, display **Pass**; otherwise, display **Fail**.

```excel
=IF(B2>=40,"Pass","Fail")
```

---

## Practical Example

| Name | Marks | Result |
|------|------:|--------|
| Aman | 72 | Pass |
| Rahul | 31 | Fail |

---

# Session 9 – AND() Function

Returns **TRUE** only if **all** conditions are satisfied.

### Syntax

```excel
=AND(condition1,condition2)
```

### Example

A student passes only if:

- Attendance ≥ 75%
- Marks ≥ 40

```excel
=AND(B2>=75,C2>=40)
```

---

# Session 10 – OR() Function

Returns **TRUE** if **any one** condition is satisfied.

### Example

A student is eligible if:

- Sports quota = Yes

OR

- NCC quota = Yes

```excel
=OR(B2="Yes",C2="Yes")
```

---

# Session 11 – IFERROR() Function

Used to replace Excel error messages with meaningful output.

### Syntax

```excel
=IFERROR(value,value_if_error)
```

### Example

```excel
=IFERROR(A2/B2,"Division Not Possible")
```

---

# Lookup Functions

Lookup functions help retrieve information automatically from large datasets.

---

# Session 12 – VLOOKUP()

### Purpose

Searches for a value in the first column of a table and returns a corresponding value from another column.

### Syntax

```excel
=VLOOKUP(Lookup_Value,Table_Array,Column_Number,FALSE)
```

### Example

| Roll No | Name |
|---------|------|
| 101 | Aman |
| 102 | Rahul |
| 103 | Simran |

Searching Roll No. **102** returns **Rahul**.

---

# Session 13 – Introduction to XLOOKUP()

Unlike VLOOKUP, XLOOKUP can search both left and right and is easier to use.

### Syntax

```excel
=XLOOKUP(Lookup_Value,Lookup_Array,Return_Array)
```

Example:

```excel
=XLOOKUP(102,A2:A10,B2:B10)
```

---

# 🖥 Hands-on Exercise 1

## Student Result Sheet

Create the following worksheet.

| Roll No. | Name | Marks | Percentage | Grade | Result |
|-----------|------|-------:|-----------:|-------|--------|

Use:

- SUM()
- AVERAGE()
- IF()

Automatically display:

- Pass/Fail
- Grade

---

# 🖥 Hands-on Exercise 2

## Attendance Management Sheet

Prepare a worksheet containing:

| Name | Total Classes | Classes Attended | Attendance % | Eligible |
|------|--------------:|-----------------:|-------------:|----------|

Use:

```excel
=IF(D2>=75,"Yes","No")
```

---

# 🖥 Hands-on Exercise 3

## Construction Material Inventory

Prepare the following table.

| Material | Unit | Quantity | Unit Cost | Supplier |
|----------|------|----------:|----------:|----------|

Students will:

- Sort materials alphabetically.
- Filter by supplier.
- Create drop-down lists.
- Apply Data Validation.

---

# 🖥 Hands-on Exercise 4

## Employee Directory

Create an employee database.

Retrieve employee details automatically using:

- VLOOKUP()
- XLOOKUP()

---

# 💡 Tips & Shortcuts

| Shortcut | Function |
|-----------|----------|
| Ctrl + Shift + L | Apply Filter |
| Ctrl + F | Find |
| Ctrl + H | Replace |
| Alt + ↓ | Open Drop-down List |
| Ctrl + A | Select All |
| Ctrl + Home | First Cell |
| Ctrl + End | Last Used Cell |

---

# 📝 Assignment

Develop an automated **Student Performance Management System** that includes:

- Student Information
- Marks
- Attendance
- Percentage
- Grade
- Pass/Fail Status

The workbook should demonstrate the use of:

- IF()
- AND()
- OR()
- IFERROR()
- VLOOKUP() or XLOOKUP()
- Sorting
- Filtering
- Data Validation

Apply professional formatting before submission.

---

# 📚 Summary

In this module, you learned:

- Sorting and Filtering
- Data Validation
- Drop-down Lists
- Flash Fill
- Find & Replace
- IF()
- AND()
- OR()
- IFERROR()
- VLOOKUP()
- XLOOKUP()

These tools significantly improve efficiency by automating calculations, reducing errors, and making large datasets easier to manage.

---

<div align="center">

## ✅ End of Module 2

**⬅️ [Module 1](Module1.md) &nbsp;&nbsp;|&nbsp;&nbsp; 📚 [Contents](Contents.md) &nbsp;&nbsp;|&nbsp;&nbsp; 🏠 [Home](../README.md) &nbsp;&nbsp;|&nbsp;&nbsp; ⏭️ [Module 3](Module3.md)**

</div>
