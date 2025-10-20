# Assignment-2
This is a simple python program that asked me to perform some operations on a list
[assignment 2.py](https://github.com/user-attachments/files/23005165/assignment.2.py)
# Create an empty list
my_list = []
# append elements
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# insert 15 at the second position(index 1)
my_list.insert(1,15)

# extend the list with another list
my_list.extend([50,60,70])

# remove the last element from the list
my_list.pop()

# sort the list in ascending order
my_list.sort()

# find and print the index of the value 30
index_of_30 = my_list.index(30)

print("my_list:", my_list)
print("index of 30:", index_of_30)
