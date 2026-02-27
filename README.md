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

```

# Practical-2: Conditional Statements

## Aim

To understand and demonstrate the use of conditional statements (if, if-else, if-elif-else, nested if) in Python.

---

## Program

```python
# PRACTICAL 2 – CONDITIONAL STATEMENTS


# 1. IF STATEMENT
print("\n1. IF statement - check positive Number")

num = int(input("Enter a number: "))
if num > 0:
    print("The number is Positive")


# 2. IF – ELSE STATEMENT
print("\n2. IF – ELSE Statement – Check Even or Odd")

num = int(input("Enter a number: "))

if num % 2 == 0:
    print("Number is Even")
else:
    print("Number is Odd")


# 3. IF – ELIF – ELSE STATEMENT
print("\n3. IF – ELIF – ELSE Statement – Grade System")

marks = int(input("Enter your marks (0 – 100): "))

if marks >= 90:
    print("Grade: A+")
elif marks >= 80:
    print("Grade: A")
elif marks >= 70:
    print("Grade: B")
elif marks >= 60:
    print("Grade: C")
elif marks >= 50:
    print("Grade: D")
elif marks >= 35:
    print("Grade: Pass")
else:
    print("Grade: Fail")


# 4. NESTED IF STATEMENT
print("\n4. NESTED IF – Positive and Even Check")

num = int(input("Enter a number: "))

if num > 0:
    if num % 2 == 0:
        print("Number is Positive and Even")
    else:
        print("Number is Positive but Odd")
else:
    print("Number is Zero or Negative")


# 5. LARGEST OF THREE NUMBERS
print("\n5. Find Largest of Three Numbers")

a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

if a > b and a > c:
    print("Largest number is:", a)
elif b > a and b > c:
    print("Largest number is:", b)
else:
    print("Largest number is:", c)


print("\n====== PRACTICAL COMPLETED ======")
```

---

## Conclusion

Successfully demonstrated the use of if, if-else, if-elif-else, and nested if conditional statements in Python.

# Practical-3: Loops (For Loop & While Loop)

## Aim

To understand and demonstrate the use of for loop and while loop in Python.

---

## Program (A) – For Loop Programs

```python
# FOR LOOP PROGRAMS

# 1. Print numbers 1 to 10
for i in range(1, 11):
    print(i)


# 2. Multiplication table of 5
for i in range(1, 11):
    print("5 x", i, "=", 5 * i)


# 3. Print even numbers from 1 to 20
for i in range(1, 21):
    if i % 2 == 0:
        print(i)


# 4. Print odd numbers from 1 to 20
for i in range(1, 21):
    if i % 2 != 0:
        print(i)


# 5. Print squares from 1 to 5
for i in range(1, 6):
    print("Square of", i, "=", i * i)


# 6. Print cubes from 1 to 5
for i in range(1, 6):
    print("Cube of", i, "=", i * i * i)


# 7. Iterate through list
animals = ["Cat", "Dog", "Lion"]
for a in animals:
    print(a)


# 8. Print characters of a string
word = "Python"
for ch in word:
    print(ch)


# 9. Print sum of numbers 1 to 10
total = 0
for i in range(1, 11):
    total += i
    print("Sum =", total)


# 10. Reverse numbers from 10 to 1
for i in range(10, 0, -1):
    print(i)
```

---

## Program (B) – While Loop Programs

```python
# WHILE LOOP PROGRAMS

print("\nWHILE LOOP PROGRAMS")

# 1. Print numbers from 1 to 10
num = 1
while num <= 10:
    print(num)
    num += 1


# 2. Print even numbers up to 20
num = 2
while num <= 20:
    print(num)
    num += 2


# 3. Print odd numbers up to 19
num = 1
while num <= 19:
    print(num)
    num += 2


# 4. Print multiplication table of 3
i = 1
while i <= 10:
    print("3 x", i, "=", 3 * i)
    i += 1


# 5. Find sum of numbers 1 to 10
total = 0
i = 1
while i <= 10:
    total += i
    i += 1

print("Sum =", total)


# 6. Reverse counting from 5 to 1
num = 5
while num >= 1:
    print(num)
    num -= 1


# 7. Print squares using while
i = 1
while i <= 5:
    print("Square of", i, "=", i * i)
    i += 1


# 8. Print cubes using while
i = 1
while i <= 5:
    print("Cube of", i, "=", i * i * i)
    i += 1


# 9. Print all elements of list using while
colors = ["Red", "Blue", "Green"]
i = 0
while i < len(colors):
    print(colors[i])
    i += 1


# 10. Print characters of string using while
word = "Loop"
i = 0
while i < len(word):
    print(word[i])
    i += 1
```

---

## Conclusion

Successfully demonstrated the use of for loop and while loop in Python with various examples.

# Practical-4: Functions in Python

## Aim

To understand and demonstrate the use of user-defined functions in Python.

---

## Program

```python
# PRACTICAL 4 – FUNCTIONS PROGRAMS


