---
title: Numpy Basics
date: 2025-06-29
author: Your Name
cell_count: 6
score: 5
---

```python
import numpy as np
```


```python
a = np.array([1, 2, 3])
b = np.array([[1, 2], [3, 4]])

```


```python
print("1D array:", a)
print("2D array:\n", b)
```

    1D array: [1 2 3]
    2D array:
     [[1 2]
     [3 4]]
    


```python
print("Sum:", a.sum())
print("Mean:", a.mean())
print("Max:", a.max())
print("Shape of b:", b.shape)
```

    Sum: 6
    Mean: 2.0
    Max: 3
    Shape of b: (2, 2)
    


```python
print("a[1]:", a[1])
print("b[0, 1]:", b[0, 1])
print("a[1:]:", a[1:])
```

    a[1]: 2
    b[0, 1]: 2
    a[1:]: [2 3]
    


```python

```


---
**Score: 5**