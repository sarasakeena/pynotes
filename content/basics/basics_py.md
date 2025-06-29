---
title: Basics Py
date: 2025-06-29
author: Your Name
cell_count: 42
score: 40
---

```python
# Declare variable
x = 5

```


```python
# Print variable
print(x)

```

    5
    


```python
# Update variable
x = 10

```


```python
# Print new value
print("Updated x:", x)

```

    Updated x: 10
    


```python
text = "Hello Sara"

```


```python
print(text)

```

    Hello Sara
    


```python
print("Length:", len(text))

```

    Length: 10
    


```python
print("Upper:", text.upper())

```

    Upper: HELLO SARA
    


```python
print("Replace:", text.replace("Sara", "Queen"))

```

    Replace: Hello Queen
    


```python
fruits = ["apple", "banana", "cherry"]

```


```python
print(fruits[0])

```

    apple
    


```python
fruits.append("orange")

```


```python
print(fruits)

```

    ['apple', 'banana', 'cherry', 'orange']
    


```python
fruits.remove("banana")
    
```


```python
print(fruits)

```

    ['apple', 'cherry', 'orange']
    


```python
a = 15
b = 4

```


```python
print("Addition:", a + b)

```

    Addition: 19
    


```python
print("Subtraction:", a - b)

```

    Subtraction: 11
    


```python
print("Multiplication:", a * b)

```

    Multiplication: 60
    


```python
print("Division:", a / b)

```

    Division: 3.75
    


```python
print("Modulus:", a % b)

```

    Modulus: 3
    


```python
print("Exponentiation:", a ** b)

```

    Exponentiation: 50625
    


```python
# Casting to int
num = int("5")
print("Integer:", num)

```

    Integer: 5
    


```python
# Casting to float
f = float("3.14")
print("Float:", f)

```

    Float: 3.14
    


```python
# Casting to string
s = str(123)
print("String:", s)

```

    String: 123
    


```python
# Type checking
print(type(f))

```

    <class 'float'>
    


```python
print(type(s))

```

    <class 'str'>
    


```python
# For loop
for i in range(3):
    print("For loop iteration:", i)

```

    For loop iteration: 0
    For loop iteration: 1
    For loop iteration: 2
    


```python
# While loop
count = 0
while count < 2:
    print("While loop count:", count)
    count += 1

```

    While loop count: 0
    While loop count: 1
    


```python
# Break
for i in range(5):
    if i == 3:
        break
    print("Breaking at:", i)

```

    Breaking at: 0
    Breaking at: 1
    Breaking at: 2
    


```python
# Continue
for i in range(5):
    if i == 2:
        continue
    print("Continue at:", i)

```

    Continue at: 0
    Continue at: 1
    Continue at: 3
    Continue at: 4
    


```python
# Continue
for i in range(5):
    if i == 2:
        continue
    print("Continue at:", i)

```

    Continue at: 0
    Continue at: 1
    Continue at: 3
    Continue at: 4
    


```python
# Pass
for i in range(1):
    pass  # Placeholder

```


```python
# Pass
for i in range(1):
    pass  # Placeholder

```


```python
x = 10
if x > 5:
    print("x is greater than 5")

```

    x is greater than 5
    


```python
if x == 10:
    print("x is exactly 10")

```

    x is exactly 10
    


```python
if x < 5:
    print("x is less than 5")
else:
    print("x is not less than 5")

```

    x is not less than 5
    


```python
if x > 5 and x < 15:
    print("x is between 5 and 15")

```

    x is between 5 and 15
    


```python
if x == 5 or x == 10:
    print("x is either 5 or 10")

```

    x is either 5 or 10
    


```python
print("basics done")
```

    basics done
    


```python

```


```python

```


---
**Score: 40**