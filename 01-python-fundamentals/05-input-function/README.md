# ⌨️ Input Function in Python

## 📖 Overview

The `input()` function is a built-in Python function that allows a program to receive data from the user while it is running.

Unlike `print()`, which displays information, `input()` waits for the user to enter a value, making Python programs interactive and dynamic.

---

## 🎯 Topics Covered

- ✅ What is `input()`
- ✅ Built-in Functions
- ✅ How `input()` Works
- ✅ Getting User Input
- ✅ Storing Input in Variables
- ✅ Printing User Input
- ✅ Hardcoded vs Dynamic Values
- ✅ Real-World Examples
- ✅ Common Mistakes

---

## 🧠 What is `input()`?

`input()` is a built-in Python function used to get information from the user.

When Python reaches an `input()` statement:

1. Displays a message to the user.
2. Waits for the user to type something.
3. Stores the entered value.
4. Continues executing the program.

---

## ⚙️ Syntax

```python
variable_name = input("Enter something: ")
```

### Example

```python
name = input("Enter your name: ")

print(name)
```

---

## 🔄 How `input()` Works

```text
Program Starts
      │
      ▼
Display Message
      │
      ▼
Wait for User Input
      │
      ▼
User Types Value
      │
      ▼
Press Enter
      │
      ▼
Store Value in Variable
      │
      ▼
Continue Program
```

---

## 📝 Store User Input

```python
name = input("Enter your name: ")
```

The value entered by the user is stored inside the variable.

---

## 🖨️ Display User Input

```python
name = input("Enter your name: ")

print(name)
```

---

## ✨ Using f-Strings

```python
name = input("Enter your name: ")

print(f"Hello, {name}!")
```

---

## 📌 Hardcoded vs Dynamic Values

### Hardcoded Value

```python
country = "India"
```

The value is fixed inside the program.

---

### Dynamic Value

```python
country = input("Enter your country: ")
```

The value changes based on what the user enters.

---

## 🌍 Real-World Examples

`input()` is used in many real applications:

- Login Forms
- Registration Forms
- ATM PIN Entry
- Search Boxes
- Online Shopping
- Chat Applications
- AI Chatbots
- Banking Applications

---

## ⚠️ Common Mistakes

### ❌ Forgetting to Store Input

```python
input("Enter your name: ")
```

✅ Correct

```python
name = input("Enter your name: ")
```

---

### ❌ Forgetting to Use the Variable

```python
name = input("Enter your name: ")
```

Nothing will be displayed.

✅ Correct

```python
print(name)
```

---

### ❌ Expecting a Number

```python
age = input("Enter your age: ")
```

`input()` always returns a string.

✅ Convert to an integer when needed:

```python
age = int(input("Enter your age: "))
```

---

## 📂 Practice File

```text
input_practice.py
```

---

## 🎯 Learning Outcome

After completing this lesson, I can:

- Understand the purpose of `input()`
- Create interactive Python programs
- Receive user input
- Store input in variables
- Display user input
- Use f-strings with user input
- Understand hardcoded and dynamic values
- Avoid common mistakes

---

## 🚀 Next Topic

➡️ **06 - Data Types**