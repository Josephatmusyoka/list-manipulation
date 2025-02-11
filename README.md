# List Manipulation Script

This repository contains a simple Python script demonstrating basic list operations. The script performs the following tasks:

1. Creates an empty list called `my_list`.
2. Appends the elements `10`, `20`, `30`, and `40` to `my_list`.
3. Inserts the value `15` at the second position in the list.
4. Extends `my_list` with another list: `[50, 60, 70]`.
5. Removes the last element from `my_list`.
6. Sorts `my_list` in ascending order.
7. Finds and prints the index of the value `30` in `my_list`.

## Script

Here is the Python script included in this repository:

```python
# Create an empty list called my_list
my_list = []

# Append the following elements to my_list: 10, 20, 30, 40
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Insert the value 15 at the second position in the list
my_list.insert(1, 15)

# Extend my_list with another list: [50, 60, 70]
my_list.extend([50, 60, 70])

# Remove the last element from my_list
my_list.pop()

# Sort my_list in ascending order
my_list.sort()

# Find and print the index of the value 30 in my_list
index_of_30 = my_list.index(30)
print("Index of 30:", index_of_30)
