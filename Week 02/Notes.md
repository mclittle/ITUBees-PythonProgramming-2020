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

## Conditional Operators

### if, else, elif

```py
if True:
    print('Hello, ITUBees')
```

```py
is_male = True
if is_male == True:  # Can be used as "if is_male:"
    print('User is male')
else:
    print('User is female')
```

```py
gender = 'M'  # F: Female, M: Male, O: Other
if gender == 'F':
    print('User is female')
elif gender == 'M':
    print('User is male')
elif gender == 'O':
    print('User is other gender')
else:
    print('Unknown gender')
```

```py
number = 13
max_limit = 10
if number < 10:
    print('number is in the limits')
elif number >= 10:  # else statement can be used
    print('number is out of the limits')
```

```py
number = 7
max_limit = 10
min_limit = 3

if number > min_limit and number < max_limit:  # min_limit < number < max_limit can be used
    print('number is in the limits')
elif number <= min_limit or number >= max_limit:  # else statement can be used
    print('number is out of the limits')
```













