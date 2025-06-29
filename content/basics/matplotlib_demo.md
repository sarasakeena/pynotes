---
title: Matplotlib Demo
date: 2025-06-29
author: Your Name
cell_count: 8
score: 5
---

```python
import matplotlib.pyplot as plt

```


```python
x = [1, 2, 3, 4, 5]
y = [5, 7, 4, 6, 8]

```


```python
plt.plot(x, y, marker='o')
plt.title("Line Plot")
plt.xlabel("X")
plt.ylabel("Y")
plt.grid(True)
plt.show()
```


    
![png](/pynotes/images/matplotlib_demo_2_0.png)
    



```python
names = ["A", "B", "C"]
scores = [75, 88, 92]

```


```python
plt.bar(names, scores, color="orange")
plt.title("Bar Chart Example")
plt.show()
```


    
![png](/pynotes/images/matplotlib_demo_4_0.png)
    



```python
sizes = [30, 20, 50]
labels = ["Apples", "Bananas", "Cherries"]

```


```python
plt.pie(sizes, labels=labels, autopct='%1.1f%%', startangle=140)
plt.axis("equal")
plt.title("Pie Chart")
plt.show()
```


    
![png](/pynotes/images/matplotlib_demo_6_0.png)
    



```python

```


---
**Score: 5**