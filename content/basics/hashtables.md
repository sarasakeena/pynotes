---
title: Hashtables
date: 2025-06-29
author: Your Name
cell_count: 80
score: 80
---

```
d = {}
```


```
d['a'] = 1
```


```
d['b'] = 2
```


```
print(d)
```


```
print(d['a'])
```


```
d['c'] = 3
```


```
d['a'] = 100
```


```
print(d)
```


```
del d['b']
```


```
print(d)
```


```
len(d)
```


```
d.get('a')
```


```
d.get('z', 'not found')
```


```
'c' in d
```


```
'z' in d
```


```
d.keys()
```


```
d.values()
```


```
d.items()
```


```
for key in d: print(key)
```


```
for value in d.values(): print(value)
```


```
for k, v in d.items(): print(k, v)
```


```
dict1 = {'x': 1, 'y': 2}
```


```
dict2 = {'y': 3, 'z': 4}
```


```
dict1.update(dict2)
```


```
print(dict1)
```


```
dict3 = dict1.copy()
```


```
print(dict3)
```


```
dict3.clear()
```


```
print(dict3)
```


```
dict4 = dict(a=1, b=2)
```


```
print(dict4)
```


```
dict5 = {i: i**2 for i in range(5)}
```


```
print(dict5)
```


```
tuple_key = (1, 2)
```


```
d[tuple_key] = 'tuple as key'
```


```
print(d)
```


```
try: print(d['missing'])
except KeyError: print('KeyError')
```


```
default = d.setdefault('new', 999)
```


```
print(d)
```


```
print(default)
```


```
d.pop('new')
```


```
print(d)
```


```
d.popitem()
```


```
print(d)
```


```
from collections import defaultdict
```


```
dd = defaultdict(int)
```


```
dd['a'] += 1
```


```
print(dd)
```


```
from collections import OrderedDict
```


```
od = OrderedDict()
```


```
od['a'] = 1
```


```
od['b'] = 2
```


```
print(od)
```


```
od.move_to_end('a')
```


```
print(od)
```


```
od.popitem(last=False)
```


```
print(od)
```


```
d = dict([('x', 10), ('y', 20)])
```


```
print(d)
```


```
zipped = zip(['a', 'b'], [1, 2])
```


```
d = dict(zipped)
```


```
print(d)
```


```
d = {chr(65+i): i for i in range(10)}
```


```
print(d)
```


```
d = {x: x+1 for x in range(10) if x % 2 == 0}
```


```
print(d)
```


```
hash('abc')
```


```
hash(123)
```


```
hash((1,2))
```


```
d = {'a': {'nested': 1}}
```


```
print(d['a']['nested'])
```


```
d['a']['nested'] += 1
```


```
print(d)
```


```
d = {i: chr(65+i) for i in range(5)}
```


```
for k in sorted(d): print(k, d[k])
```


```
inverse = {v: k for k, v in d.items()}
```


```
print(inverse)
```


```
import json
```


```
json_str = json.dumps(d)
```


```
print(json_str)
```


---
**Score: 80**