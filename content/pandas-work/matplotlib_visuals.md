---
title: Matplotlib Visuals
date: 2025-06-30
author: Your Name
cell_count: 80
score: 80
---

```
import matplotlib.pyplot as plt
plt.plot([1, 2, 3, 4])
plt.show()
```


```
import matplotlib.pyplot as plt
plt.plot([1, 2, 3, 4], [1, 4, 9, 16])
plt.title('Plot 2: Line Plot')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.bar([1,2,3], [3,7,5])
plt.title('Plot 3: Bar Chart')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.barh([1,2,3], [3,7,5])
plt.title('Plot 4: Horizontal Bar')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.pie([30, 40, 30])
plt.title('Plot 5: Pie Chart')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.scatter([1,2,3,4], [4,3,2,1])
plt.title('Plot 6: Scatter Plot')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.hist([1,2,2,3,3,3,4,4,4,4])
plt.title('Plot 7: Histogram')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.linspace(0, 2*np.pi, 100)
y = np.sin(x)
plt.plot(x, y)
plt.title('Plot 8: Sine Wave')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.random.randn(100)
y = np.random.randn(100)
plt.scatter(x, y, alpha=0.5)
plt.title('Plot 9: Random Scatter')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.linspace(-10, 10, 100)
y = x**2
plt.plot(x, y)
plt.title('Plot 10: Parabola')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.boxplot([[1,2,5,7], [2,4,6,8]])
plt.title('Plot 11: Boxplot')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.random.rand(10)
y = np.random.rand(10)
colors = np.random.rand(10)
sizes = 1000 * np.random.rand(10)
plt.scatter(x, y, c=colors, s=sizes, alpha=0.3)
plt.title('Plot 12: Bubble Chart')
plt.show()
```


```
import matplotlib.pyplot as plt
labels = ['A', 'B', 'C', 'D']
values = [10, 20, 15, 5]
plt.bar(labels, values, color='green')
plt.title('Plot 13: Colored Bar Chart')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.linspace(0, 10, 100)
y1 = np.sin(x)
y2 = np.cos(x)
plt.plot(x, y1)
plt.plot(x, y2)
plt.legend(['sin(x)', 'cos(x)'])
plt.title('Plot 14: Multiple Lines')
plt.show()
```


```
import matplotlib.pyplot as plt
x = [1, 2, 3, 4]
y = [10, 20, 25, 30]
plt.step(x, y)
plt.title('Plot 15: Step Plot')
plt.show()
```


```
import matplotlib.pyplot as plt
x = [1, 2, 3, 4]
y = [10, 20, 25, 30]
plt.fill_between(x, y)
plt.title('Plot 16: Area Plot')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.linspace(0, 2*np.pi, 400)
y = np.sin(x**2)
plt.plot(x, y)
plt.title('Plot 17: Sine Squared')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.random.randn(1000)
plt.hist(x, bins=30)
plt.title('Plot 18: Normal Distribution')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.arange(0., 5., 0.2)
plt.plot(x, x, 'r--', x, x**2, 'bs', x, x**3, 'g^')
plt.title('Plot 19: Different Styles')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.linspace(0, 4*np.pi, 100)
y = np.sin(x)
plt.plot(x, y)
plt.grid(True)
plt.title('Plot 20: Grid Enabled')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.plot([1, 2, 3, 4])
plt.show()
```


```
import matplotlib.pyplot as plt
plt.plot([1, 2, 3, 4], [1, 4, 9, 16])
plt.title('Plot 22: Line Plot')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.bar([1,2,3], [3,7,5])
plt.title('Plot 23: Bar Chart')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.barh([1,2,3], [3,7,5])
plt.title('Plot 24: Horizontal Bar')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.pie([30, 40, 30])
plt.title('Plot 25: Pie Chart')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.scatter([1,2,3,4], [4,3,2,1])
plt.title('Plot 26: Scatter Plot')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.hist([1,2,2,3,3,3,4,4,4,4])
plt.title('Plot 27: Histogram')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.linspace(0, 2*np.pi, 100)
y = np.sin(x)
plt.plot(x, y)
plt.title('Plot 28: Sine Wave')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.random.randn(100)
y = np.random.randn(100)
plt.scatter(x, y, alpha=0.5)
plt.title('Plot 29: Random Scatter')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.linspace(-10, 10, 100)
y = x**2
plt.plot(x, y)
plt.title('Plot 30: Parabola')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.boxplot([[1,2,5,7], [2,4,6,8]])
plt.title('Plot 31: Boxplot')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.random.rand(10)
y = np.random.rand(10)
colors = np.random.rand(10)
sizes = 1000 * np.random.rand(10)
plt.scatter(x, y, c=colors, s=sizes, alpha=0.3)
plt.title('Plot 32: Bubble Chart')
plt.show()
```


