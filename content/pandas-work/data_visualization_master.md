---
title: Data Visualization Master
date: 2025-06-29
author: Your Name
cell_count: 65
score: 65
---

```python
# Imports
import matplotlib.pyplot as plt
import seaborn as sns
import numpy as np
import pandas as pd
%matplotlib inline

```


```python
# Sample Data
x = [1, 2, 3, 4, 5]
y = [10, 15, 13, 17, 20]

```


```python
# DataFrame for seaborn
df = pd.DataFrame({
    'Day': ['Mon', 'Tue', 'Wed', 'Thu', 'Fri'],
    'Sales': [200, 300, 250, 400, 450],
    'Category': ['A', 'B', 'A', 'B', 'A']
})

```


```python
df.head()

```


```python
# Basic line plot
plt.plot(x, y)
plt.title("Simple Line Plot")
plt.show()

```


```python
# Line plot with labels
plt.plot(x, y)
plt.xlabel("X-axis")
plt.ylabel("Y-axis")
plt.title("Line Plot with Labels")
plt.show()

```


```python
# Line color and style
plt.plot(x, y, color='green', linestyle='--', marker='o')
plt.title("Styled Line Plot")
plt.show()

```


```python
# Line thickness
plt.plot(x, y, linewidth=2)
plt.title("Thick Line")
plt.show()

```


```python
# Multiple lines
y2 = [5, 10, 8, 12, 18]
plt.plot(x, y, label='First')
plt.plot(x, y2, label='Second')
plt.legend()
plt.show()

```


```python
# Grid
plt.plot(x, y)
plt.grid(True)
plt.title("Grid Example")
plt.show()

```


```python
# Markers
plt.plot(x, y, marker='^')
plt.title("Custom Markers")
plt.show()

```


```python
# Axis limits
plt.plot(x, y)
plt.ylim(0, 25)
plt.xlim(0, 6)
plt.title("Axis Limit Example")
plt.show()

```


```python
# Color
plt.plot(x, y, color='purple')
plt.title("Purple Line")
plt.show()

```


```python
# Subplot 1x2
plt.subplot(1, 2, 1)
plt.plot(x, y)
plt.title("Left")

plt.subplot(1, 2, 2)
plt.plot(x, y2)
plt.title("Right")

plt.tight_layout()
plt.show()

```


```python
# Bar chart
plt.bar(df['Day'], df['Sales'])
plt.title("Bar Chart")
plt.show()

```


```python
# Horizontal bar
plt.barh(df['Day'], df['Sales'], color='orange')
plt.title("Horizontal Bar")
plt.show()

```


```python
# Bar with color
colors = ['red', 'blue', 'green', 'purple', 'cyan']
plt.bar(df['Day'], df['Sales'], color=colors)
plt.title("Colored Bars")
plt.show()

```


```python
# Width
plt.bar(df['Day'], df['Sales'], width=0.5)
plt.title("Custom Width")
plt.show()

```


```python
# Grouped bars
labels = ['G1', 'G2', 'G3']
a = [20, 34, 30]
b = [25, 32, 34]

x = np.arange(len(labels))
width = 0.35

fig, ax = plt.subplots()
ax.bar(x - width/2, a, width, label='A')
ax.bar(x + width/2, b, width, label='B')
ax.set_xticks(x)
ax.set_xticklabels(labels)
ax.legend()
plt.title("Grouped Bar Chart")
plt.show()

```


```python
# Grouped bars
labels = ['G1', 'G2', 'G3']
a = [20, 34, 30]
b = [25, 32, 34]

x = np.arange(len(labels))
width = 0.35

fig, ax = plt.subplots()
ax.bar(x - width/2, a, width, label='A')
ax.bar(x + width/2, b, width, label='B')
ax.set_xticks(x)
ax.set_xticklabels(labels)
ax.legend()
plt.title("Grouped Bar Chart")
plt.show()

```


