# List.py
my_list = []  # 1. Create an empty list

my_list.append(10)  #Box now has (10) 
my_list.append(20   #Box now has (10, 20)
my_list.append(30)  #Box now has (10, 20, 30)
my_list.append(40)  #Box now has (10, 20, 30)

my_list.insert(1, 15)  #Box now has (10, 15, 20, 30, 40)

my_list.extend([50, 60, 70])  #Box now has (10, 15, 20, 30, 40, 50, 60, 70)

my_list.pop()  #Box now has (10,15,20,30,40,50,60)

my_list.sort()  #Box now has (10, 15, 20, 30, 40, 50, 60)

index_of_30 = my_list.index(30)  # 7. Find the index of 30
print(index_of_30)  #This will print 3, because 30 is at the 4th position (index 3)
The index of 30 in my_list is 3.
