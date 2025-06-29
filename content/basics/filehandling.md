---
title: Filehandling
date: 2025-06-30
author: Your Name
cell_count: 48
score: 45
---

```python
# Writing a file
file = open("sara.txt", "w")
file.write("Sara\n")
file.close()


```


```python
# Reading the file
file = open("sara.txt", "r")
print(file.read())
file.close()


```

    Sara
    
    


```python
# Writing multiple lines
lines = ["Line 1\n", "Line 2\n", "Line 3\n"]
file = open("lines.txt", "w")
file.writelines(lines)
file.close()

```


```python
# Reading multiple lines
file = open("lines.txt", "r")
print(file.readlines())
file.close()

```

    ['Line 1\n', 'Line 2\n', 'Line 3\n']
    


```python
# Appending to a file
file = open("sara.txt", "a")
file.write("Keep shining!\n")
file.close()

```


```python
# Read after append
with open("sara.txt", "r") as f:
    print(f.read())

```

    Sara
    Keep shining!
    
    


```python
# Reading line by line
with open("lines.txt", "r") as f:
    for line in f:
        print("Line:", line.strip())

```

    Line: Line 1
    Line: Line 2
    Line: Line 3
    


```python
# Using with to write
with open("safe.txt", "w") as f:
    f.write("This is safe.")

```


```python
# File modes demo
modes = ['r', 'w', 'a', 'r+']
print("Modes:", modes)

```

    Modes: ['r', 'w', 'a', 'r+']
    


```python
# Try reading a non-existent file
try:
    open("nofile.txt", "r")
except FileNotFoundError as e:
    print("Error:", e)

```

    Error: [Errno 2] No such file or directory: 'nofile.txt'
    


```python
# 'r+' mode
with open("lines.txt", "r+") as f:
    print("Reading:", f.read())

```

    Reading: Line 1
    Line 2
    Line 3
    
    


```python
# 'a+' mode
with open("lines.txt", "a+") as f:
    f.write("Appended via a+\n")
    f.seek(0)
    print(f.read())

```

    Line 1
    Line 2
    Line 3
    Appended via a+
    
    


```python
# Checking if file is closed
f = open("temp.txt", "w")
f.write("Testing closed")
print("Closed?", f.closed)
f.close()
print("Closed after closing?", f.closed)

```

    Closed? False
    Closed after closing? True
    


```python
# File pointer position
with open("lines.txt", "r") as f:
    print("Pointer at:", f.tell())
    f.read(5)
    print("Pointer after read:", f.tell())

```

    Pointer at: 0
    Pointer after read: 5
    


```python
# Seek to start
with open("lines.txt", "r") as f:
    f.seek(0)
    print("Start:", f.read(6))

```

    Start: Line 1
    


```python
import os
print("Files in directory:", os.listdir())

```

    Files in directory: ['.ipynb_checkpoints', 'age-calculator.ipynb', 'basics_py.ipynb', 'bmi_calculator.ipynb', 'dictionary_operations.ipynb', 'filehandling.ipynb', 'functions.ipynb', 'iris_knn_classifier.ipynb', 'lines.txt', 'list_vs_tuple.ipynb', 'loops_and_conditions.ipynb', 'matplotlib_demo.ipynb', 'numpy_basics.ipynb', 'oop.ipynb', 'python_operators.ipynb', 'quiz_app.ipynb', 'regex_basics.ipynb', 'safe.txt', 'sample.ipynb', 'sara.txt', 'temp.txt', 'test.ipynb']
    


```python
# Check existence
print("Does sara.txt exist?", os.path.exists("sara.txt"))

```

    Does sara.txt exist? True
    


```python
# Get file size
print("Size of sara.txt:", os.path.getsize("sara.txt"))

```

    Size of sara.txt: 21
    


```python
# Rename file
os.rename("safe.txt", "renamed_safe.txt")
print("Renamed file!")

```

    Renamed file!
    


```python
# Delete file
if os.path.exists("temp.txt"):
    os.remove("temp.txt")
    print("Deleted temp.txt")

```

    Deleted temp.txt
    


```python
# Making new folder
if not os.path.exists("sara_folder"):
    os.mkdir("sara_folder")
    print("Folder created!")

```

    Folder created!
    


