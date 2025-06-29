---
title: Strings
date: 2025-06-29
author: Your Name
cell_count: 85
score: 85
---

```python
sample = "PythonString1"
print("Original:", sample)
print("Upper:", sample.upper())
```

    Original: PythonString1
    Upper: PYTHONSTRING1
    


```python
sample = "PythonString1"
print("Original:", sample)
print("Upper:", sample.upper())
```

    Original: PythonString1
    Upper: PYTHONSTRING1
    


```python
sample = "PythonString2"
print("Lower:", sample.lower())
```

    Lower: pythonstring2
    


```python
sample = "PythonString4"
print("Reversed:", sample[::-1])
```

    Reversed: 4gnirtSnohtyP
    


```python
# Cell 5
sample = "PythonString5"
print("Slice 2–6:", sample[2:6])
```

    Slice 2–6: thon
    


```python
sample = "PythonString6"
print("Replace 'o' with '@':", sample.replace('o', '@'))
```

    Replace 'o' with '@': Pyth@nString6
    


```python
sample = "PythonString7"
print("Count 'n':", sample.count('n'))
```

    Count 'n': 2
    


```python
sample = "PythonString8"
print("Ends with 'g':", sample.endswith('g'))
```

    Ends with 'g': False
    


```python
sample = "PythonString9"
print("Starts with 'P':", sample.startswith('P')
```


      Cell In[9], line 2
        print("Starts with 'P':", sample.startswith('P')
                                                        ^
    SyntaxError: incomplete input
    



```python
sample = "PythonString10"
print("Title:", sample.title())
```

    Title: Pythonstring10
    


```python
sample = "PythonString11"
print("Swapcase:", sample.swapcase())
```

    Swapcase: pYTHONsTRING11
    


```python
sample = "PythonString12"
print("Center (20):", sample.center(20, "-"))
```

    Center (20): ---PythonString12---
    


```python
sample = "PythonString13"
print("Find 't':", sample.find('t'))
```

    Find 't': 2
    


```python

```


```python
sample = "PythonString14"
print("Zfill (20):", sample.zfill(20))
```

    Zfill (20): 000000PythonString14
    


```python
# Cell 15
sample = "PythonString15"
print("Encode:", sample.encode())
```

    Encode: b'PythonString15'
    


```python
sample = "PythonString16"
print("IsUpper:", sample.isupper())
```

    IsUpper: False
    


```python
sample = "PythonString16"
print("IsUpper:", sample.isupper())
```

    IsUpper: False
    


```python
sample = "PythonString17"
print("IsLower:", sample.islower())
```

    IsLower: False
    


```python
sample = "PythonString20"
print("Index of 'h':", sample.index('h'))
```

    Index of 'h': 3
    


```python
sample = "PythonString21"
print("Partition:", sample.partition("n"))
```

    Partition: ('Pytho', 'n', 'String21')
    


```python
sample = "PythonString23"
print("Ljust (20):", sample.ljust(20, "*"))
```

    Ljust (20): PythonString23******
    


```python
sample = "PythonString22"
print("Rjust (20):", sample.rjust(20, "*"))
```

    Rjust (20): ******PythonString22
    


```python
sample = "PythonString22"
print("Rjust (20):", sample.rjust(20, "*"))
```

    Rjust (20): ******PythonString22
    


```python
sample = "PythonString26"
print("Isdecimal:", sample.isdecimal())
```

    Isdecimal: False
    


```python
sample = "PythonString27"
print("Isidentifier:", sample.isidentifier())
```

    Isidentifier: True
    


```python
sample = "PythonString28"
print("Isidentifier:", sample.isidentifier())
```

    Isidentifier: True
    


```python
sample = "PythonString29"
print("Expandtabs:", "Python\tString".expandtabs(4))

```

    Expandtabs: Python  String
    


```python
sample = "PythonString30"
print("Translate (remove 'o'):", sample.translate(str.maketrans("", "", "o")))

```

    Translate (remove 'o'): PythnString30
    


```python
sample = "PythonString31"
print("Replace 'P' with 'X':", sample.replace("P", "X"))

```

    Replace 'P' with 'X': XythonString31
    


```python
# Cell 32
sample = "PythonString32"
print("Strip:", f"   {sample}   ".strip())
```

    Strip: PythonString32
    


```python
sample = "PythonString33"
print("Rstrip:", f"   {sample}   ".rstrip())
```

    Rstrip:    PythonString33
    


```python
sample = "PythonString34"
print("Lstrip:", f"   {sample}   ".lstrip())
```

    Lstrip: PythonString34   
    


```python
sample = "PythonString35"
print("Casefold:", sample.casefold())
```

    Casefold: pythonstring35
    


```python
sample = "PythonString36"
print("Count 't':", sample.count("t"))
```

    Count 't': 2
    


```python
sample = "PythonString37"
print("Find 'S':", sample.find("S"))
```

    Find 'S': 6
    


```python
sample = "PythonString38"
print("Rfind 'n':", sample.rfind("n"))
```

    Rfind 'n': 10
    


```python
sample = "PythonString39"
print("IsSpace:", "   ".isspace())

```

    IsSpace: True
    


```python
sample = "PythonString40"
print("IsTitle:", "Python Is Cool".istitle())

```

    IsTitle: True
    


```python
sample = "PythonString41"
print("Startswith 'Py':", sample.startswith("Py"))
```

    Startswith 'Py': True
    


```python
sample = "PythonString42"
print("Endswith '42':", sample.endswith("42"))

```

    Endswith '42': True
    


```python
sample = "PythonString43"
print("Length:", len(sample))

```

    Length: 14
    


```python
sample = "PythonString44"
print("Multiply * 2:", sample * 2)
```

    Multiply * 2: PythonString44PythonString44
    


```python
sample = "PythonString45"
print("In Operator ('on' in str):", "on" in sample)

```

    In Operator ('on' in str): True
    


```python
sample = "PythonString46"
print("Convert to List:", list(sample))
```

    Convert to List: ['P', 'y', 't', 'h', 'o', 'n', 'S', 't', 'r', 'i', 'n', 'g', '4', '6']
    


```python
sample = "PythonString46"
print("Convert to List:", list(sample))
```

    Convert to List: ['P', 'y', 't', 'h', 'o', 'n', 'S', 't', 'r', 'i', 'n', 'g', '4', '6']
    


```python
sample = "PythonString47"
print("Count 'i':", sample.count("i"))
```

    Count 'i': 1
    


```python
sample = "PythonString48"
print("Count 'g':", sample.count("g"))
```

    Count 'g': 1
    


```python
sample = "PythonString50"
print("Count 'z':", sample.count("z"))

```

    Count 'z': 0
    


```python
sample = "PythonString50"
print("Count 'z':", sample.count("z"))

```

    Count 'z': 0
    


```python
sample = "PythonString51"
print("All Upper:", sample.upper() == sample)
```

    All Upper: False
    


```python
sample = "PythonString52"
print("All Lower:", sample.lower() == sample)
```

    All Lower: False
    


```python
sample = "PythonString53"
print("Only alphabets:", sample.isalpha())

```

    Only alphabets: False
    


```python
sample = "PythonString54"
print("Only digits:", sample.isdigit())

```

    Only digits: False
    


```python
sample = "PythonString55"
print("Only alnum:", sample.isalnum())
```

    Only alnum: True
    


```python
sample = "PythonString56"
print("Replace 't' with '*':", sample.replace("t", "*"))
```

    Replace 't' with '*': Py*honS*ring56
    


```python
sample = "PythonString57"
print("Count of vowels:", sum(sample.count(v) for v in "aeiouAEIOU"))
```

    Count of vowels: 2
    


```python
sample = "PythonString58"
print("ASCII sum:", sum(ord(c) for c in sample))
```

    ASCII sum: 1382
    


```python
sample = "PythonString59"
print("Check 'String' in value:", "String" in sample)
```

    Check 'String' in value: True
    


```python
sample = "PythonString61"
print("Max char:", max(sample))
```

    Max char: y
    


```python
sample = "PythonString62"
print("Min char:", min(sample))
```

    Min char: 2
    


```python
sample = "PythonString63"
print("String multiplied:", sample * 3)
```

    String multiplied: PythonString63PythonString63PythonString63
    


```python
sample = "PythonString64"
print("First char:", sample[0])
```

    First char: P
    


```python
sample = "PythonString65"
print("Last char:", sample[-1])
```

    Last char: 5
    


```python
sample = "PythonString66"
print("Slice last 3:", sample[-3:])
```

    Slice last 3: g66
    


```python
sample = "PythonString67"
print("Slice middle:", sample[3:8])
```

    Slice middle: honSt
    


```python
sample = "PythonString68"
print("Slice even index:", sample[::2])
```

    Slice even index: PtoSrn6
    


```python
sample = "PythonString69"
print("Slice odd index:", sample[1::2])
```

    Slice odd index: yhntig9
    


```python
sample = "PythonString70"
print("Replace 'n' with 'Z':", sample.replace('n', 'Z'))
```

    Replace 'n' with 'Z': PythoZStriZg70
    


```python
sample = "PythonString71"
print("Make binary of each char:", [bin(ord(c)) for c in sample])

# Cell 72
```

    Make binary of each char: ['0b1010000', '0b1111001', '0b1110100', '0b1101000', '0b1101111', '0b1101110', '0b1010011', '0b1110100', '0b1110010', '0b1101001', '0b1101110', '0b1100111', '0b110111', '0b110001']
    


```python
ample = "PythonString72"
print("Find index of first vowel:", next((i for i, c in enumerate(sample) if c.lower() in 'aeiou'), -1))

```

    Find index of first vowel: 4
    


```python
sample = "PythonString73"
print("String after removing vowels:", ''.join([c for c in sample if c.lower() not in 'aeiou']))

```

    String after removing vowels: PythnStrng73
    


```python
sample = "PythonString74"
print("Reverse using loop:", ''.join(reversed(sample)))
```

    Reverse using loop: 47gnirtSnohtyP
    


```python
sample = "PythonString75"
print("String repeated with newlines:\n", '\n'.join([sample] * 3))
```

    String repeated with newlines:
     PythonString75
    PythonString75
    PythonString75
    


```python
sample = "PythonString76"
print("Is numeric:", sample.isnumeric())
```

    Is numeric: False
    


```python
sample = "PythonString77"
print("String in Title Case:", sample.title())
```

    String in Title Case: Pythonstring77
    


```python
sample = "PythonString78"
print("Count of 'Py':", sample.count('Py'))
```

    Count of 'Py': 1
    


```python
sample = "PythonString78"
print("Count of 'Py':", sample.count('Py'))
```

    Count of 'Py': 1
    


```python
sample = "PythonString80"
print("Number of uppercase letters:", sum(1 for c in sample if c.isupper()))

```

    Number of uppercase letters: 2
    


```python




sample = "PythonString80"
print("Number of uppercase letters:", sum(1 for c in sample if c.isupper()))

```

    Number of uppercase letters: 2
    


```python
sample = "PythonString81"
print("Number of lowercase letters:", sum(1 for c in sample if c.islower()))
```

    Number of lowercase letters: 10
    


```python

```


```python

```


```python

```


```python

```


---
**Score: 85**