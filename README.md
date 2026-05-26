# Assignment-8
#1
d = {'a': 3, 'b': 1, 'c': 2}

# Ascending
asc = dict(sorted(d.items(), key=lambda x: x[1]))
print("Ascending:", asc)

# Descending
desc = dict(sorted(d.items(), key=lambda x: x[1], reverse=True))
print("Descending:", desc)

#2
d = {'a': 1, 'b': 2, 'c': 3}
key = 'b'

if key in d:
    print("Key exists")
else:
    print("Key does not exist")

#3
d1 = {'a': 1, 'b': 2}
d2 = {'c': 3, 'd': 4}

merged = {**d1, **d2}
print("Merged Dictionary:", merged)

#4
t = (1, 2, 3)

t = t + (4,)
print("Updated Tuple:", t)

#5
t = (1, "Hello", 3.5, True)

print("Tuple:", t)

#6
lst = [1, 2, 3, 4, 5]

total = sum(lst)
print("Sum:", total)

#7
lst = [10, 25, 5, 40, 15]

largest = max(lst)
print("Largest Number:", largest)

#8
s = {1, 2, 3}

s.add(4)
s.update([5, 6])

print("Updated Set:", s)

#9
arr = [1, 2, 3, 4, 5]

arr.reverse()
print("Reversed Array:", arr)

#10
arr = [10, 20, 30, 40, 50]

print("Array:", arr)

# Access elements
print("First element:", arr[0])
print("Third element:", arr[2])

OUTPUT
Ascending: {'b': 1, 'c': 2, 'a': 3}
Descending: {'a': 3, 'c': 2, 'b': 1}
Key exists
Merged Dictionary: {'a': 1, 'b': 2, 'c': 3, 'd': 4}
Updated Tuple: (1, 2, 3, 4)
Tuple: (1, 'Hello', 3.5, True)
Sum: 15
Largest Number: 40
Updated Set: {1, 2, 3, 4, 5, 6}
Reversed Array: [5, 4, 3, 2, 1]
Array: [10, 20, 30, 40, 50]
First element: 10
Third element: 30
