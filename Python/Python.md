# 🐍 Python Data Types & Slicing

A beginner-friendly reference covering the core data types in Python and how to work with sequences using slicing and built-in methods.

---

## 📦 Data Types

Variables are containers that store values. Each value has a **type** that determines what you can do with it.

| Type | Example |
|------|---------|
| `str` (String) | `'Nelson'`, `'haha'` |
| `int` (Integer) | `1`, `100` |
| `float` | `1.1`, `100.1` |
| `list` | `['haha', 123, 'Ben', True]` |
| `dict` (Dictionary) | `{'age': '24', 'name': 'Nelson'}` |
| `bool` (Boolean) | `True`, `False` |

```python
# Assigning variables
a = 'python'
print(a)  # outputs: python

# Boolean
a = True
b = False
```

> 💡 **Tip:** Use `type(variable)` to check the data type of any variable.

```python
print(type(a))  # <class 'str'>
```

---

## ✂️ Slicing

Slicing lets you extract a portion of a sequence (like a list or string) using index positions.

```python
b = ['human', 'haha', 100, True, 1.2, 1, 2, 3]

b[0]    # 'human'   → first item
b[1]    # 'haha'    → second item
b[-1]   # 3         → last item
b[:3]   # ['human', 'haha', 100]  → first 3 items
b[-2:]  # [2, 3]    → last 2 items
```

> 💡 Index counting starts at `0`. Negative indices count from the end.

---

## 📋 Working with Lists

```python
b = ['human', 'haha', 100, True, 1.2, 1, 2, 3]

# Find the index of an item
b.index('human')   # returns 0

# Add an item to the end
b.append('banana')
print(b)  # ['human', 'haha', 100, True, 1.2, 1, 2, 3, 'banana']
```

---

## 📖 Working with Dictionaries

Dictionaries store data as **key-value pairs**.

```python
a = {'name': 'nello', 'location': 'singapore', 'age': '99'}

# Access all keys or values
a.keys()    # dict_keys(['name', 'location', 'age'])
a.values()  # dict_values(['nello', 'singapore', '99'])

# Add a new key-value pair
a['interest'] = 'basketball'
print(a)
# {'name': 'nello', 'location': 'singapore', 'age': '99', 'interest': 'basketball'}
```

---

## 🔑 Quick Reference

| Goal | Code |
|------|------|
| Check data type | `type(variable)` |
| Get item by index | `list[0]` |
| Get last item | `list[-1]` |
| Slice a range | `list[1:4]` |
| Find item index | `list.index('item')` |
| Add to list | `list.append('item')` |
| Get all dict keys | `dict.keys()` |
| Get all dict values | `dict.values()` |
| Add to dictionary | `dict['new_key'] = 'value'` |
