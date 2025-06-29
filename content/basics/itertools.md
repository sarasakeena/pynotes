---
title: Itertools
date: 2025-06-30
author: Your Name
cell_count: 350
score: 350
---

```python
import itertools
```


```python
list(itertools.count(10, 2))[:11]
```


```python
list(itertools.cycle('ABCD'))[:12]
```


```python
list(itertools.repeat('hello', 5))
```


```python
list(itertools.accumulate([1,2,3,4]))
```


```python
list(itertools.chain('ABC', 'DEF'))
```


```python
list(itertools.compress('ABCDEF', [1,0,1,0,1,0]))
```


```python
list(itertools.dropwhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.takewhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.filterfalse(lambda x: x%2, range(10)))
```


```python
list(itertools.islice(range(20), 5))
```


```python
list(itertools.islice(range(20), 5, 15))
```


```python
list(itertools.islice(range(20), 5, 15, 2))
```


```python
list(itertools.permutations('ABC'))
```


```python
list(itertools.permutations('ABCD', 2))
```


```python
list(itertools.combinations('ABCD', 2))
```


```python
list(itertools.combinations_with_replacement('AB', 3))
```


```python
list(itertools.product('AB', repeat=2))
```


```python
list(itertools.groupby('AABBBCCDAA'))
```


```python
[list(g) for k, g in itertools.groupby('AABBBCCDAA')]
```


```python
list(itertools.starmap(pow, [(2,5), (3,2), (10,3)]))
```


```python
list(itertools.tee([1, 2, 3, 4], 2))[0]
```


```python
a, b = itertools.tee([1, 2, 3, 4], 2); list(a), list(b)
```


```python
list(itertools.zip_longest('AB', '1234', fillvalue='-'))
```


```python
data = [(1, 2), (3, 4)]; list(itertools.starmap(lambda x, y: x + y, data))
```


```python
list(itertools.accumulate(range(1, 6), lambda x, y: x*y))
```


```python
import itertools
```


```python
list(itertools.count(10, 2))[:12]
```


```python
list(itertools.cycle('ABCD'))[:13]
```


```python
list(itertools.repeat('hello', 5))
```


```python
list(itertools.accumulate([1,2,3,4]))
```


```python
list(itertools.chain('ABC', 'DEF'))
```


```python
list(itertools.compress('ABCDEF', [1,0,1,0,1,0]))
```


```python
list(itertools.dropwhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.takewhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.filterfalse(lambda x: x%2, range(10)))
```


```python
list(itertools.islice(range(20), 5))
```


```python
list(itertools.islice(range(20), 5, 15))
```


```python
list(itertools.islice(range(20), 5, 15, 2))
```


```python
list(itertools.permutations('ABC'))
```


```python
list(itertools.permutations('ABCD', 2))
```


```python
list(itertools.combinations('ABCD', 2))
```


```python
list(itertools.combinations_with_replacement('AB', 3))
```


```python
list(itertools.product('AB', repeat=2))
```


```python
list(itertools.groupby('AABBBCCDAA'))
```


```python
[list(g) for k, g in itertools.groupby('AABBBCCDAA')]
```


```python
list(itertools.starmap(pow, [(2,5), (3,2), (10,3)]))
```


```python
list(itertools.tee([1, 2, 3, 4], 2))[0]
```


```python
a, b = itertools.tee([1, 2, 3, 4], 2); list(a), list(b)
```


```python
list(itertools.zip_longest('AB', '1234', fillvalue='-'))
```


```python
data = [(1, 2), (3, 4)]; list(itertools.starmap(lambda x, y: x + y, data))
```


```python
list(itertools.accumulate(range(1, 6), lambda x, y: x*y))
```


```python
import itertools
```


```python
list(itertools.count(10, 2))[:13]
```


```python
list(itertools.cycle('ABCD'))[:14]
```


```python
list(itertools.repeat('hello', 5))
```


```python
list(itertools.accumulate([1,2,3,4]))
```


