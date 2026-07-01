# 🧩 Data Types in Python

Learn the fundamental data types in Python and understand how different kinds of data are stored and used in programs.

---

# 📖 Overview

Data types define the kind of value a variable can store. Python provides several built-in data types, but the most commonly used are:

- 🔢 Numbers (`int`, `float`)
- 📝 Strings (`str`)
- ✅ Booleans (`bool`)

Understanding data types is essential because every Python program works with them.

---

# 📚 Topics Covered

### 🔢 Numbers
- Integers (`int`)
- Floating-point numbers (`float`)
- Basic arithmetic operations
- Division (`/` vs `//`)
- Power operator (`**`)

---

### 📝 Strings
- Creating strings
- Single quotes and double quotes
- Triple quotes
- String concatenation (`+`)
- String repetition (`*`)
- Finding string length (`len()`)
- Converting values using `str()`

---

### ✅ Booleans
- True and False
- Creating boolean variables
- Comparison operators
- Boolean expressions
- Using booleans in conditions

---

# 💻 Examples

## Numbers

```python
age = 25
price = 199.99

print(type(age))
print(type(price))
```

---

## Strings

```python
name = "Vinod Kumar"

print(name)
print(len(name))
```

---

## Booleans

```python
is_logged_in = True
is_admin = False

print(is_logged_in)
print(type(is_admin))
```

---

# ⚠️ Common Mistakes

## 🔢 Numbers

### Division always returns float

```python
result = 10 / 2
print(result)        # 5.0
print(type(result))  # float
```

Use integer division if needed.

```python
result = 10 // 2
print(result)
```

---

### Can't use commas in numbers

❌ Wrong

```python
million = 1,000,000
```

✅ Right

```python
million = 1000000
```

or

```python
million = 1_000_000
```

---

## 📝 Strings

### Mixing quotes

❌ Wrong

```python
text = "Hello'
```

✅ Right

```python
text = "Hello"
text = 'Hello'
```

---

### Can't add strings and numbers

❌ Wrong

```python
result = "Age: " + 25
```

✅ Right

```python
result = "Age: " + str(25)
```

---

### Forgetting quotation marks

❌ Wrong

```python
name = Alice
```

✅ Right

```python
name = "Alice"
```

---

## ✅ Booleans

### Wrong capitalization

❌ Wrong

```python
is_ready = true
is_done = FALSE
```

✅ Right

```python
is_ready = True
is_done = False
```

---

### Using `=` instead of `==`

❌ Wrong

```python
if age = 18:
    print("Adult")
```

✅ Right

```python
if age == 18:
    print("Adult")
```

Better

```python
if is_logged_in:
    print("Welcome")
```

---

# 💡 Best Practices

- Use meaningful variable names.
- Store text inside quotes.
- Use integers for whole numbers.
- Use floats for decimal values.
- Use booleans for True/False conditions.
- Use `type()` whenever you're unsure of a variable's data type.
- Use `_` in large numbers for readability.

Example:

```python
population = 1_500_000
```

---

# 📁 Practice Files

```text
data_types_practice.py
numbers_practice.py
strings_practice.py
booleans_practice.py
```

---

# 🎯 Learning Outcomes

After completing this section, you will be able to:

- ✅ Understand Python data types
- ✅ Work with integers and floating-point numbers
- ✅ Create and manipulate strings
- ✅ Use Boolean values for decision making
- ✅ Check variable types using `type()`
- ✅ Avoid common beginner mistakes
- ✅ Write cleaner and more readable Python code