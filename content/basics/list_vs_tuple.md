---
title: List Vs Tuple
date: 2025-06-29
author: Your Name
cell_count: 5
score: 5
---

```python
import time
```


```python
list1 = [1, 2, 3]
list1[0] = 100
```


```python
tuple1 = (1, 2, 3)
try:
    tuple1[0] = 100
except TypeError as e:
    print("Tuples are immutable:", e)
```

    Tuples are immutable: 'tuple' object does not support item assignment
    


```python
def list_test():
    list_x = [x for x in range(1000000)]
    
def tuple_test():
    tuple_x = tuple(x for x in range(1000000))

start = time.time()
list_test()
print("List time:", time.time() - start)

start = time.time()
tuple_test()
print("Tuple time:", time.time() - start)
```

    List time: 0.09406590461730957
    Tuple time: 0.0926821231842041
    


```python
- Lists: Mutable, Slower, More flexible
- Tuples: Immutable, Faster, Safer for fixed data
```


---
**Score: 5**