```python
list(itertools.chain('ABC', 'DEF'))
```


```python
list(itertools.compress('ABCDEF', [1,0,1,0,1,0]))
```


```python
list(itertools.dropwhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.takewhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.filterfalse(lambda x: x%2, range(10)))
```


```python
list(itertools.islice(range(20), 5))
```


```python
list(itertools.islice(range(20), 5, 15))
```


```python
list(itertools.islice(range(20), 5, 15, 2))
```


```python
list(itertools.permutations('ABC'))
```


```python
list(itertools.permutations('ABCD', 2))
```


```python
list(itertools.combinations('ABCD', 2))
```


```python
list(itertools.combinations_with_replacement('AB', 3))
```


```python
list(itertools.product('AB', repeat=2))
```


```python
list(itertools.groupby('AABBBCCDAA'))
```


```python
[list(g) for k, g in itertools.groupby('AABBBCCDAA')]
```


```python
list(itertools.starmap(pow, [(2,5), (3,2), (10,3)]))
```


```python
list(itertools.tee([1, 2, 3, 4], 2))[0]
```


```python
a, b = itertools.tee([1, 2, 3, 4], 2); list(a), list(b)
```


```python
list(itertools.zip_longest('AB', '1234', fillvalue='-'))
```


```python
data = [(1, 2), (3, 4)]; list(itertools.starmap(lambda x, y: x + y, data))
```


```python
list(itertools.accumulate(range(1, 6), lambda x, y: x*y))
```


```python
import itertools
```


```python
list(itertools.count(10, 2))[:14]
```


```python
list(itertools.cycle('ABCD'))[:10]
```


```python
list(itertools.repeat('hello', 5))
```


```python
list(itertools.accumulate([1,2,3,4]))
```


```python
list(itertools.chain('ABC', 'DEF'))
```


```python
list(itertools.compress('ABCDEF', [1,0,1,0,1,0]))
```


```python
list(itertools.dropwhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.takewhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.filterfalse(lambda x: x%2, range(10)))
```


```python
list(itertools.islice(range(20), 5))
```


```python
list(itertools.islice(range(20), 5, 15))
```


```python
list(itertools.islice(range(20), 5, 15, 2))
```


```python
list(itertools.permutations('ABC'))
```


```python
list(itertools.permutations('ABCD', 2))
```


```python
list(itertools.combinations('ABCD', 2))
```


```python
list(itertools.combinations_with_replacement('AB', 3))
```


```python
list(itertools.product('AB', repeat=2))
```


```python
list(itertools.groupby('AABBBCCDAA'))
```


```python
[list(g) for k, g in itertools.groupby('AABBBCCDAA')]
```


```python
list(itertools.starmap(pow, [(2,5), (3,2), (10,3)]))
```


```python
list(itertools.tee([1, 2, 3, 4], 2))[0]
```


```python
a, b = itertools.tee([1, 2, 3, 4], 2); list(a), list(b)
```


```python
list(itertools.zip_longest('AB', '1234', fillvalue='-'))
```


```python
data = [(1, 2), (3, 4)]; list(itertools.starmap(lambda x, y: x + y, data))
```


```python
list(itertools.accumulate(range(1, 6), lambda x, y: x*y))
```


```python
import itertools
```


```python
list(itertools.count(10, 2))[:10]
```


```python
list(itertools.cycle('ABCD'))[:11]
```


```python
list(itertools.repeat('hello', 5))
```


```python
list(itertools.accumulate([1,2,3,4]))
```


```python
list(itertools.chain('ABC', 'DEF'))
```


```python
list(itertools.compress('ABCDEF', [1,0,1,0,1,0]))
```


```python
list(itertools.dropwhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.takewhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.filterfalse(lambda x: x%2, range(10)))
```


```python
list(itertools.islice(range(20), 5))
```


```python
list(itertools.islice(range(20), 5, 15))
```


```python
list(itertools.islice(range(20), 5, 15, 2))
```


