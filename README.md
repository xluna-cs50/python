Prac - 1A
# PROGRAM: VARIABLES AND DATA TYPES

This program demonstrates the different data types available in Python.

## Overview

This Python script illustrates how to create variables of various data types and print their values along with their types.

## Data Types Covered

### 1. Integer Variable
```python
age = 20
print("Age:", age)
print("Data type of age:", type(age))
```
Integers are whole numbers without decimal points.

### 2. Float Variable
```python
height = 5.9
print("Height:", height)
print("Data type of height:", type(height))
```
Floats are numbers with decimal points.

### 3. String Variable
```python
student_name = "Student A"
print("Student Name:", student_name)
print("Data type of student_name:", type(student_name))
```
Strings are sequences of characters enclosed in quotes.

### 4. Boolean Variable
```python
is_student = True
print("Is student:", is_student)
print("Data type of is_student:", type(is_student))
```
Booleans are True or False values.

### 5. List Variable
```python
marks = [85, 90, 75, 92]
print("Marks list:", marks)
print("Data type of marks:", type(marks))
```
Lists are ordered, mutable collections of items.

### 6. Tuple Variable
```python
subjects = ("Maths", "Science", "English")
print("Subjects tuple:", subjects)
print("Data type of subjects:", type(subjects))
```
Tuples are ordered, immutable collections of items.

### 7. Dictionary Variable
```python
student_info = {
    "id": 101,
    "class": "SYbsc",
    "roll_no": 25
}

print("Student info dictionary:", student_info)
print("Data type of student_info:", type(student_info))
```
Dictionaries are unordered collections of key-value pairs.

### 8. Set Variable
```python
unique_numbers = {10, 20, 30, 20, 10}
print("Unique Numbers Set:", unique_numbers)
print("Data type of unique_numbers:", type(unique_numbers))
```
Sets are unordered collections of unique items.

## How to Run

To run this program, save it as a Python file and execute it with:
```bash
python variables_and_data_types.py
```

## Learning Outcomes

After running this program, you'll understand:
- How to declare variables of different data types
- How Python's `type()` function identifies data types
- The characteristics of each built-in data type in Python
