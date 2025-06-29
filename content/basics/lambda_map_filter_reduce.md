---
title: Lambda Map Filter Reduce
date: 2025-06-30
author: Your Name
cell_count: 450
score: 450
---

```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
lst = ['a', 'b', 'c']
for index, value in enumerate(lst): print(index, value)
```

    0 a
    1 b
    2 c
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
lst = ['a', 'b', 'c']
for index, value in enumerate(lst): print(index, value)
```

    0 a
    1 b
    2 c
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
lst = ['a', 'b', 'c']
for index, value in enumerate(lst): print(index, value)
```

    0 a
    1 b
    2 c
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
lst = ['a', 'b', 'c']
for index, value in enumerate(lst): print(index, value)
```

    0 a
    1 b
    2 c
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
lst = ['a', 'b', 'c']
for index, value in enumerate(lst): print(index, value)
```

    0 a
    1 b
    2 c
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
lst = ['a', 'b', 'c']
for index, value in enumerate(lst): print(index, value)
```

    0 a
    1 b
    2 c
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
lst = ['a', 'b', 'c']
for index, value in enumerate(lst): print(index, value)
```

    0 a
    1 b
    2 c
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
lst = ['a', 'b', 'c']
for index, value in enumerate(lst): print(index, value)
```

    0 a
    1 b
    2 c
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
lst = ['a', 'b', 'c']
for index, value in enumerate(lst): print(index, value)
```

    0 a
    1 b
    2 c
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
lst = ['a', 'b', 'c']
for index, value in enumerate(lst): print(index, value)
```

    0 a
    1 b
    2 c
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
lst = ['a', 'b', 'c']
for index, value in enumerate(lst): print(index, value)
```

    0 a
    1 b
    2 c
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
lst = ['a', 'b', 'c']
for index, value in enumerate(lst): print(index, value)
```

    0 a
    1 b
    2 c
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
lst = ['a', 'b', 'c']
for index, value in enumerate(lst): print(index, value)
```

    0 a
    1 b
    2 c
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
lst = ['a', 'b', 'c']
for index, value in enumerate(lst): print(index, value)
```

    0 a
    1 b
    2 c
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
lst = ['a', 'b', 'c']
for index, value in enumerate(lst): print(index, value)
```

    0 a
    1 b
    2 c
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
lst = ['a', 'b', 'c']
for index, value in enumerate(lst): print(index, value)
```

    0 a
    1 b
    2 c
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
lst = ['a', 'b', 'c']
for index, value in enumerate(lst): print(index, value)
```

    0 a
    1 b
    2 c
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
lst = ['a', 'b', 'c']
for index, value in enumerate(lst): print(index, value)
```

    0 a
    1 b
    2 c
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
lst = ['a', 'b', 'c']
for index, value in enumerate(lst): print(index, value)
```

    0 a
    1 b
    2 c
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
lst = ['a', 'b', 'c']
for index, value in enumerate(lst): print(index, value)
```

    0 a
    1 b
    2 c
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
x = [1, 2, 3]
y = ['a', 'b', 'c']
z = zip(x, y)
print(list(z))
```

    [(1, 'a'), (2, 'b'), (3, 'c')]
    


```python
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
print(result)
```

    [2, 4, 6, 8]
    


```python
lst = ['a', 'b', 'c']
for index, value in enumerate(lst): print(index, value)
```

    0 a
    1 b
    2 c
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
x = lambda a, b : a * b
print(x(5, 6))
```

    30
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
x = lambda a : a + 10
print(x(5))
```

    15
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
lst = ['a', 'b', 'c']
for index, value in enumerate(lst): print(index, value)
```

    0 a
    1 b
    2 c
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
words = ['hello', 'world']
result = list(map(str.upper, words))
print(result)
```

    ['HELLO', 'WORLD']
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
x = lambda a, b, c : a + b + c
print(x(1, 2, 3))
```

    6
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x * y, nums)
print(result)
```

    24
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)
```

    10
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


```python
names = ['Amy', 'Ben', 'Cathy', 'Dan']
result = list(filter(lambda x: x.startswith('C'), names))
print(result)
```

    ['Cathy']
    


```python
names = ['a', 'b', 'c']
scores = [85, 90, 95]
result = list(zip(names, scores))
print(result)
```

    [('a', 85), ('b', 90), ('c', 95)]
    


```python
lst = ['a', 'b', 'c']
for index, value in enumerate(lst): print(index, value)
```

    0 a
    1 b
    2 c
    


```python
s = 'hello'
for i, ch in enumerate(s): print(i, ch)
```

    0 h
    1 e
    2 l
    3 l
    4 o
    


```python
nums = [1, 2, 3, 4, 5, 6]
result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

    [2, 4, 6]
    


---
**Score: 450**