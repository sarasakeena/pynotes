---
title: Advanced Numpy
date: 2025-06-30
author: Your Name
cell_count: 126
score: 125
---

```python
import numpy as np
import pandas as pd
import time
from numpy.linalg import inv, det, eig, norm
```


```python
arr_1 = np.arange(6).reshape(2, 3)  # 6 is divisible by 2
print(arr_1)

```

    [[0 1 2]
     [3 4 5]]
    


```python
# Cell 2 – Array Creation
arr_2 = np.arange(2*3).reshape(3, -1)
print(arr_2)
```

    [[0 1]
     [2 3]
     [4 5]]
    


```python
# Cell 3 – Array Creation
arr_3 = np.arange(3*3).reshape(1, -1)
print(arr_3)
```

    [[0 1 2 3 4 5 6 7 8]]
    


```python
# Cell 4 – Array Creation
arr_4 = np.arange(4*3).reshape(2, -1)
print(arr_4)
```

    [[ 0  1  2  3  4  5]
     [ 6  7  8  9 10 11]]
    


```python
# Cell 5 – Array Creation
arr_5 = np.arange(5*3).reshape(3, -1)
print(arr_5)
```

    [[ 0  1  2  3  4]
     [ 5  6  7  8  9]
     [10 11 12 13 14]]
    


```python
# Cell 6 – Array Creation
arr_6 = np.arange(6*3).reshape(1, -1)
print(arr_6)
```

    [[ 0  1  2  3  4  5  6  7  8  9 10 11 12 13 14 15 16 17]]
    


```python
# Cell 7 – Array Creation
arr_7 = np.arange(24).reshape(2, -1)  # 24 ÷ 2 = 12 columns
print(arr_7)

```

    [[ 0  1  2  3  4  5  6  7  8  9 10 11]
     [12 13 14 15 16 17 18 19 20 21 22 23]]
    


```python
# Cell 8 – Array Creation
arr_8 = np.arange(8*3).reshape(3, -1)
print(arr_8)
```

    [[ 0  1  2  3  4  5  6  7]
     [ 8  9 10 11 12 13 14 15]
     [16 17 18 19 20 21 22 23]]
    


```python
# Cell 9 – Array Creation
arr_9 = np.arange(9*3).reshape(1, -1)
print(arr_9)
```

    [[ 0  1  2  3  4  5  6  7  8  9 10 11 12 13 14 15 16 17 18 19 20 21 22 23
      24 25 26]]
    


```python
# Cell 10 – Array Creation
arr_10 = np.arange(10*3).reshape(2, -1)
print(arr_10)
```

    [[ 0  1  2  3  4  5  6  7  8  9 10 11 12 13 14]
     [15 16 17 18 19 20 21 22 23 24 25 26 27 28 29]]
    


```python
# Cell 11 – Slicing & Indexing
print(arr_1[:1])
```

    [[0 1 2]]
    


```python
# Cell 12 – Slicing & Indexing
print(arr_2[:1])
```

    [[0 1]]
    


```python
# Cell 13 – Slicing & Indexing
print(arr_3[:1])
```

    [[0 1 2 3 4 5 6 7 8]]
    


```python
# Cell 14 – Slicing & Indexing
print(arr_4[:1])
```

    [[0 1 2 3 4 5]]
    


```python
# Cell 15 – Slicing & Indexing
print(arr_5[:1])
```

    [[0 1 2 3 4]]
    


```python
# Cell 16 – Slicing & Indexing
print(arr_6[:1])
```

    [[ 0  1  2  3  4  5  6  7  8  9 10 11 12 13 14 15 16 17]]
    


```python
# Cell 17 – Slicing & Indexing
print(arr_7[:1])
```

    [[ 0  1  2  3  4  5  6  7  8  9 10 11]]
    


```python
# Cell 18 – Slicing & Indexing
print(arr_8[:1])
```

    [[0 1 2 3 4 5 6 7]]
    


```python
# Cell 19 – Slicing & Indexing
print(arr_9[:1])
```

    [[ 0  1  2  3  4  5  6  7  8  9 10 11 12 13 14 15 16 17 18 19 20 21 22 23
      24 25 26]]
    


```python
# Cell 20 – Slicing & Indexing
print(arr_10[:1])
```

    [[ 0  1  2  3  4  5  6  7  8  9 10 11 12 13 14]]
    