```python
# Writing inside folder
with open("sara_folder/newfile.txt", "w") as f:
    f.write("Inside folder!")

```


```python
# Reading from folder
with open("sara_folder/newfile.txt", "r") as f:
    print(f.read())

```

    Inside folder!
    


```python
# Removing folder
os.remove("sara_folder/newfile.txt")
os.rmdir("sara_folder")

```


```python
import csv
data = [["Name", "Score"], ["Sara", "1000"], ["Ali", "950"]]
with open("scores.csv", "w", newline="") as f:
    writer = csv.writer(f)
    writer.writerows(data)

```


```python
# Read CSV
with open("scores.csv", "r") as f:
    reader = csv.reader(f)
    for row in reader:
        print("CSV Row:", row)

```

    CSV Row: ['Name', 'Score']
    CSV Row: ['Sara', '1000']
    CSV Row: ['Ali', '950']
    


```python
# Read CSV
with open("scores.csv", "r") as f:
    reader = csv.reader(f)
    for row in reader:
        print("CSV Row:", row)

```

    CSV Row: ['Name', 'Score']
    CSV Row: ['Sara', '1000']
    CSV Row: ['Ali', '950']
    


```python
# Append to CSV
with open("scores.csv", "a", newline="") as f:
    writer = csv.writer(f)
    writer.writerow(["Afra", "890"])

```


```python
# Reading again
with open("scores.csv", "r") as f:
    print(f.read())

```

    Name,Score
    Sara,1000
    Ali,950
    Afra,890
    
    


```python
# Writing CSV using DictWriter
with open("dict_scores.csv", "w", newline="") as f:
    fieldnames = ["name", "marks"]
    writer = csv.DictWriter(f, fieldnames=fieldnames)
    writer.writeheader()
    writer.writerow({"name": "Sara", "marks": 99})

```


```python
# Reading Dict CSV
with open("dict_scores.csv", "r") as f:
    reader = csv.DictReader(f)
    for row in reader:
        print(row)

```

    {'name': 'Sara', 'marks': '99'}
    


```python
# CSV edge case: empty file
open("empty.csv", "w").close()

```


```python
# Read empty
with open("empty.csv", "r") as f:
    print("Empty:", f.read())

```

    Empty: 
    


```python
# Delete all CSVs
files = ["scores.csv", "dict_scores.csv", "empty.csv"]
for f in files:
    if os.path.exists(f):
        os.remove(f)

```


```python
import json
info = {"name": "Sara", "skills": ["Python", "ML"], "score": 999}
with open("info.json", "w") as f:
    json.dump(info, f)

```


```python
# Read JSON
with open("info.json", "r") as f:
    data = json.load(f)
    print("Loaded:", data)
    
```

    Loaded: {'name': 'Sara', 'skills': ['Python', 'ML'], 'score': 999}
    


```python
# Pretty JSON
with open("pretty.json", "w") as f:
    json.dump(info, f, indent=4)

```


```python
# Load pretty
with open("pretty.json", "r") as f:
    print(f.read())

```

    {
        "name": "Sara",
        "skills": [
            "Python",
            "ML"
        ],
        "score": 999
    }
    


```python
# Add to dict and dump
info["rank"] = 1
with open("info.json", "w") as f:
    json.dump(info, f)

```


```python
# Load after update
with open("info.json", "r") as f:
    print(json.load(f))

```

    {'name': 'Sara', 'skills': ['Python', 'ML'], 'score': 999, 'rank': 1}
    


```python
# Check key existence
print("Has rank?", "rank" in info)

```

    Has rank? True
    


```python
# Delete key
del info["rank"]
print("After delete:", info)

```

    After delete: {'name': 'Sara', 'skills': ['Python', 'ML'], 'score': 999}
    


```python
# Re-dump JSON
with open("info.json", "w") as f:
    json.dump(info, f)

```


```python
# Clean JSONs
for f in ["info.json", "pretty.json"]:
    os.remove(f)

```


```python
# Recap: file write & read
with open("recap.txt", "w") as f:
    f.write("done")

```


```python
# Read recap
with open("recap.txt", "r") as f:
    print(f.read())

```

    done
    


```python
# Check last files exist
print("Recap file?", os.path.exists("recap.txt"))

```

    Recap file? True
    


```python

```


---
**Score: 45**