```python
list(itertools.permutations('ABC'))
```


```python
list(itertools.permutations('ABCD', 2))
```


```python
list(itertools.combinations('ABCD', 2))
```


```python
list(itertools.combinations_with_replacement('AB', 3))
```


```python
list(itertools.product('AB', repeat=2))
```


```python
list(itertools.groupby('AABBBCCDAA'))
```


```python
[list(g) for k, g in itertools.groupby('AABBBCCDAA')]
```


```python
list(itertools.starmap(pow, [(2,5), (3,2), (10,3)]))
```


```python
list(itertools.tee([1, 2, 3, 4], 2))[0]
```


```python
a, b = itertools.tee([1, 2, 3, 4], 2); list(a), list(b)
```


```python
list(itertools.zip_longest('AB', '1234', fillvalue='-'))
```


```python
data = [(1, 2), (3, 4)]; list(itertools.starmap(lambda x, y: x + y, data))
```


```python
list(itertools.accumulate(range(1, 6), lambda x, y: x*y))
```


```python
import itertools
```


```python
list(itertools.count(10, 2))[:11]
```


```python
list(itertools.cycle('ABCD'))[:12]
```


```python
list(itertools.repeat('hello', 5))
```


```python
list(itertools.accumulate([1,2,3,4]))
```


```python
list(itertools.chain('ABC', 'DEF'))
```


```python
list(itertools.compress('ABCDEF', [1,0,1,0,1,0]))
```


```python
list(itertools.dropwhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.takewhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.filterfalse(lambda x: x%2, range(10)))
```


```python
list(itertools.islice(range(20), 5))
```


```python
list(itertools.islice(range(20), 5, 15))
```


```python
list(itertools.islice(range(20), 5, 15, 2))
```


```python
list(itertools.permutations('ABC'))
```


```python
list(itertools.permutations('ABCD', 2))
```


```python
list(itertools.combinations('ABCD', 2))
```


```python
list(itertools.combinations_with_replacement('AB', 3))
```


```python
list(itertools.product('AB', repeat=2))
```


```python
list(itertools.groupby('AABBBCCDAA'))
```


```python
[list(g) for k, g in itertools.groupby('AABBBCCDAA')]
```


```python
list(itertools.starmap(pow, [(2,5), (3,2), (10,3)]))
```


```python
list(itertools.tee([1, 2, 3, 4], 2))[0]
```


```python
a, b = itertools.tee([1, 2, 3, 4], 2); list(a), list(b)
```


```python
list(itertools.zip_longest('AB', '1234', fillvalue='-'))
```


```python
data = [(1, 2), (3, 4)]; list(itertools.starmap(lambda x, y: x + y, data))
```


```python
list(itertools.accumulate(range(1, 6), lambda x, y: x*y))
```


```python
import itertools
```


```python
list(itertools.count(10, 2))[:12]
```


```python
list(itertools.cycle('ABCD'))[:13]
```


```python
list(itertools.repeat('hello', 5))
```


```python
list(itertools.accumulate([1,2,3,4]))
```


```python
list(itertools.chain('ABC', 'DEF'))
```


```python
list(itertools.compress('ABCDEF', [1,0,1,0,1,0]))
```


```python
list(itertools.dropwhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.takewhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.filterfalse(lambda x: x%2, range(10)))
```


```python
list(itertools.islice(range(20), 5))
```


```python
list(itertools.islice(range(20), 5, 15))
```


```python
list(itertools.islice(range(20), 5, 15, 2))
```


```python
list(itertools.permutations('ABC'))
```


```python
list(itertools.permutations('ABCD', 2))
```


```python
list(itertools.combinations('ABCD', 2))
```


```python
list(itertools.combinations_with_replacement('AB', 3))
```


```python
list(itertools.product('AB', repeat=2))
```


```python
list(itertools.groupby('AABBBCCDAA'))
```


```python
[list(g) for k, g in itertools.groupby('AABBBCCDAA')]
```