```python
# Cell 21 – Stats
print('mean:', arr_1.mean(), 'std:', arr_1.std())
```

    mean: 2.5 std: 1.707825127659933
    


```python
# Cell 22 – Stats
print('mean:', arr_2.mean(), 'std:', arr_2.std())
```

    mean: 2.5 std: 1.707825127659933
    


```python
# Cell 23 – Stats
print('mean:', arr_3.mean(), 'std:', arr_3.std())
```

    mean: 4.0 std: 2.581988897471611
    


```python
# Cell 24 – Stats
print('mean:', arr_4.mean(), 'std:', arr_4.std())
```

    mean: 5.5 std: 3.452052529534663
    


```python
# Cell 25 – Stats
print('mean:', arr_5.mean(), 'std:', arr_5.std())
```

    mean: 7.0 std: 4.320493798938574
    


```python
# Cell 26 – Stats
print('mean:', arr_6.mean(), 'std:', arr_6.std())
```

    mean: 8.5 std: 5.188127472091127
    


```python
# Cell 27 – Stats
print('mean:', arr_7.mean(), 'std:', arr_7.std())
```

    mean: 11.5 std: 6.922186552431729
    


```python
# Cell 28 – Stats
print('mean:', arr_8.mean(), 'std:', arr_8.std())
```

    mean: 11.5 std: 6.922186552431729
    


```python
# Cell 29 – Stats
print('mean:', arr_9.mean(), 'std:', arr_9.std())
```

    mean: 13.0 std: 7.788880963698615
    


```python
# Cell 30 – Stats
print('mean:', arr_10.mean(), 'std:', arr_10.std())
```

    mean: 14.5 std: 8.65544144839919
    


```python
# Cell 31 – Matrix Ops
m = np.random.randint(1, 10, (3, 3))
print('Matrix:', m)
print('Det:', det(m))
```

    Matrix: [[8 2 2]
     [4 3 9]
     [8 9 6]]
    Det: -384.0
    


```python
# Cell 32 – Matrix Ops
m = np.random.randint(1, 10, (3, 3))
print('Matrix:', m)
print('Det:', det(m))
```

    Matrix: [[6 3 6]
     [9 5 7]
     [6 5 8]]
    Det: 30.000000000000014
    


```python
# Cell 33 – Matrix Ops
m = np.random.randint(1, 10, (3, 3))
print('Matrix:', m)
print('Det:', det(m))
```

    Matrix: [[9 2 4]
     [3 5 5]
     [6 4 1]]
    Det: -152.99999999999997
    


```python
# Cell 34 – Matrix Ops
m = np.random.randint(1, 10, (3, 3))
print('Matrix:', m)
print('Det:', det(m))
```

    Matrix: [[3 5 1]
     [8 8 5]
     [6 3 3]]
    Det: 32.999999999999986
    


```python
# Cell 35 – Matrix Ops
m = np.random.randint(1, 10, (3, 3))
print('Matrix:', m)
print('Det:', det(m))
```

    Matrix: [[4 6 8]
     [5 5 7]
     [9 7 7]]
    Det: 32.000000000000014
    


```python
# Cell 36 – Matrix Ops
m = np.random.randint(1, 10, (3, 3))
print('Matrix:', m)
print('Det:', det(m))
```

    Matrix: [[8 4 6]
     [9 5 5]
     [8 4 5]]
    Det: -4.000000000000003
    


```python
# Cell 37 – Matrix Ops
m = np.random.randint(1, 10, (3, 3))
print('Matrix:', m)
print('Det:', det(m))
```

    Matrix: [[8 9 2]
     [7 2 8]
     [5 7 3]]
    Det: -151.0
    


```python
# Cell 38 – Matrix Ops
m = np.random.randint(1, 10, (3, 3))
print('Matrix:', m)
print('Det:', det(m))
```

    Matrix: [[1 3 3]
     [8 2 9]
     [9 2 4]]
    Det: 131.00000000000006
    


```python
# Cell 39 – Matrix Ops
m = np.random.randint(1, 10, (3, 3))
print('Matrix:', m)
print('Det:', det(m))
```

    Matrix: [[4 8 8]
     [2 8 3]
     [3 6 1]]
    Det: -79.99999999999997
    