```
import matplotlib.pyplot as plt
labels = ['A', 'B', 'C', 'D']
values = [10, 20, 15, 5]
plt.bar(labels, values, color='green')
plt.title('Plot 33: Colored Bar Chart')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.linspace(0, 10, 100)
y1 = np.sin(x)
y2 = np.cos(x)
plt.plot(x, y1)
plt.plot(x, y2)
plt.legend(['sin(x)', 'cos(x)'])
plt.title('Plot 34: Multiple Lines')
plt.show()
```


```
import matplotlib.pyplot as plt
x = [1, 2, 3, 4]
y = [10, 20, 25, 30]
plt.step(x, y)
plt.title('Plot 35: Step Plot')
plt.show()
```


```
import matplotlib.pyplot as plt
x = [1, 2, 3, 4]
y = [10, 20, 25, 30]
plt.fill_between(x, y)
plt.title('Plot 36: Area Plot')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.linspace(0, 2*np.pi, 400)
y = np.sin(x**2)
plt.plot(x, y)
plt.title('Plot 37: Sine Squared')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.random.randn(1000)
plt.hist(x, bins=30)
plt.title('Plot 38: Normal Distribution')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.arange(0., 5., 0.2)
plt.plot(x, x, 'r--', x, x**2, 'bs', x, x**3, 'g^')
plt.title('Plot 39: Different Styles')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.linspace(0, 4*np.pi, 100)
y = np.sin(x)
plt.plot(x, y)
plt.grid(True)
plt.title('Plot 40: Grid Enabled')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.plot([1, 2, 3, 4])
plt.show()
```


```
import matplotlib.pyplot as plt
plt.plot([1, 2, 3, 4], [1, 4, 9, 16])
plt.title('Plot 42: Line Plot')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.bar([1,2,3], [3,7,5])
plt.title('Plot 43: Bar Chart')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.barh([1,2,3], [3,7,5])
plt.title('Plot 44: Horizontal Bar')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.pie([30, 40, 30])
plt.title('Plot 45: Pie Chart')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.scatter([1,2,3,4], [4,3,2,1])
plt.title('Plot 46: Scatter Plot')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.hist([1,2,2,3,3,3,4,4,4,4])
plt.title('Plot 47: Histogram')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.linspace(0, 2*np.pi, 100)
y = np.sin(x)
plt.plot(x, y)
plt.title('Plot 48: Sine Wave')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.random.randn(100)
y = np.random.randn(100)
plt.scatter(x, y, alpha=0.5)
plt.title('Plot 49: Random Scatter')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.linspace(-10, 10, 100)
y = x**2
plt.plot(x, y)
plt.title('Plot 50: Parabola')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.boxplot([[1,2,5,7], [2,4,6,8]])
plt.title('Plot 51: Boxplot')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.random.rand(10)
y = np.random.rand(10)
colors = np.random.rand(10)
sizes = 1000 * np.random.rand(10)
plt.scatter(x, y, c=colors, s=sizes, alpha=0.3)
plt.title('Plot 52: Bubble Chart')
plt.show()
```


```
import matplotlib.pyplot as plt
labels = ['A', 'B', 'C', 'D']
values = [10, 20, 15, 5]
plt.bar(labels, values, color='green')
plt.title('Plot 53: Colored Bar Chart')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.linspace(0, 10, 100)
y1 = np.sin(x)
y2 = np.cos(x)
plt.plot(x, y1)
plt.plot(x, y2)
plt.legend(['sin(x)', 'cos(x)'])
plt.title('Plot 54: Multiple Lines')
plt.show()
```