# 1. Simple Interest
def simple_interest(p, r, t):
    si = (p * r * t) / 100
    return si

p = int(input("Enter principal: "))
r = int(input("Enter rate: "))
t = int(input("Enter time: "))

print("Simple Interest =", simple_interest(p, r, t))


# 2. Check Positive / Negative / Zero
def check_number(n):
    if n > 0:
        return "Positive"
    elif n < 0:
        return "Negative"
    else:
        return "Zero"

num = int(input("Enter a number: "))
print(check_number(num))


# 3. Sum of first n natural numbers
def sum_n(n):
    return n * (n + 1) // 2

num = int(input("Enter a number: "))
print("Sum =", sum_n(num))


# 4. Area of Circle
def area_circle(r):
    return 3.14 * r * r

radius = float(input("Enter radius: "))
print("Area of Circle =", area_circle(radius))


# 5. Celsius to Fahrenheit
def celsius_to_fahrenheit(c):
    return (c * 9 / 5) + 32

c = float(input("Enter temperature in Celsius: "))
print("Temperature in Fahrenheit =", celsius_to_fahrenheit(c))


# 6. Addition of Two Numbers
def add(a, b):
    return a + b

x = int(input("Enter first number: "))
y = int(input("Enter second number: "))

result = add(x, y)
print("Addition =", result)


# 7. Check Even or Odd
def check_even_odd(n):
    if n % 2 == 0:
        return "Even"
    else:
        return "Odd"

num = int(input("Enter a number: "))
print("Number is", check_even_odd(num))


# 8. Square of a Number
def square(n):
    return n * n

num = int(input("Enter a number: "))
print("Square =", square(num))


# 9. Maximum of Two Numbers
def maximum(a, b):
    if a > b:
        return a
    else:
        return b

x = int(input("Enter first number: "))
y = int(input("Enter second number: "))

print("Maximum =", maximum(x, y))


# 10. Factorial of a Number
def factorial(n):
    fact = 1
    for i in range(1, n + 1):
        fact = fact * i
    return fact

num = int(input("Enter a number: "))
print("Factorial =", factorial(num))
```

---

## Conclusion

Successfully demonstrated the use of user-defined functions in Python for various mathematical and logical operations.

# Practical-5: List Programs

## Aim

To understand and demonstrate list creation, operations, and functions in Python.

---

## Program (A) – List Basic Operations

```python
# PRACTICAL 5 – LIST OPERATIONS

# 1. Create and print list
lst = [10, 20, 30]
print(lst)


# 2. Access list elements
colors = ["Red", "Blue", "Green"]
print(colors[0])
print(colors[1])


# 3. Append element
nums = [1, 2, 3]
nums.append(4)
print(nums)


# 4. Insert element
nums = [10, 20, 40]
nums.insert(1, 20)
print(nums)


# 5. Remove element
nums = [10, 20, 30]
nums.remove(10)
print(nums)


# 6. Pop element
nums = [10, 20, 30]
nums.pop()
print(nums)


# 7. Update element
marks = [50, 60, 70]
marks[1] = 65
print(marks)


# 8. Create list using user input
n = int(input("Enter number of elements: "))
lst = []

for i in range(n):
    lst.append(input("Enter Value: "))

print(lst)


# 9. Length, max and min
nums = [4, 8, 3, 9]
print(len(nums))
print(max(nums))
print(min(nums))


# 10. Traverse list using for loop
nums = [10, 20, 30]
for i in nums:
    print(i)
```

---

## Program (B) – List Functions (Insert, Delete, Update)

```python
# PRACTICAL 5 – LIST FUNCTIONS


# Create List Function
def create_list():
    lst = []
    n = int(input("Enter number of elements: "))
    for i in range(n):
        lst.append(int(input("Enter Values: ")))
    return lst


mylist = create_list()
print("List:", mylist)


# Display List
def display_list(lst):
    for i in lst:
        print(i)

display_list(mylist)


# Insert Element
def insert_element(lst):
    val = int(input("Enter value to insert: "))
    lst.append(val)
    return lst

insert_element(mylist)
print("After Insert:", mylist)


# Delete Element
def delete_element(lst):
    val = int(input("Enter value to delete: "))
    if val in lst:
        lst.remove(val)
    else:
        print("Element not found")

delete_element(mylist)
print("After delete:", mylist)


# Update Element
def update_element(lst):
    pos = int(input("Enter index to update: "))
    val = int(input("Enter new value: "))
    lst[pos] = val

update_element(mylist)
print("After update:", mylist)
```

---

## Conclusion

Successfully demonstrated list creation, basic operations, and user-defined functions for insert, delete, and update in Python.

# Practical-6: Tuples and Dictionary

## Aim

To understand and demonstrate the use of tuples and dictionaries in Python.

---

## Program (A) – Tuple Basics

```python
# PRAC – 6 (A) : TUPLE PROGRAMS

# 1. Simple Tuple
t1 = (10, 20, 30)
print("Simple Tuple:", t1)