```python
# Cell 40 – Matrix Ops
m = np.random.randint(1, 10, (3, 3))
print('Matrix:', m)
print('Det:', det(m))
```

    Matrix: [[1 9 7]
     [3 4 3]
     [7 3 6]]
    Det: -90.99999999999997
    


```python
# Cell 41 – Matrix Ops
m = np.random.randint(1, 10, (3, 3))
print('Matrix:', m)
print('Det:', det(m))
```

    Matrix: [[2 2 5]
     [9 1 5]
     [6 5 2]]
    Det: 172.99999999999991
    


```python
# Cell 42 – Matrix Ops
m = np.random.randint(1, 10, (3, 3))
print('Matrix:', m)
print('Det:', det(m))
```

    Matrix: [[6 5 1]
     [5 8 1]
     [1 4 7]]
    Det: 154.00000000000006
    


```python
# Cell 43 – Matrix Ops
m = np.random.randint(1, 10, (3, 3))
print('Matrix:', m)
print('Det:', det(m))
```

    Matrix: [[8 3 3]
     [6 2 7]
     [1 6 9]]
    Det: -230.99999999999994
    


```python
# Cell 44 – Matrix Ops
m = np.random.randint(1, 10, (3, 3))
print('Matrix:', m)
print('Det:', det(m))
```

    Matrix: [[6 6 3]
     [7 5 6]
     [8 3 4]]
    Det: 74.99999999999997
    


```python
# Cell 45 – Matrix Ops
m = np.random.randint(1, 10, (3, 3))
print('Matrix:', m)
print('Det:', det(m))
```

    Matrix: [[1 5 7]
     [5 3 7]
     [6 1 5]]
    Det: 1.9999999999999905
    


```python
# Cell 46 – Random
np.random.seed(46)
print(np.random.rand(3, 3))
```

    [[0.78383235 0.63483371 0.24904309]
     [0.75807586 0.31307694 0.93723736]
     [0.04286545 0.4408672  0.91272229]]
    


```python
# Cell 47 – Random
np.random.seed(47)
print(np.random.rand(3, 3))
```

    [[0.11348847 0.97448309 0.72873463]
     [0.35146781 0.70760514 0.7996046 ]
     [0.64556185 0.41459961 0.70603101]]
    


```python
# Cell 48 – Random
np.random.seed(48)
print(np.random.rand(3, 3))
```

    [[0.01749027 0.89157327 0.28486117]
     [0.29897638 0.79203426 0.3244706 ]
     [0.86471039 0.44751263 0.54822991]]
    


```python
# Cell 49 – Random
np.random.seed(49)
print(np.random.rand(3, 3))
```

    [[0.30096446 0.24706183 0.92633514]
     [0.89160344 0.68327676 0.56688466]
     [0.54696588 0.21042384 0.76975447]]
    


```python
# Cell 50 – Random
np.random.seed(50)
print(np.random.rand(3, 3))
```

    [[0.49460165 0.2280831  0.25547392]
     [0.39632991 0.3773151  0.99657423]
     [0.4081972  0.77189399 0.76053669]]
    


```python
# Cell 51 – Random
np.random.seed(51)
print(np.random.rand(3, 3))
```

    [[0.67573142 0.04471218 0.34330367]
     [0.64401973 0.284213   0.94933781]
     [0.15767017 0.38797296 0.58999368]]
    


```python
# Cell 52 – Random
np.random.seed(52)
print(np.random.rand(3, 3))
```

    [[0.82311034 0.02611798 0.21077064]
     [0.61842177 0.09828447 0.62013131]
     [0.05389022 0.96065406 0.98042937]]
    


```python
# Cell 53 – Random
np.random.seed(53)
print(np.random.rand(3, 3))
```

    [[0.84666241 0.56116554 0.4548754 ]
     [0.35217491 0.58585138 0.53574974]
     [0.82745628 0.2645422  0.47837906]]
    


```python
# Cell 54 – Random
np.random.seed(54)
print(np.random.rand(3, 3))
```

    [[0.42018297 0.3632395  0.18487669]
     [0.51828273 0.00860545 0.96893621]
     [0.80138126 0.75731199 0.6714843 ]]
    


```python
# Cell 55 – Random
np.random.seed(55)
print(np.random.rand(3, 3))
```

    [[0.09310829 0.97165592 0.48385998]
     [0.2425227  0.53112383 0.28554424]
     [0.86263038 0.04110015 0.10834773]]
    


