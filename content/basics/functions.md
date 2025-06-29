---
title: Functions
date: 2025-06-30
author: Your Name
cell_count: 29
score: 25
---

```python
def greet():
    print("Hello, Sara!")

greet()

```

    Hello, Sara!
    


```python
def add(a, b):
    return a + b
```


```python
add(5, 3)
```




    8




```python
def say_hello():
    print("Hello!")
```


```python
def greet_name(name):
    print(f"Hi {name}!")
```


```python
def square(x):
    return x * x
```


```python
def welcome(name="Sara"):
    print(f"Welcome, {name}!")
```


```python
def intro(name, age):
    print(f"{name} is {age} years old")
```


```python
intro(age=21, name="Sara")
```

    Sara is 21 years old
    


```python
def total(*nums):
    print(sum(nums))
```


```python
total(1, 2, 3, 4)
```

    10
    


```python
def student_details(**kwargs):
    for key, value in kwargs.items():
        print(f"{key}: {value}")
```


```python
student_details(name="Sara", age=20, course="AI")
```

    name: Sara
    age: 20
    course: AI
    


```python
x = 10
def func():
    x = 5
    print("Inside:", x)
```


```python
func()
print("Outside:", x)
```

    Inside: 5
    Outside: 10
    


```python
x = 10
def update():
    global x
    x = 20
```


```python
update()
print("Now x:", x)
```

    Now x: 20
    


```python
square = lambda x: x * x
print(square(6))

```

    36
    


```python
add = lambda a, b: a + b
add(2, 3)

```




    5




```python
nums = [1, 2, 3, 4]
squares = list(map(lambda x: x**2, nums))
print(squares)

```

    [1, 4, 9, 16]
    


```python
evens = list(filter(lambda x: x % 2 == 0, nums))
print(evens)

```

    [2, 4]
    


```python
from functools import reduce
total = reduce(lambda a, b: a + b, nums)
print(total)

```

    10
    


```python
# Mini calculator
def calc(a, b, op):
    if op == '+': return a + b
    elif op == '-': return a - b
    elif op == '*': return a * b
    elif op == '/': return a / b
    else: return "Invalid"

calc(10, 5, '*')

```




    50




```python

# Use input + call functions
def main():
    a = int(input("Enter a: "))
    b = int(input("Enter b: "))
    op = input("Enter operator (+ - * /): ")
    print("Result:", calc(a, b, op))

main() 

```

    Enter a:  2
    Enter b:  2
    Enter operator (+ - * /):  +
    

    Result: 4
    


```python

```


```python

```


```python

```


```python

```


```python

```


---
**Score: 25**