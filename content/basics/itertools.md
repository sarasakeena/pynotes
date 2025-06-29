---
title: Itertools
date: 2025-06-29
author: Your Name
cell_count: 350
score: 350
---

```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




```python
import itertools

```


```python
a = [1, 2, 3]

```


```python
b = [4, 5]

```


```python
list(itertools.product(a, b))

```




    [(1, 4), (1, 5), (2, 4), (2, 5), (3, 4), (3, 5)]




```python
list(itertools.permutations(a))

```




    [(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)]




```python
list(itertools.combinations(a, 2))

```




    [(1, 2), (1, 3), (2, 3)]




```python
list(itertools.combinations_with_replacement(a, 2))

```




    [(1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3)]




```python
list(itertools.accumulate(a))

```




    [1, 3, 6]




```python
list(itertools.chain(a, b))

```




    [1, 2, 3, 4, 5]




```python
list(itertools.islice(itertools.count(10), 5))

```




    [10, 11, 12, 13, 14]




---
**Score: 350**