```python
# Cell 56 – Logical Ops
print(arr_7 > 1)
```

    [[False False  True  True  True  True  True  True  True  True  True  True]
     [ True  True  True  True  True  True  True  True  True  True  True  True]]
    


```python
# Cell 57 – Logical Ops
print(arr_8 > 2)
```

    [[False False False  True  True  True  True  True]
     [ True  True  True  True  True  True  True  True]
     [ True  True  True  True  True  True  True  True]]
    


```python
# Cell 58 – Logical Ops
print(arr_9 > 3)
```

    [[False False False False  True  True  True  True  True  True  True  True
       True  True  True  True  True  True  True  True  True  True  True  True
       True  True  True]]
    


```python
# Cell 59 – Logical Ops
print(arr_10 > 4)
```

    [[False False False False False  True  True  True  True  True  True  True
       True  True  True]
     [ True  True  True  True  True  True  True  True  True  True  True  True
       True  True  True]]
    


```python
# Cell 60 – Logical Ops
print(arr_1 > 0)
```

    [[False  True  True]
     [ True  True  True]]
    


```python
# Cell 61 – Logical Ops
print(arr_2 > 1)
```

    [[False False]
     [ True  True]
     [ True  True]]
    


```python
# Cell 62 – Logical Ops
print(arr_3 > 2)
```

    [[False False False  True  True  True  True  True  True]]
    


```python
# Cell 63 – Logical Ops
print(arr_4 > 3)
```

    [[False False False False  True  True]
     [ True  True  True  True  True  True]]
    


```python
# Cell 64 – Logical Ops
print(arr_5 > 4)
```

    [[False False False False False]
     [ True  True  True  True  True]
     [ True  True  True  True  True]]
    


```python
# Cell 65 – Logical Ops
print(arr_6 > 0)
```

    [[False  True  True  True  True  True  True  True  True  True  True  True
       True  True  True  True  True  True]]
    


```python
# Cell 66 – Sort & Argsort
rand = np.random.randint(1, 100, 5)
print('Sorted:', np.sort(rand))
```

    Sorted: [13 25 72 78 95]
    


```python
# Cell 67 – Sort & Argsort
rand = np.random.randint(1, 100, 5)
print('Sorted:', np.sort(rand))
```

    Sorted: [32 52 73 75 98]
    


```python
# Cell 68 – Sort & Argsort
rand = np.random.randint(1, 100, 5)
print('Sorted:', np.sort(rand))
```

    Sorted: [ 1 56 92 94 94]
    


```python
# Cell 69 – Sort & Argsort
rand = np.random.randint(1, 100, 5)
print('Sorted:', np.sort(rand))
```

    Sorted: [44 50 63 83 92]
    


```python
# Cell 70 – Sort & Argsort
rand = np.random.randint(1, 100, 5)
print('Sorted:', np.sort(rand))
```

    Sorted: [11 49 61 79 89]
    


```python
# Cell 71 – Sort & Argsort
rand = np.random.randint(1, 100, 5)
print('Sorted:', np.sort(rand))
```

    Sorted: [45 60 60 89 93]
    


```python
# Cell 72 – Sort & Argsort
rand = np.random.randint(1, 100, 5)
print('Sorted:', np.sort(rand))
```

    Sorted: [22 53 63 78 94]
    


```python
# Cell 73 – Sort & Argsort
rand = np.random.randint(1, 100, 5)
print('Sorted:', np.sort(rand))
```

    Sorted: [34 46 53 59 62]
    


```python
# Cell 74 – Sort & Argsort
rand = np.random.randint(1, 100, 5)
print('Sorted:', np.sort(rand))
```

    Sorted: [19 25 28 56 81]
    


```python
# Cell 75 – Sort & Argsort
rand = np.random.randint(1, 100, 5)
print('Sorted:', np.sort(rand))
```

    Sorted: [19 43 57 63 63]
    


```python
# Cell 76 – Stack/Split
a = np.ones(2)
b = np.zeros(2)
print(np.vstack((a,b)))
```

    [[1. 1.]
     [0. 0.]]
    


```python
# Cell 77 – Stack/Split
a = np.ones(3)
b = np.zeros(3)
print(np.vstack((a,b)))
```

    [[1. 1. 1.]
     [0. 0. 0.]]
    


```python
# Cell 78 – Stack/Split
a = np.ones(4)
b = np.zeros(4)
print(np.vstack((a,b)))
```

    [[1. 1. 1. 1.]
     [0. 0. 0. 0.]]
    


