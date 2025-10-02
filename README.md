# 📝 Python List Assignment

This repository contains a simple Python program that demonstrates basic **list operations** in Python.

## 📌 Task Requirements
1. Create an empty list called `my_list`.
2. Append the following elements to `my_list`: **10, 20, 30, 40**.
3. Insert the value **15** at the second position in the list.
4. Extend `my_list` with another list: **[50, 60, 70]**.
5. Remove the last element from `my_list`.
6. Sort `my_list` in ascending order.
7. Find and print the index of the value **30** in `my_list`.

---

## 🐍 Code (list_assignment.py)

```python
# Create an empty list
my_list = []

# Append elements
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Insert 15 at the second position (index 1)
my_list.insert(1, 15)

# Extend with another list [50, 60, 70]
my_list.extend([50, 60, 70])

# Remove the last element
my_list.pop()

# Sort the list in ascending order
my_list.sort()

# Find and print the index of 30
index_30 = my_list.index(30)

print("Final list:", my_list)
print("Index of 30:", index_30)
