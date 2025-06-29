---
title: Hashtables
date: 2025-06-30
author: Your Name
cell_count: 80
score: 80
---

```python
d = {}
```


```python
d['a'] = 1
```


```python
d['b'] = 2
```


```python
print(d)
```

    {'a': 1, 'b': 2}
    


```python
print(d['a'])
```

    1
    


```python
d['c'] = 3
```


```python
d['a'] = 100
```


```python
print(d)
```

    {'a': 100, 'b': 2, 'c': 3}
    


```python
del d['b']
```


```python
print(d)
```

    {'a': 100, 'c': 3}
    


```python
len(d)
```




    2




```python
d.get('a')
```




    100




```python
d.get('z', 'not found')
```




    'not found'




```python
'c' in d
```




    True




```python
'z' in d
```




    False




```python
d.keys()
```




    dict_keys(['a', 'c'])




```python
d.values()
```




    dict_values([100, 3])




```python
d.items()
```




    dict_items([('a', 100), ('c', 3)])




```python
for key in d: print(key)
```

    a
    c
    


```python
for value in d.values(): print(value)
```

    100
    3
    


```python
for k, v in d.items(): print(k, v)
```

    a 100
    c 3
    


```python
dict1 = {'x': 1, 'y': 2}
```


```python
dict2 = {'y': 3, 'z': 4}
```


```python
dict1.update(dict2)
```


```python
print(dict1)
```

    {'x': 1, 'y': 3, 'z': 4}
    


```python
dict3 = dict1.copy()
```


```python
print(dict3)
```

    {'x': 1, 'y': 3, 'z': 4}
    


```python
dict3.clear()
```


```python
print(dict3)
```

    {}
    


```python
dict4 = dict(a=1, b=2)
```


```python
print(dict4)
```

    {'a': 1, 'b': 2}
    


```python
dict5 = {i: i**2 for i in range(5)}
```


```python
print(dict5)
```

    {0: 0, 1: 1, 2: 4, 3: 9, 4: 16}
    


```python
tuple_key = (1, 2)
```


```python
d[tuple_key] = 'tuple as key'
```


```python
print(d)
```

    {'a': 100, 'c': 3, (1, 2): 'tuple as key'}
    


```python
try: print(d['missing'])
except KeyError: print('KeyError')
```

    KeyError
    


```python
default = d.setdefault('new', 999)
```


```python
print(d)
```

    {'a': 100, 'c': 3, (1, 2): 'tuple as key', 'new': 999}
    


```python
print(default)
```

    999
    


```python
d.pop('new')
```




    999




```python
print(d)
```

    {'a': 100, 'c': 3, (1, 2): 'tuple as key'}
    


```python
d.popitem()
```




    ((1, 2), 'tuple as key')




```python
print(d)
```

    {'a': 100, 'c': 3}
    


```python
from collections import defaultdict
```


```python
dd = defaultdict(int)
```


```python
dd['a'] += 1
```


```python
print(dd)
```

    defaultdict(<class 'int'>, {'a': 1})
    


```python
from collections import OrderedDict
```


```python
od = OrderedDict()
```


```python
od['a'] = 1
```


```python
od['b'] = 2
```


```python
print(od)
```

    OrderedDict({'a': 1, 'b': 2})
    


```python
od.move_to_end('a')
```


```python
print(od)
```

    OrderedDict({'b': 2, 'a': 1})
    


```python
od.popitem(last=False)
```




    ('b', 2)




```python
print(od)
```

    OrderedDict({'a': 1})
    


```python
d = dict([('x', 10), ('y', 20)])
```


```python
print(d)
```

    {'x': 10, 'y': 20}
    


```python
zipped = zip(['a', 'b'], [1, 2])
```


```python
d = dict(zipped)
```


```python
print(d)
```

    {'a': 1, 'b': 2}
    


```python
d = {chr(65+i): i for i in range(10)}
```


```python
print(d)
```

    {'A': 0, 'B': 1, 'C': 2, 'D': 3, 'E': 4, 'F': 5, 'G': 6, 'H': 7, 'I': 8, 'J': 9}
    


```python
d = {x: x+1 for x in range(10) if x % 2 == 0}
```


```python
print(d)
```

    {0: 1, 2: 3, 4: 5, 6: 7, 8: 9}
    


```python
hash('abc')
```




    -6797330088782940123




```python
hash(123)
```




    123




```python
hash((1,2))
```




    -3550055125485641917




```python
d = {'a': {'nested': 1}}
```


```python
print(d['a']['nested'])
```

    1
    


```python
d['a']['nested'] += 1
```


```python
print(d)
```

    {'a': {'nested': 2}}
    


```python
d = {i: chr(65+i) for i in range(5)}
```


```python
for k in sorted(d): print(k, d[k])
```

    0 A
    1 B
    2 C
    3 D
    4 E
    


```python
inverse = {v: k for k, v in d.items()}
```


```python
print(inverse)
```

    {'A': 0, 'B': 1, 'C': 2, 'D': 3, 'E': 4}
    


```python
import json
```


```python
json_str = json.dumps(d)
```


```python
print(json_str)
```

    {"0": "A", "1": "B", "2": "C", "3": "D", "4": "E"}
    


---
**Score: 80**