```python
# Cell 79 – Stack/Split
a = np.ones(5)
b = np.zeros(5)
print(np.vstack((a,b)))
```

    [[1. 1. 1. 1. 1.]
     [0. 0. 0. 0. 0.]]
    


```python
# Cell 80 – Stack/Split
a = np.ones(2)
b = np.zeros(2)
print(np.vstack((a,b)))
```

    [[1. 1.]
     [0. 0.]]
    


```python
# Cell 81 – Stack/Split
a = np.ones(3)
b = np.zeros(3)
print(np.vstack((a,b)))
```

    [[1. 1. 1.]
     [0. 0. 0.]]
    


```python
# Cell 82 – Stack/Split
a = np.ones(4)
b = np.zeros(4)
print(np.vstack((a,b)))
```

    [[1. 1. 1. 1.]
     [0. 0. 0. 0.]]
    


```python
# Cell 83 – Stack/Split
a = np.ones(5)
b = np.zeros(5)
print(np.vstack((a,b)))
```

    [[1. 1. 1. 1. 1.]
     [0. 0. 0. 0. 0.]]
    


```python
# Cell 84 – Stack/Split
a = np.ones(2)
b = np.zeros(2)
print(np.vstack((a,b)))
```

    [[1. 1.]
     [0. 0.]]
    


```python
# Cell 85 – Stack/Split
a = np.ones(3)
b = np.zeros(3)
print(np.vstack((a,b)))
```

    [[1. 1. 1.]
     [0. 0. 0.]]
    


```python
# Cell 86 – Set Ops
a = np.array([1,2,3,4])
b = np.array([3,4,5])
print(np.union1d(a,b))
```

    [1 2 3 4 5]
    


```python
# Cell 87 – Set Ops
a = np.array([1,2,3,4])
b = np.array([3,4,5])
print(np.union1d(a,b))
```

    [1 2 3 4 5]
    


```python
# Cell 88 – Set Ops
a = np.array([1,2,3,4])
b = np.array([3,4,5])
print(np.union1d(a,b))
```

    [1 2 3 4 5]
    


```python
# Cell 89 – Set Ops
a = np.array([1,2,3,4])
b = np.array([3,4,5])
print(np.union1d(a,b))
```

    [1 2 3 4 5]
    


```python
# Cell 90 – Set Ops
a = np.array([1,2,3,4])
b = np.array([3,4,5])
print(np.union1d(a,b))
```

    [1 2 3 4 5]
    


```python
# Cell 91 – Set Ops
a = np.array([1,2,3,4])
b = np.array([3,4,5])
print(np.union1d(a,b))
```

    [1 2 3 4 5]
    


```python
# Cell 92 – Set Ops
a = np.array([1,2,3,4])
b = np.array([3,4,5])
print(np.union1d(a,b))
```

    [1 2 3 4 5]
    


```python
# Cell 93 – Set Ops
a = np.array([1,2,3,4])
b = np.array([3,4,5])
print(np.union1d(a,b))
```

    [1 2 3 4 5]
    


```python
# Cell 94 – Set Ops
a = np.array([1,2,3,4])
b = np.array([3,4,5])
print(np.union1d(a,b))
```

    [1 2 3 4 5]
    


```python
# Cell 95 – Set Ops
a = np.array([1,2,3,4])
b = np.array([3,4,5])
print(np.union1d(a,b))
```

    [1 2 3 4 5]
    


```python
# Cell 96 – Flatten
x = np.array([[1,2],[3,4]])
print(x.flatten())
```

    [1 2 3 4]
    


```python
# Cell 97 – Flatten
x = np.array([[1,2],[3,4]])
print(x.flatten())
```

    [1 2 3 4]
    


```python
# Cell 98 – Flatten
x = np.array([[1,2],[3,4]])
print(x.flatten())
```

    [1 2 3 4]
    


```python
# Cell 99 – Flatten
x = np.array([[1,2],[3,4]])
print(x.flatten())
```

    [1 2 3 4]
    


```python
# Cell 100 – Flatten
x = np.array([[1,2],[3,4]])
print(x.flatten())
```

    [1 2 3 4]
    


```python
# Cell 101 – Save/Load
np.save('temp_101.npy', arr_2)
print(np.load('temp_101.npy'))
```

    [[0 1]
     [2 3]
     [4 5]]
    