```python
list(itertools.starmap(pow, [(2,5), (3,2), (10,3)]))
```


```python
list(itertools.tee([1, 2, 3, 4], 2))[0]
```


```python
a, b = itertools.tee([1, 2, 3, 4], 2); list(a), list(b)
```


```python
list(itertools.zip_longest('AB', '1234', fillvalue='-'))
```


```python
data = [(1, 2), (3, 4)]; list(itertools.starmap(lambda x, y: x + y, data))
```


```python
list(itertools.accumulate(range(1, 6), lambda x, y: x*y))
```


```python
import itertools
```


```python
list(itertools.count(10, 2))[:13]
```


```python
list(itertools.cycle('ABCD'))[:14]
```


```python
list(itertools.repeat('hello', 5))
```


```python
list(itertools.accumulate([1,2,3,4]))
```


```python
list(itertools.chain('ABC', 'DEF'))
```


```python
list(itertools.compress('ABCDEF', [1,0,1,0,1,0]))
```


```python
list(itertools.dropwhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.takewhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.filterfalse(lambda x: x%2, range(10)))
```


```python
list(itertools.islice(range(20), 5))
```


```python
list(itertools.islice(range(20), 5, 15))
```


```python
list(itertools.islice(range(20), 5, 15, 2))
```


```python
list(itertools.permutations('ABC'))
```


```python
list(itertools.permutations('ABCD', 2))
```


```python
list(itertools.combinations('ABCD', 2))
```


```python
list(itertools.combinations_with_replacement('AB', 3))
```


```python
list(itertools.product('AB', repeat=2))
```


```python
list(itertools.groupby('AABBBCCDAA'))
```


```python
[list(g) for k, g in itertools.groupby('AABBBCCDAA')]
```


```python
list(itertools.starmap(pow, [(2,5), (3,2), (10,3)]))
```


```python
list(itertools.tee([1, 2, 3, 4], 2))[0]
```


```python
a, b = itertools.tee([1, 2, 3, 4], 2); list(a), list(b)
```


```python
list(itertools.zip_longest('AB', '1234', fillvalue='-'))
```


```python
data = [(1, 2), (3, 4)]; list(itertools.starmap(lambda x, y: x + y, data))
```


```python
list(itertools.accumulate(range(1, 6), lambda x, y: x*y))
```


```python
import itertools
```


```python
list(itertools.count(10, 2))[:14]
```


```python
list(itertools.cycle('ABCD'))[:10]
```


```python
list(itertools.repeat('hello', 5))
```


```python
list(itertools.accumulate([1,2,3,4]))
```


```python
list(itertools.chain('ABC', 'DEF'))
```


```python
list(itertools.compress('ABCDEF', [1,0,1,0,1,0]))
```


```python
list(itertools.dropwhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.takewhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.filterfalse(lambda x: x%2, range(10)))
```


```python
list(itertools.islice(range(20), 5))
```


```python
list(itertools.islice(range(20), 5, 15))
```


```python
list(itertools.islice(range(20), 5, 15, 2))
```


```python
list(itertools.permutations('ABC'))
```


```python
list(itertools.permutations('ABCD', 2))
```


```python
list(itertools.combinations('ABCD', 2))
```


```python
list(itertools.combinations_with_replacement('AB', 3))
```


```python
list(itertools.product('AB', repeat=2))
```


```python
list(itertools.groupby('AABBBCCDAA'))
```


```python
[list(g) for k, g in itertools.groupby('AABBBCCDAA')]
```


```python
list(itertools.starmap(pow, [(2,5), (3,2), (10,3)]))
```


```python
list(itertools.tee([1, 2, 3, 4], 2))[0]
```


```python
a, b = itertools.tee([1, 2, 3, 4], 2); list(a), list(b)
```


```python
list(itertools.zip_longest('AB', '1234', fillvalue='-'))
```


```python
data = [(1, 2), (3, 4)]; list(itertools.starmap(lambda x, y: x + y, data))
```


