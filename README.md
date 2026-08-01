# CloudExify-Project-2

# Student Grade Management System

A command-line based Student Grade Management System built using Python.

This project was developed as part of the CloudExify Python Internship 2026 - Month 1 Project.

---

## Project Description

The Student Grade Management System is a CLI application designed to help teachers or administrators manage student records.

The system allows users to:
- Add students
- Add grades for multiple subjects
- View student details
- Calculate averages
- Check pass/fail status
- Search students
- Edit student records
- Remove students
- Generate class reports
- Sort students by grades
- Save and load records using CSV files

---

## Features

### Student Management

- Add new student records
- Search students by ID or name
- Edit student information
- Remove student records


### Grade Management

- Add grades for multiple subjects
- Calculate student average
- Automatically determine Pass/Fail status


### Reports

- Highest student average
- Lowest student average
- Overall class average
- Sort students by performance


### Data Storage

- Student records are stored in a CSV file.
- Data automatically loads when the program starts.
- Data automatically saves when the program exits.

---

## Technologies Used

- Python 3.x
- Object-Oriented Programming (OOP)
- CSV File Handling
- Dictionaries
- Lists
- Command Line Interface (CLI)

---

## Project Structure

```

StudentGradeSystem/

│
├── main.py
│       Main program and menu system
│
├── student.py
│       Student class and grade calculations
│
├── grade_manager.py
│       Student management operations
│
├── file_handler.py
│       CSV save/load functionality
│
├── utils.py
│       Input validation helpers
│
├── students.csv
│       Stored student records
│
└── README.md
Project documentation

```

---

## How to Run

### 1. Open the project folder

```

cd StudentGradeSystem

```

### 2. Run the application

```

python main.py

```

---

## Example Menu

```

=============================================
STUDENT GRADE MANAGEMENT SYSTEM
===============================

1. Add Student
2. Add Grade
3. View All Students
4. Search Student
5. Edit Student
6. Remove Student
7. Class Report
8. Sort Students
9. Save Data
10. Exit

```

---

## Example Student Record

```

ID      : 101
Name    : Ahmed

Grades:
Python: 90
Database: 80
Math: 85

Average : 85.00
Status  : Pass

```

---

## Learning Outcomes

This project demonstrates:

- Python classes and objects
- Object-Oriented Programming basics
- Functions
- Lists and dictionaries
- File handling
- CSV data storage
- Exception handling
- Sorting algorithms
- Data management

---

## Future Improvements

Possible improvements:

- Add a graphical user interface
- Add login system
- Add database support
- Generate PDF reports
- Add attendance tracking
- Add charts and statistics

---