```python
# Cell 102 – Save/Load
np.save('temp_102.npy', arr_3)
print(np.load('temp_102.npy'))
```

    [[0 1 2 3 4 5 6 7 8]]
    


```python
# Cell 103 – Save/Load
np.save('temp_103.npy', arr_4)
print(np.load('temp_103.npy'))
```

    [[ 0  1  2  3  4  5]
     [ 6  7  8  9 10 11]]
    


```python
# Cell 104 – Save/Load
np.save('temp_104.npy', arr_5)
print(np.load('temp_104.npy'))
```

    [[ 0  1  2  3  4]
     [ 5  6  7  8  9]
     [10 11 12 13 14]]
    


```python
# Cell 105 – Save/Load
np.save('temp_105.npy', arr_6)
print(np.load('temp_105.npy'))
```

    [[ 0  1  2  3  4  5  6  7  8  9 10 11 12 13 14 15 16 17]]
    


```python
# Cell 106 – Save/Load
np.save('temp_106.npy', arr_7)
print(np.load('temp_106.npy'))
```

    [[ 0  1  2  3  4  5  6  7  8  9 10 11]
     [12 13 14 15 16 17 18 19 20 21 22 23]]
    


```python
# Cell 107 – Save/Load
np.save('temp_107.npy', arr_8)
print(np.load('temp_107.npy'))
```

    [[ 0  1  2  3  4  5  6  7]
     [ 8  9 10 11 12 13 14 15]
     [16 17 18 19 20 21 22 23]]
    


```python
# Cell 108 – Save/Load
np.save('temp_108.npy', arr_9)
print(np.load('temp_108.npy'))
```

    [[ 0  1  2  3  4  5  6  7  8  9 10 11 12 13 14 15 16 17 18 19 20 21 22 23
      24 25 26]]
    


```python
# Cell 109 – Save/Load
np.save('temp_109.npy', arr_10)
print(np.load('temp_109.npy'))
```

    [[ 0  1  2  3  4  5  6  7  8  9 10 11 12 13 14]
     [15 16 17 18 19 20 21 22 23 24 25 26 27 28 29]]
    


```python
# Cell 110 – Save/Load
np.save('temp_110.npy', arr_1)
print(np.load('temp_110.npy'))
```

    [[0 1 2]
     [3 4 5]]
    


```python
# Cell 111 – Bonus Trick
x = np.random.rand(1000)
start = time.time()
s = np.sum(x)
end = time.time()
print('Time:', end - start)
```

    Time: 0.0
    


```python
# Cell 112 – Bonus Trick
x = np.random.rand(1000)
start = time.time()
s = np.sum(x)
end = time.time()
print('Time:', end - start)
```

    Time: 0.0
    


```python
# Cell 113 – Bonus Trick
x = np.random.rand(1000)
start = time.time()
s = np.sum(x)
end = time.time()
print('Time:', end - start)
```

    Time: 0.0010080337524414062
    


```python
# Cell 114 – Bonus Trick
x = np.random.rand(1000)
start = time.time()
s = np.sum(x)
end = time.time()
print('Time:', end - start)
```

    Time: 0.0
    


```python
# Cell 115 – Bonus Trick
x = np.random.rand(1000)
start = time.time()
s = np.sum(x)
end = time.time()
print('Time:', end - start)
```

    Time: 0.0
    


```python
# Cell 116 – Bonus Trick
x = np.random.rand(1000)
start = time.time()
s = np.sum(x)
end = time.time()
print('Time:', end - start)
```

    Time: 0.0
    


```python
# Cell 117 – Bonus Trick
x = np.random.rand(1000)
start = time.time()
s = np.sum(x)
end = time.time()
print('Time:', end - start)
```

    Time: 0.0
    


```python
# Cell 118 – Bonus Trick
x = np.random.rand(1000)
start = time.time()
s = np.sum(x)
end = time.time()
print('Time:', end - start)
```

    Time: 0.0
    


```python

x = np.random.rand(1000)
start = time.time()
s = np.sum(x)
end = time.time()
print('Time:', end - start)
```

    Time: 0.0
    


```python

x = np.random.rand(1000)
start = time.time()
s = np.sum(x)
end = time.time()
print('Time:', end - start)
```

    Time: 0.0
    


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
**Score: 125**