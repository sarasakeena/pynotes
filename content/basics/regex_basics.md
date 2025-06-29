---
title: Regex Basics
date: 2025-06-29
author: Your Name
cell_count: 5
score: 5
---

```python
import re
```


```python
text = "Contact us at sara123@gmail.com or call +91-9876543210"

```


```python
email = re.findall(r"[a-zA-Z0-9._]+@[a-z]+\.[a-z]+", text)
print("Email:", email)

```

    Email: ['sara123@gmail.com']
    


```python
phone = re.findall(r"\+91-\d{10}", text)
print("Phone:", phone)
```

    Phone: ['+91-9876543210']
    


```python
Regex is used for pattern matching.
Useful in scraping, validation.

```


---
**Score: 5**