```python
# Annotated bar chart
bars = plt.bar(df['Day'], df['Sales'])
for bar in bars:
    yval = bar.get_height()
    plt.text(bar.get_x() + 0.1, yval + 10, yval)
plt.title("Annotated Bars")
plt.show()

```


```python
# Bar chart by category
sns.barplot(x='Day', y='Sales', hue='Category', data=df)
plt.title("Bar Chart with Seaborn")
plt.show()

```


```python
# Countplot
sns.countplot(x='Category', data=df)
plt.title("Countplot")
plt.show()

```


```python
# Bar chart with palette
sns.barplot(x='Day', y='Sales', data=df, palette='mako')
plt.title("Palette Mako")
plt.show()

```


```python
# Horizontal bar seaborn
sns.barplot(x='Sales', y='Day', data=df)
plt.title("Seaborn Horizontal Bar")
plt.show()

```


```python
# Simple pie
sizes = [30, 40, 20, 10]
labels = ['A', 'B', 'C', 'D']
plt.pie(sizes, labels=labels)
plt.title("Simple Pie")
plt.show()

```


```python
# Pie with explode
explode = (0.1, 0, 0, 0)
plt.pie(sizes, labels=labels, explode=explode, autopct='%1.1f%%')
plt.title("Exploded Pie")
plt.show()

```


```python
# Pie with shadow
plt.pie(sizes, labels=labels, shadow=True, startangle=140)
plt.title("Pie with Shadow")
plt.show()

```


```python
# Pie with colors
colors = ['gold', 'lightgreen', 'skyblue', 'lightcoral']
plt.pie(sizes, labels=labels, colors=colors)
plt.title("Colored Pie")
plt.show()

```


```python
# Pie with percentages
plt.pie(sizes, labels=labels, autopct='%1.2f%%')
plt.title("Pie Percentages")
plt.show()

```


```python
# Donut chart
plt.pie(sizes, labels=labels)
plt.gca().add_artist(plt.Circle((0,0), 0.5, color='white'))
plt.title("Donut Chart")
plt.show()

```


```python
# Pie + bar side by side
plt.subplot(1, 2, 1)
plt.pie(sizes, labels=labels)
plt.subplot(1, 2, 2)
plt.bar(labels, sizes)
plt.tight_layout()
plt.show()

```


```python
# Pie from dataframe
sales = df['Sales']
plt.pie(sales, labels=df['Day'], autopct='%1.1f%%')
plt.title("Sales Distribution Pie")
plt.show()

```


```python
# Pie with large dataset
labels = ['A', 'B', 'C', 'D', 'E']
values = [30, 25, 20, 15, 10]
plt.pie(values, labels=labels, autopct='%1.0f%%')
plt.title("Large Pie")
plt.show()

```


```python
# Pie chart rotated
plt.pie(sizes, labels=labels, startangle=90)
plt.title("Rotated Pie")
plt.show()

```


```python
# Histogram
data = np.random.randn(100)
plt.hist(data)
plt.title("Histogram")
plt.show()

```


```python
# Histogram bins
plt.hist(data, bins=20, color='teal')
plt.title("Histogram with Bins")
plt.show()

```


```python
# KDE plot
sns.kdeplot(data)
plt.title("KDE Plot")
plt.show()

```


```python
# KDE shade
sns.kdeplot(data, shade=True)
plt.title("KDE with Shade")
plt.show()

```


```python
# KDE + Histogram
sns.histplot(data, kde=True)
plt.title("Histogram with KDE")
plt.show()

```


```python
# Boxplot
tips = sns.load_dataset("tips")
sns.boxplot(x=tips['total_bill'])
plt.title("Boxplot of Total Bill")
plt.show()

```


```python
# Boxplot by category
sns.boxplot(x='day', y='total_bill', data=tips)
plt.title("Boxplot by Day")
plt.show()

```


