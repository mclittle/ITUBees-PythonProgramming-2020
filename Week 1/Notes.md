# Week 1: Introduction   

## Print
```py
print('Hello, ITUBees')
```

### Print with '
```py
print("Hello, ITU'Bees")
```

### Print with "
```py
print('Hello, "ITUBees"')
```

### Print with both ' and "
```py
print("Hello, \"ITU'Bees\"")
```

## Basic Data Types
```py
age = 20
pi = 3.14
name = "Ismail"
is_male = True
```

## Basic Operations
```py
a = 20.0
b = 16.0

c = a + b
d = a * b
e = a / b # gives 1.25 (in Python 2.x it gives 1)
f = a - b
g = a ** 2
h = a % b # gives 4 (remaining)
i = round(12.6)
j = abs(-10)
k = a // b # gives 1 (answer)
```

## Basic String Methods
### Some str Methods
```py
a = "Some String"

is_startswith_s = a.startswith("S") # result is a boolean
is_endswith_ing = a.endswith("ing") # result is a boolean
uppercase = a.upper() # result is a new string
lowercase = a.lower() # result is a new string

print(is_startswith_s) # prints True
print(is_endswith_ing) # prints True
print(uppercase) # prints "SOME STRING"
print(lowercase) # prints "some string"
```

### String Formatting
```py
name = "Ismail"
a = f"The coder name is {name}"

print(a) # prints "The coder name is Ismail"
```

### Multiline Strings
```py
a = '''
Mr. Smith,

This is a multiline string that comes to you from the deep of my heart.

Sincerely,
Ismail Kucuk
'''

print(a)
```