```
import matplotlib.pyplot as plt
x = [1, 2, 3, 4]
y = [10, 20, 25, 30]
plt.step(x, y)
plt.title('Plot 55: Step Plot')
plt.show()
```


```
import matplotlib.pyplot as plt
x = [1, 2, 3, 4]
y = [10, 20, 25, 30]
plt.fill_between(x, y)
plt.title('Plot 56: Area Plot')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.linspace(0, 2*np.pi, 400)
y = np.sin(x**2)
plt.plot(x, y)
plt.title('Plot 57: Sine Squared')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.random.randn(1000)
plt.hist(x, bins=30)
plt.title('Plot 58: Normal Distribution')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.arange(0., 5., 0.2)
plt.plot(x, x, 'r--', x, x**2, 'bs', x, x**3, 'g^')
plt.title('Plot 59: Different Styles')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.linspace(0, 4*np.pi, 100)
y = np.sin(x)
plt.plot(x, y)
plt.grid(True)
plt.title('Plot 60: Grid Enabled')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.plot([1, 2, 3, 4])
plt.show()
```


```
import matplotlib.pyplot as plt
plt.plot([1, 2, 3, 4], [1, 4, 9, 16])
plt.title('Plot 62: Line Plot')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.bar([1,2,3], [3,7,5])
plt.title('Plot 63: Bar Chart')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.barh([1,2,3], [3,7,5])
plt.title('Plot 64: Horizontal Bar')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.pie([30, 40, 30])
plt.title('Plot 65: Pie Chart')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.scatter([1,2,3,4], [4,3,2,1])
plt.title('Plot 66: Scatter Plot')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.hist([1,2,2,3,3,3,4,4,4,4])
plt.title('Plot 67: Histogram')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.linspace(0, 2*np.pi, 100)
y = np.sin(x)
plt.plot(x, y)
plt.title('Plot 68: Sine Wave')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.random.randn(100)
y = np.random.randn(100)
plt.scatter(x, y, alpha=0.5)
plt.title('Plot 69: Random Scatter')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.linspace(-10, 10, 100)
y = x**2
plt.plot(x, y)
plt.title('Plot 70: Parabola')
plt.show()
```


```
import matplotlib.pyplot as plt
plt.boxplot([[1,2,5,7], [2,4,6,8]])
plt.title('Plot 71: Boxplot')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.random.rand(10)
y = np.random.rand(10)
colors = np.random.rand(10)
sizes = 1000 * np.random.rand(10)
plt.scatter(x, y, c=colors, s=sizes, alpha=0.3)
plt.title('Plot 72: Bubble Chart')
plt.show()
```


```
import matplotlib.pyplot as plt
labels = ['A', 'B', 'C', 'D']
values = [10, 20, 15, 5]
plt.bar(labels, values, color='green')
plt.title('Plot 73: Colored Bar Chart')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.linspace(0, 10, 100)
y1 = np.sin(x)
y2 = np.cos(x)
plt.plot(x, y1)
plt.plot(x, y2)
plt.legend(['sin(x)', 'cos(x)'])
plt.title('Plot 74: Multiple Lines')
plt.show()
```


```
import matplotlib.pyplot as plt
x = [1, 2, 3, 4]
y = [10, 20, 25, 30]
plt.step(x, y)
plt.title('Plot 75: Step Plot')
plt.show()
```


```
import matplotlib.pyplot as plt
x = [1, 2, 3, 4]
y = [10, 20, 25, 30]
plt.fill_between(x, y)
plt.title('Plot 76: Area Plot')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.linspace(0, 2*np.pi, 400)
y = np.sin(x**2)
plt.plot(x, y)
plt.title('Plot 77: Sine Squared')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.random.randn(1000)
plt.hist(x, bins=30)
plt.title('Plot 78: Normal Distribution')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.arange(0., 5., 0.2)
plt.plot(x, x, 'r--', x, x**2, 'bs', x, x**3, 'g^')
plt.title('Plot 79: Different Styles')
plt.show()
```


```
import matplotlib.pyplot as plt
import numpy as np
x = np.linspace(0, 4*np.pi, 100)
y = np.sin(x)
plt.plot(x, y)
plt.grid(True)
plt.title('Plot 80: Grid Enabled')
plt.show()
```


---
**Score: 80**