```python
# Violin plot
sns.violinplot(x='day', y='total_bill', data=tips)
plt.title("Violin Plot")
plt.show()

```


```python
# Swarm plot
sns.swarmplot(x='day', y='total_bill', data=tips)
plt.title("Swarm Plot")
plt.show()
    
```


```python
# Combined swarm + violin
sns.violinplot(x='day', y='total_bill', data=tips, inner=None)
sns.swarmplot(x='day', y='total_bill', data=tips, color='k', alpha=0.5)
plt.title("Violin + Swarm")
plt.show()

```


```python
# Scatter plot
plt.scatter(df['Sales'], [1,2,3,4,5])
plt.title("Scatter Plot")
plt.show()

```


```python
# Scatter with color
colors = ['red', 'blue', 'green', 'orange', 'purple']
plt.scatter(df['Sales'], [1,2,3,4,5], c=colors)
plt.title("Colored Scatter")
plt.show()

```


```python
# Seaborn scatter
sns.scatterplot(x='Day', y='Sales', hue='Category', data=df)
plt.title("Seaborn Scatter")
plt.show()

```


```python
# Pairplot
sns.pairplot(tips)
plt.suptitle("Pairplot of Tips", y=1.02)
plt.show()

```


```python
# Pairplot
sns.pairplot(tips)
plt.suptitle("Pairplot of Tips", y=1.02)
plt.show()

```


```python
# Heatmap
corr = tips.corr()
sns.heatmap(corr, annot=True, cmap='coolwarm')
plt.title("Correlation Heatmap")
plt.show()

```


```python
# Heatmap without annotations
sns.heatmap(corr, cmap='YlGnBu')
plt.title("Heatmap No Annot")
plt.show()

```


```python
# Subplot 2x2
fig, axs = plt.subplots(2, 2)
axs[0, 0].plot(x, y)
axs[0, 1].bar(df['Day'], df['Sales'])
axs[1, 0].pie(sizes, labels=labels)
axs[1, 1].hist(data)
plt.tight_layout()
plt.show()

```


```python
# Dark theme
plt.style.use('dark_background')
plt.plot(x, y)
plt.title("Dark Theme Plot")
plt.show()

```


```python
# Reset style
plt.style.use('default')

```


```python
# Save figure
plt.plot(x, y)
plt.savefig("plot.png")
plt.title("Saved Plot")
plt.show()

```


```python
# 3D Surface Plot (if matplotlib 3D enabled)
from mpl_toolkits.mplot3d import Axes3D
fig = plt.figure()
ax = fig.add_subplot(111, projection='3d')
X, Y = np.meshgrid(np.linspace(-5, 5, 100), np.linspace(-5, 5, 100))
Z = np.sin(np.sqrt(X**2 + Y**2))
ax.plot_surface(X, Y, Z, cmap='viridis')
plt.title("3D Surface Plot")
plt.show()

```


```python
# Rug plot
sns.rugplot(data, height=0.3)
plt.title("Rug Plot")
plt.show()

```


```python
# Strip plot
sns.stripplot(x='day', y='total_bill', data=tips)
plt.title("Strip Plot")
plt.show()

```


```python
# Strip plot
sns.stripplot(x='day', y='total_bill', data=tips)
plt.title("Strip Plot")
plt.show()

```


```python
# Multi-hue bar plot
sns.barplot(x="day", y="tip", hue="sex", data=tips)
plt.title("Multi-Hue Bar")
plt.show()

```


```python
# Histogram + KDE + Style
sns.histplot(tips['total_bill'], kde=True, color='skyblue')
plt.title("Styled Hist + KDE")
plt.show()

```


```python
# Joint plot
sns.jointplot(x="total_bill", y="tip", data=tips, kind='reg')
plt.show()

```


```python
# Set figure size
plt.figure(figsize=(8, 4))
plt.plot(x, y)
plt.title("Custom Size")
plt.show()

```


```python

```


---
**Score: 65**