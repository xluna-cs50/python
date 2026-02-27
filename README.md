# Prac-1A: Variables and Data Types

## Program

```python
# PROGRAM: VARIABLES AND DATA TYPES

# Integer Variable
age = 20
print("Age:", age)
print("Data type of age:", type(age))

# Float Variable
height = 5.9
print("Height:", height)
print("Data type of height:", type(height))

# String Variable
student_name = "Student A"
print("Student Name:", student_name)
print("Data type of student_name:", type(student_name))

# Boolean Variable
is_student = True
print("Is student:", is_student)
print("Data type of is_student:", type(is_student))

# List Variable
marks = [85, 90, 75, 92]
print("Marks list:", marks)
print("Data type of marks:", type(marks))

# Tuple Variable
subjects = ("Maths", "Science", "English")
print("Subjects tuple:", subjects)
print("Data type of subjects:", type(subjects))

# Dictionary Variable
student_info = {
    "id": 101,
    "class": "SYbsc",
    "roll_no": 25
}
print("Student info dictionary:", student_info)
print("Data type of student_info:", type(student_info))

# Set Variable
unique_numbers = {10, 20, 30, 20, 10}
print("Unique Numbers Set:", unique_numbers)
print("Data type of unique_numbers:", type(unique_numbers))
```
# Prac-1B: Type Casting

## Program

```python
# PROGRAM: TYPE CASTING

# int to float
age_float = float(20)
print("Integer to float:", age_float)
print("Data type:", type(age_float))

# float to int
height_int = int(6.5)
print("Float to Integer:", height_int)
print("Data type:", type(height_int))

# int to string
age_str = str(20)
print("Integer to string:", age_str)
print("Data type:", type(age_str))

# string to int
number_text = "200"
number_int = int(number_text)
print("String to integer:", number_int)
print("Data type:", type(number_int))

# string to float
number_float = float(number_text)
print("String to float:", number_float)
print("Data type:", type(number_float))

# list to tuple
marks = [90, 95, 99, 94]
marks_tuple = tuple(marks)
print("List to tuple:", marks_tuple)
print("Data type:", type(marks_tuple))

# tuple to list
subjects = ("science", "maths", "english")
subjects_list = list(subjects)
print("Tuple to list:", subjects_list)
print("Data type:", type(subjects_list))


