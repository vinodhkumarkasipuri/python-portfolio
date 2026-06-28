# Python Variables

## 📌 Lesson Information

- Module: Python Fundamentals
- Lesson: 01 - Variables
- Difficulty: Beginner
- Practice File: variables.py

---

# What is a Variable?

A variable is a named container that stores data in memory.

Variables allow us to save information so that we can use it later in our program.

Example:

```python
name = "Vinod"
age = 29
```

---

# Why Do We Need Variables?

Without variables, every value would have to be written repeatedly.

Variables help us:

- Store information
- Reuse data
- Update values easily
- Make programs readable
- Reduce duplicate code

---

# Variable Syntax

```python
variable_name = value
```

Examples

```python
name = "Vinod"
age = 29
salary = 65000
is_student = False
```

---

# Variable Naming Rules

Python follows these rules:

✅ Can contain letters

```python
name
city
```

✅ Can contain numbers

```python
student1
emp100
```

✅ Can contain underscore

```python
first_name
employee_salary
```

❌ Cannot start with a number

```python
1name
```

❌ Cannot contain spaces

```python
first name
```

❌ Cannot use Python keywords

```python
class
if
while
```

---

# Naming Conventions

Good

```python
student_name
employee_salary
country
```

Bad

```python
a
x
abc123
```

Always use meaningful names.

---

# Variable Types Used

| Variable | Value | Type |
|----------|-------|------|
| name | Vinod | String |
| age | 29 | Integer |
| salary | 65000 | Integer |
| height | 5.9 | Float |
| is_student | False | Boolean |

---

# Printing Variables

```python
print(name)
print(age)
```

Output

```
Vinod
29
```

---

# Multiple Variables

```python
wife_name = "Keerthi"
daughter_name = "Nyaara"
city = "Hyderabad"

print(wife_name)
print(daughter_name)
print(city)
```

---

# Updating Variables

Variables can change.

```python
age = 29

age = 30
```

Now age becomes 30.

---

# Best Practices

✔ Use meaningful names

✔ Follow snake_case

✔ Avoid one-letter variables

✔ Keep naming consistent

✔ Use lowercase letters

---

# Common Beginner Mistakes

❌ Starting variable names with numbers

❌ Forgetting quotation marks

❌ Using spaces

❌ Mixing uppercase and lowercase unnecessarily

---

# Real-world Example

```python
employee_name = "John"
employee_id = 1001
department = "Finance"
salary = 85000
```

---

# Practice Exercise

Create variables for:

- Your Name
- Age
- City
- Country
- Wife Name
- Daughter Name
- Dream Job

Print all variables.

---

# Key Takeaways

- Variables store data.
- Variables have names.
- Python is case-sensitive.
- Use meaningful names.
- Variables make programs reusable.

---

# Files in this Lesson

```
01-variables/
│
├── variables.py
└── README.md
```

---

# Next Lesson

➡ Data Types