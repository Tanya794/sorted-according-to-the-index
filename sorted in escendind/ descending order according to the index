from random import *

user = int(input("How many numbers are in your list?: "))

lst = [randint(1,20) for i in range(user)]
print(f"List with random numbers: {lst}")
even = []
odd = []

for t in range(user):
    if t % 2 == 0:
        even.append(lst[t])
    else:
        odd.append(lst[t])

even.sort()
odd.sort(reverse = True)

lst1 = []

for i in range(user):
    if i % 2 == 0:
        lst1.insert(i, even.pop(0))
    else:
        lst1.insert(i, odd.pop(0))

# numbers with even indexes sorted in ascending order, number with odd indexes sorted in descending order       
print(f"Result: {lst1}") 
