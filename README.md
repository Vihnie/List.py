# List.py
my_list = []  # 1. Create an empty list

my_list.append(10)  # 2. Append elements
my_list.append(20)
my_list.append(30)
my_list.append(40)

my_list.insert(1, 15)  # 3. Insert 15 at the second position

my_list.extend([50, 60, 70])  # 4. Extend with another list

my_list.pop()  # 5. Remove the last element

my_list.sort()  # 6. Sort in ascending order

index_of_30 = my_list.index(30)  # 7. Find the index of 30
print(index_of_30)  # Print the index
