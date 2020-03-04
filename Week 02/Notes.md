# Week 2
## Lists

### Define List
```py
list = []
print(type(list))  # prints <class 'list'>

variables = [10, 'ITUBees', True, 12.6, False]
print(variables)  # print the list
```
### Add and remove elements
```py
variables.append("Navid's friends")  # add element
print(variables)

variables.pop()  # removes last element
print(variables)
```

### Indexing and Manipulating
```py
fruits = ['apple', 'orange', 'watermelon', 'banana', 'kiwi']
print(fruits[0])  # prints only [first element]
print(fruits[2])  # prints only [3rd element]
print(fruits[2:5])  # prints list from [3rd element] to (last element)
print(fruits[2:])  # prints list from [3rd element] to (last element)
print(fruits[:3])  # prints list from [first element] to (third element)
print(fruits[-2])  # prints only [second element from end]
print(fruits[2:-2])  # prints list from [3d element] to (second element from end)
print(fruits[::2])  # prints list from [1st element] to (last element) stepping (2 element)

fruits[0] = "strawberry"
print(fruits)  # prints "strawberry"
```

### 2D Arrays
```py
matrix = [[11, 12, 13], [21, 22, 23], [31, 32, 33]]
print(matrix[0])  # gives first row
print(matrix[0][1])  # gives i_12
```

 ## Dictionaries
 
 ### Define Dictionary
 ```py
dict = {}
print(type(dict))
 ```
 
 ### Reaching Dictionary Entries
 ```py
students = {1: 'navid', 2: 'ismail'}
print(students)  # prints dictionary
print(students[2])

words = {'apple': 'elma', 'orange': 'portakal'}
print(words['orange'])  # prints "portakal"
 ```