```python
list(itertools.accumulate(range(1, 6), lambda x, y: x*y))
```


```python
import itertools
```


```python
list(itertools.count(10, 2))[:10]
```


```python
list(itertools.cycle('ABCD'))[:11]
```


```python
list(itertools.repeat('hello', 5))
```


```python
list(itertools.accumulate([1,2,3,4]))
```


```python
list(itertools.chain('ABC', 'DEF'))
```


```python
list(itertools.compress('ABCDEF', [1,0,1,0,1,0]))
```


```python
list(itertools.dropwhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.takewhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.filterfalse(lambda x: x%2, range(10)))
```


```python
list(itertools.islice(range(20), 5))
```


```python
list(itertools.islice(range(20), 5, 15))
```


```python
list(itertools.islice(range(20), 5, 15, 2))
```


```python
list(itertools.permutations('ABC'))
```


```python
list(itertools.permutations('ABCD', 2))
```


```python
list(itertools.combinations('ABCD', 2))
```


```python
list(itertools.combinations_with_replacement('AB', 3))
```


```python
list(itertools.product('AB', repeat=2))
```


```python
list(itertools.groupby('AABBBCCDAA'))
```


```python
[list(g) for k, g in itertools.groupby('AABBBCCDAA')]
```


```python
list(itertools.starmap(pow, [(2,5), (3,2), (10,3)]))
```


```python
list(itertools.tee([1, 2, 3, 4], 2))[0]
```


```python
a, b = itertools.tee([1, 2, 3, 4], 2); list(a), list(b)
```


```python
list(itertools.zip_longest('AB', '1234', fillvalue='-'))
```


```python
data = [(1, 2), (3, 4)]; list(itertools.starmap(lambda x, y: x + y, data))
```


```python
list(itertools.accumulate(range(1, 6), lambda x, y: x*y))
```


```python
import itertools
```


```python
list(itertools.count(10, 2))[:11]
```


```python
list(itertools.cycle('ABCD'))[:12]
```


```python
list(itertools.repeat('hello', 5))
```


```python
list(itertools.accumulate([1,2,3,4]))
```


```python
list(itertools.chain('ABC', 'DEF'))
```


```python
list(itertools.compress('ABCDEF', [1,0,1,0,1,0]))
```


```python
list(itertools.dropwhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.takewhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.filterfalse(lambda x: x%2, range(10)))
```


```python
list(itertools.islice(range(20), 5))
```


```python
list(itertools.islice(range(20), 5, 15))
```


```python
list(itertools.islice(range(20), 5, 15, 2))
```


```python
list(itertools.permutations('ABC'))
```


```python
list(itertools.permutations('ABCD', 2))
```


```python
list(itertools.combinations('ABCD', 2))
```


```python
list(itertools.combinations_with_replacement('AB', 3))
```


```python
list(itertools.product('AB', repeat=2))
```


```python
list(itertools.groupby('AABBBCCDAA'))
```


```python
[list(g) for k, g in itertools.groupby('AABBBCCDAA')]
```


```python
list(itertools.starmap(pow, [(2,5), (3,2), (10,3)]))
```


```python
list(itertools.tee([1, 2, 3, 4], 2))[0]
```


```python
a, b = itertools.tee([1, 2, 3, 4], 2); list(a), list(b)
```


```python
list(itertools.zip_longest('AB', '1234', fillvalue='-'))
```


```python
data = [(1, 2), (3, 4)]; list(itertools.starmap(lambda x, y: x + y, data))
```


```python
list(itertools.accumulate(range(1, 6), lambda x, y: x*y))
```


```python
import itertools
```


```python
list(itertools.count(10, 2))[:12]
```


```python
list(itertools.cycle('ABCD'))[:13]
```


```python
list(itertools.repeat('hello', 5))
```


```python
list(itertools.accumulate([1,2,3,4]))
```


```python
list(itertools.chain('ABC', 'DEF'))
```