# 2. Heterogeneous Tuple
t2 = (1, "Python", 3.5, True)
print("Heterogeneous Tuple:", t2)

# 3. Nested Tuple
t3 = ((1, 2), (3, 4))
print("Nested Tuple:", t3)

# 4. Single Element Tuple
t4 = (5,)
print("Single Element Tuple:", t4)

# 5. Tuple using User Input
n = int(input("Enter number of elements: "))
lst = []

for i in range(n):
    lst.append(input("Enter value: "))

t5 = tuple(lst)
print("User input Tuple:", t5)
```

---

## Program (B) – Tuple Operations

```python
# PRAC – 6 (B) : TUPLE OPERATIONS

# Create a tuple
t = (10, 20, 30, 40, 20)
print("Original Tuple:", t)

# 1. Indexing
print("Element at index 0:", t[0])
print("Element at index 3:", t[3])

# 2. Slicing
print("Slice from index 1 to 4:", t[1:4])
print("Slice till index 3:", t[:3])
print("Slice from index 2:", t[2:])

# 3. Traversing Tuple
print("Traversing tuple:")
for i in t:
    print(i)

# 4. Length of Tuple
print("Length of tuple:", len(t))

# 5. Concatenation
t1 = (1, 2, 3)
t2 = (4, 5)
t3 = t1 + t2
print("After concatenation:", t3)

# 6. Repetition
print("Repetition:", t1 * 3)

# 7. Membership operation
print("20 in Tuple:", 20 in t)
print("50 not in tuple:", 50 not in t)

# 8. Max and Min
print("Maximum value:", max(t))
print("Minimum value:", min(t))

# 9. Count and Index
print("Count of 20:", t.count(20))
print("Index of 30:", t.index(30))
```

---

## Program (C) – Dictionary Programs

```python
# PRAC – 6 (C) : DICTIONARY PROGRAMS

# 1. Creating a dictionary for a student
abc = {
    "roll": 301,
    "name": "Riya",
    "marks": (78, 85, 92)
}

print("Original Dictionary:", abc)

# 2. Accessing elements
print("Roll Number:", abc["roll"])
print("Student Marks:", abc["marks"])

# 3. Adding new element
abc["grade"] = "A"
print("After Adding Grade:", abc)

# 4. Updating element
abc["name"] = "Riya Sharma"
print("After Updating Name:", abc)

# 5. Deleting element
del abc["grade"]
print("After Deleting Grade:", abc)

# 6. Dictionary length
print("Length of dictionary:", len(abc))

# 7. Traversing dictionary
print("Traversing dictionary:")
for k, v in abc.items():
    print(k, ":", v)
```

---

## Conclusion

Successfully demonstrated tuple creation, operations, and dictionary creation with CRUD operations in Python.

# Practical-7: Regular Expressions

## Aim

To understand and demonstrate the use of regular expressions (re module) in Python.

---

## Program (A) – Basic Regex Checks

```python
# PRACTICAL 7 – REGULAR EXPRESSIONS (Basic Examples)

import re

text = "Hello123"

# Check if string contains a digit
if re.search(r'\d', text):
    print("Contains digit")

# Check if string starts with 'Hello'
if re.match(r'^Hello', "Hello World"):
    print("String starts with a word")

# Check if string ends with 'World'
if re.search(r'World$', "Hello World"):
    print("String ends with a word")

# Check if string contains only alphabets
if re.match(r'^[A-Za-z]+$', "xyz"):
    print("String has only alphabets")

# Validate mobile number (10 digits starting from 6-9)
if re.match(r'^[6-9]\d{9}$', "9876540310"):
    print("Valid Mobile Number")

# Validate email address
if re.match(r'^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$', "abc@gmail.com"):
    print("Valid Email Address")
```

---

## Program (B) – Name Validation

```python
import re

name = input("Enter your name: ")

if re.match(r'^[A-Za-z]+$', name):
    print("Name only contains alphabets")
else:
    print("Name contains invalid characters")
```

---

## Program (C) – Check if String Contains a Digit

```python
import re

text = input("Enter a string: ")

if re.search(r'\d', text):
    print("The string contains a digit")
else:
    print("The string does not contain a digit")
```

---

## Program (D) – Check if String Starts with 'Hello'

```python
import re

text = input("Enter a string: ")

if re.match(r'^Hello', text):
    print("String starts with Hello")
else:
    print("String does not start with Hello")
```

---

## Program (E) – Validate Mobile Number

```python
import re

mobile = input("Enter Mobile Number: ")

if re.match(r'^[6-9]\d{9}$', mobile):
    print("Valid Mobile Number")
else:
    print("Invalid Mobile Number")
```

---

## Program (F) – Validate Email Address

```python
import re

email = input("Enter email address: ")

pattern = r'^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$'

if re.match(pattern, email):
    print("Valid Email Address")
else:
    print("Invalid Email Address")
```

---

## Conclusion

Successfully demonstrated the use of regular expressions in Python for pattern matching, validation of names, mobile numbers, and email addresses.


