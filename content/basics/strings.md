---
title: Strings
date: 2025-06-30
author: Your Name
cell_count: 87
score: 85
---

```python
s = 'hello world'
```


```python
print(len(s))
```

    11
    


```python
print(s.upper())
```

    HELLO WORLD
    


```python
print(s.lower())
```

    hello world
    


```python
print(s.capitalize())
```

    Hello world
    


```python
print(s.title())
```

    Hello World
    


```python
print(s.swapcase())
```

    HELLO WORLD
    


```python
print(s.startswith('hello'))
```

    True
    


```python
print(s.endswith('world'))
```

    True
    


```python
print(s.find('o'))
```

    4
    


```python
print(s.rfind('o'))
```

    7
    


```python
print(s.index('e'))
```

    1
    


```python
print(s.replace('world', 'python'))
```

    hello python
    


```python
print(s.split())
```

    ['hello', 'world']
    


```python
print('-'.join(['a', 'b', 'c']))
```

    a-b-c
    


```python
print(s.strip())
```

    hello world
    


```python
print('  test  '.lstrip())
```

    test  
    


```python
print('  test  '.rstrip())
```

      test
    


```python
print(s.count('l'))
```

    3
    


```python
print('abc123'.isalnum())
```

    True
    


```python
print('abc'.isalpha())
```

    True
    


```python
print('123'.isdigit())
```

    True
    


```python
print('abc'.islower())
```

    True
    


```python
print('ABC'.isupper())
```

    True
    


```python
print('Hello'.istitle())
```

    True
    


```python
print('   '.isspace())
```

    True
    


```python
print('abc'.center(10, '-'))
```

    ---abc----
    


```python
print('abc'.ljust(10, '*'))
```

    abc*******
    


```python
print('abc'.rjust(10, '*'))
```

    *******abc
    


```python
print('42'.zfill(5))
```

    00042
    


```python
print('a	b	c'.expandtabs(4))
```

    a   b   c
    


```python
print(f'Length of s is {len(s)}')
```

    Length of s is 11
    


```python
s2 = 'こんにちは'
print(s2.encode('utf-8'))
```

    b'\xe3\x81\x93\xe3\x82\x93\xe3\x81\xab\xe3\x81\xa1\xe3\x81\xaf'
    


```python
print(list('hello'))
```

    ['h', 'e', 'l', 'l', 'o']
    


```python
print(s[1:5])
```

    ello
    


```python
print(s[:5])
```

    hello
    


```python
print(s[6:])
```

    world
    


```python
print(s[::-1])
```

    dlrow olleh
    


```python
print('hello' * 3)
```

    hellohellohello
    


```python
print('lo' in s)
```

    True
    


```python
print('xyz' not in s)
```

    True
    


```python
print(any(char.isdigit() for char in s))
```

    False
    


```python
print(all(char.isalpha() for char in 'abc'))
```

    True
    


```python
print('python3'.partition('3'))
```

    ('python', '3', '')
    


```python
print('foo
bar
baz'.splitlines())
```


      Cell In[78], line 1
        print('foo
              ^
    SyntaxError: unterminated string literal (detected at line 1)
    



```python
print('1,2,3'.split(','))
```

    ['1', '2', '3']
    


```python
print('...hello...'.strip('.'))
```

    hello
    


```python
print('TestCase'.casefold())
```

    testcase
    


```python
print('ß'.lower())
```

    ß
    


```python
print('ß'.casefold())
```

    ss
    


```python
print(chr(97))
```

    a
    


```python
print(ord('a'))
```

    97
    


```python
print('hello'.__contains__('ell'))
```

    True
    


```python
print('python'.__getitem__(3))
```

    h
    


```python
print('hello'.__len__())
```

    5
    


```python
print('  abc  '.strip(' '))
```

    abc
    


```python
print('abcABC123'.isprintable())
```

    True
    


```python
print('abc
def'.isprintable())
```


      Cell In[91], line 1
        print('abc
              ^
    SyntaxError: unterminated string literal (detected at line 1)
    



```python
print('ABC'.rpartition('B'))
```

    ('A', 'B', 'C')
    


```python
print('hello'.rindex('l'))
```

    3
    


```python
print('hello'.isidentifier())
```

    True
    


```python
print('_var'.isidentifier())
```

    True
    


```python
print('snake_case'.replace('_', ' ').title().replace(' ', ''))
```

    SnakeCase
    


```python
print('abc'.encode())
```

    b'abc'
    


```python
print(b'abc'.decode())
```

    abc
    


```python
print('abcDEF'.translate(str.maketrans('abc', '123')))
```

    123DEF
    


```python
print('12345'.isdigit())
```

    True
    


```python
print('Ⅻ'.isnumeric())
```

    True
    


```python
print('one1two2'.translate(str.maketrans('', '', '0123456789')))
```

    onetwo
    


```python
print('  Hello  '.strip().lower())
```

    hello
    


```python
print('12'.rjust(5, '0'))
```

    00012
    


```python
print('abc'.rjust(10))
```

           abc
    


```python
print('xyxyxy'.replace('xy', 'z', 2))
```

    zzxy
    


```python
print('hello'.count('l', 1, 4))
```

    2
    


```python
print('abcdefghijklmno'.find('k', 5))
```

    10
    


```python
print('a-b-c'.rsplit('-', 1))
```

    ['a-b', 'c']
    


```python
print('a,b,c'.split(',', 2))
```

    ['a', 'b', 'c']
    


```python
print('abc'.rjust(6, '.'))
```

    ...abc
    


```python
print(','.join(map(str, range(5))))
```

    0,1,2,3,4
    


```python
print('abc'.__add__('123'))
```

    abc123
    


```python
print('abc' < 'abd')
```

    True
    


```python
print('Abc' < 'abc')
```

    True
    


```python
print('hello'.endswith(('o', 'd')))
```

    True
    


```python
print('hello'.startswith(('he', 'le')))
```

    True
    


```python

```


```python

```


```python

```


---
**Score: 85**