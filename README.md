# PythonWeek2 - Python List Operations

This project demonstrates basic Python list operations such as creating, appending, inserting, extending, removing, sorting, and finding the index of an element.

## Steps Performed
1. Create an empty list called `my_list`.
2. Append elements `10`, `20`, `30`, and `40` to the list.
3. Insert the value `15` at the second position in the list.
4. Extend `my_list` with another list: `[50, 60, 70]`.
5. Remove the last element from the list.
6. Sort the list in ascending order.
7. Find and print the index of the value `30` in the list.

## Code Example

```python
# Create an empty list
my_list = []

# Append elements
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Insert 15 at second position
my_list.insert(1, 15)

# Extend the list
my_list.extend([50, 60, 70])

# Remove the last element
my_list.pop()

# Sort in ascending order
my_list.sort()

# Find the index of 30
index_of_30 = my_list.index(30)

print("Final list:", my_list)
print("Index of 30:", index_of_30)
Expected Output
yaml
Copy code
Final list: [10, 15, 20, 30, 40, 50, 60]
Index of 30: 3
Requirements
Python 3.x installed on your machine.

Run the Code
Save the file as list_operations.py.

Run in terminal/command prompt:

bash
Copy code
python list_operations.py