```python
list(itertools.compress('ABCDEF', [1,0,1,0,1,0]))
```


```python
list(itertools.dropwhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.takewhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.filterfalse(lambda x: x%2, range(10)))
```


```python
list(itertools.islice(range(20), 5))
```


```python
list(itertools.islice(range(20), 5, 15))
```


```python
list(itertools.islice(range(20), 5, 15, 2))
```


```python
list(itertools.permutations('ABC'))
```


```python
list(itertools.permutations('ABCD', 2))
```


```python
list(itertools.combinations('ABCD', 2))
```


```python
list(itertools.combinations_with_replacement('AB', 3))
```


```python
list(itertools.product('AB', repeat=2))
```


```python
list(itertools.groupby('AABBBCCDAA'))
```


```python
[list(g) for k, g in itertools.groupby('AABBBCCDAA')]
```


```python
list(itertools.starmap(pow, [(2,5), (3,2), (10,3)]))
```


```python
list(itertools.tee([1, 2, 3, 4], 2))[0]
```


```python
a, b = itertools.tee([1, 2, 3, 4], 2); list(a), list(b)
```


```python
list(itertools.zip_longest('AB', '1234', fillvalue='-'))
```


```python
data = [(1, 2), (3, 4)]; list(itertools.starmap(lambda x, y: x + y, data))
```


```python
list(itertools.accumulate(range(1, 6), lambda x, y: x*y))
```


```python
import itertools
```


```python
list(itertools.count(10, 2))[:13]
```


```python
list(itertools.cycle('ABCD'))[:14]
```


```python
list(itertools.repeat('hello', 5))
```


```python
list(itertools.accumulate([1,2,3,4]))
```


```python
list(itertools.chain('ABC', 'DEF'))
```


```python
list(itertools.compress('ABCDEF', [1,0,1,0,1,0]))
```


```python
list(itertools.dropwhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.takewhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.filterfalse(lambda x: x%2, range(10)))
```


```python
list(itertools.islice(range(20), 5))
```


```python
list(itertools.islice(range(20), 5, 15))
```


```python
list(itertools.islice(range(20), 5, 15, 2))
```


```python
list(itertools.permutations('ABC'))
```


```python
list(itertools.permutations('ABCD', 2))
```


```python
list(itertools.combinations('ABCD', 2))
```


```python
list(itertools.combinations_with_replacement('AB', 3))
```


```python
list(itertools.product('AB', repeat=2))
```


```python
list(itertools.groupby('AABBBCCDAA'))
```


```python
[list(g) for k, g in itertools.groupby('AABBBCCDAA')]
```


```python
list(itertools.starmap(pow, [(2,5), (3,2), (10,3)]))
```


```python
list(itertools.tee([1, 2, 3, 4], 2))[0]
```


```python
a, b = itertools.tee([1, 2, 3, 4], 2); list(a), list(b)
```


```python
list(itertools.zip_longest('AB', '1234', fillvalue='-'))
```


```python
data = [(1, 2), (3, 4)]; list(itertools.starmap(lambda x, y: x + y, data))
```


```python
list(itertools.accumulate(range(1, 6), lambda x, y: x*y))
```


```python
import itertools
```


```python
list(itertools.count(10, 2))[:14]
```


```python
list(itertools.cycle('ABCD'))[:10]
```


```python
list(itertools.repeat('hello', 5))
```


```python
list(itertools.accumulate([1,2,3,4]))
```


```python
list(itertools.chain('ABC', 'DEF'))
```


```python
list(itertools.compress('ABCDEF', [1,0,1,0,1,0]))
```


```python
list(itertools.dropwhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.takewhile(lambda x: x<5, [1,4,6,7,3]))
```


```python
list(itertools.filterfalse(lambda x: x%2, range(10)))
```


```python
list(itertools.islice(range(20), 5))
```


```python
list(itertools.islice(range(20), 5, 15))
```


---
**Score: 350**