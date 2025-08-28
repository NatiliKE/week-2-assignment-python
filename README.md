List Operations in Python

This example demonstrates how to create and manipulate a list in Python using common list methods.

Steps Performed

Create an empty list

my_list = []


Append elements to the list

my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)


Result: [10, 20, 30, 40]

Insert a value at a specific position
Insert 15 at index 1 (second position).

my_list.insert(1, 15)


Result: [10, 15, 20, 30, 40]

Extend the list with another list

my_list.extend([50, 60, 70])


Result: [10, 15, 20, 30, 40, 50, 60, 70]

Remove the last element

my_list.pop()


Result: [10, 15, 20, 30, 40, 50, 60]

Sort the list in ascending order

my_list.sort()


Result: [10, 15, 20, 30, 40, 50, 60]

Find the index of a value
Find the index of 30:

index_of_30 = my_list.index(30)
print(index_of_30)  # Output: 3

Final Output
Final List: [10, 15, 20, 30, 40, 50, 60]
Index of 30: 3
