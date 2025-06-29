---
title: Youtube Stats Analysis
date: 2025-06-30
author: Your Name
cell_count: 9
score: 5
---

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

```


```python
df = pd.read_csv(r'C:\datasets\youtube_stats.csv')
df

```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Title</th>
      <th>Views</th>
      <th>Likes</th>
      <th>Comments</th>
      <th>Duration</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Study Vlog - 1</td>
      <td>254300</td>
      <td>15300</td>
      <td>1893</td>
      <td>12:30</td>
    </tr>
    <tr>
      <th>1</th>
      <td>How to Focus Better</td>
      <td>431000</td>
      <td>28500</td>
      <td>3045</td>
      <td>10:45</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Python for Beginners</td>
      <td>891000</td>
      <td>76000</td>
      <td>4589</td>
      <td>25:00</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Room Tour 2025</td>
      <td>123000</td>
      <td>8200</td>
      <td>1203</td>
      <td>8:00</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Study With Me - 2hr Pomodoro</td>
      <td>710000</td>
      <td>54200</td>
      <td>3421</td>
      <td>120:00</td>
    </tr>
    <tr>
      <th>5</th>
      <td>My Daily Routine</td>
      <td>276500</td>
      <td>17400</td>
      <td>2145</td>
      <td>9:50</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Productive Morning Routine</td>
      <td>389000</td>
      <td>23800</td>
      <td>2801</td>
      <td>11:00</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Q&amp;A: Student Life</td>
      <td>194000</td>
      <td>12200</td>
      <td>1645</td>
      <td>13:20</td>
    </tr>
  </tbody>
</table>
</div>




```python
df.info()


```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 8 entries, 0 to 7
    Data columns (total 5 columns):
     #   Column    Non-Null Count  Dtype 
    ---  ------    --------------  ----- 
     0   Title     8 non-null      object
     1   Views     8 non-null      int64 
     2   Likes     8 non-null      int64 
     3   Comments  8 non-null      int64 
     4   Duration  8 non-null      object
    dtypes: int64(3), object(2)
    memory usage: 452.0+ bytes
    




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Views</th>
      <th>Likes</th>
      <th>Comments</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>8.000000</td>
      <td>8.000000</td>
      <td>8.000000</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>408600.000000</td>
      <td>29450.000000</td>
      <td>2592.750000</td>
    </tr>
    <tr>
      <th>std</th>
      <td>265469.142678</td>
      <td>23624.563488</td>
      <td>1097.964057</td>
    </tr>
    <tr>
      <th>min</th>
      <td>123000.000000</td>
      <td>8200.000000</td>
      <td>1203.000000</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>239225.000000</td>
      <td>14525.000000</td>
      <td>1831.000000</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>332750.000000</td>
      <td>20600.000000</td>
      <td>2473.000000</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>500750.000000</td>
      <td>34925.000000</td>
      <td>3139.000000</td>
    </tr>
    <tr>
      <th>max</th>
      <td>891000.000000</td>
      <td>76000.000000</td>
      <td>4589.000000</td>
    </tr>
  </tbody>
</table>
</div>




```python
df.describe()
```


```python
df.loc[df["Views"].idxmax()]

```




    Title       Python for Beginners
    Views                     891000
    Likes                      76000
    Comments                    4589
    Duration                   25:00
    Name: 2, dtype: object




```python
df["Engagement"] = (df["Likes"] + df["Comments"]) / df["Views"]
df.sort_values("Engagement", ascending=False)

```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Title</th>
      <th>Views</th>
      <th>Likes</th>
      <th>Comments</th>
      <th>Duration</th>
      <th>Engagement</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2</th>
      <td>Python for Beginners</td>
      <td>891000</td>
      <td>76000</td>
      <td>4589</td>
      <td>25:00</td>
      <td>0.090448</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Study With Me - 2hr Pomodoro</td>
      <td>710000</td>
      <td>54200</td>
      <td>3421</td>
      <td>120:00</td>
      <td>0.081156</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Room Tour 2025</td>
      <td>123000</td>
      <td>8200</td>
      <td>1203</td>
      <td>8:00</td>
      <td>0.076447</td>
    </tr>
    <tr>
      <th>1</th>
      <td>How to Focus Better</td>
      <td>431000</td>
      <td>28500</td>
      <td>3045</td>
      <td>10:45</td>
      <td>0.073190</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Q&amp;A: Student Life</td>
      <td>194000</td>
      <td>12200</td>
      <td>1645</td>
      <td>13:20</td>
      <td>0.071366</td>
    </tr>
    <tr>
      <th>5</th>
      <td>My Daily Routine</td>
      <td>276500</td>
      <td>17400</td>
      <td>2145</td>
      <td>9:50</td>
      <td>0.070687</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Productive Morning Routine</td>
      <td>389000</td>
      <td>23800</td>
      <td>2801</td>
      <td>11:00</td>
      <td>0.068383</td>
    </tr>
    <tr>
      <th>0</th>
      <td>Study Vlog - 1</td>
      <td>254300</td>
      <td>15300</td>
      <td>1893</td>
      <td>12:30</td>
      <td>0.067609</td>
    </tr>
  </tbody>
</table>
</div>




```python
plt.figure(figsize=(10,6))
sns.barplot(data=df.sort_values("Views", ascending=False), x="Views", y="Title", palette="mako")
plt.title(" YouTube Video Views")
plt.xlabel("Views")
plt.ylabel("Video Title")
plt.tight_layout()
plt.show()

```

    C:\Users\HP\AppData\Local\Temp\ipykernel_16092\1895900681.py:2: FutureWarning: 
    
    Passing `palette` without assigning `hue` is deprecated and will be removed in v0.14.0. Assign the `y` variable to `hue` and set `legend=False` for the same effect.
    
      sns.barplot(data=df.sort_values("Views", ascending=False), x="Views", y="Title", palette="mako")
    


    
![png](/pynotes/images/YouTube_Stats_Analysis_6_1.png)
    



```python
sns.lmplot(data=df, x="Likes", y="Comments", height=6, aspect=1.3)
plt.title("Likes vs Comments Relationship")

```




    Text(0.5, 1.0, 'Likes vs Comments Relationship')




    
![png](/pynotes/images/YouTube_Stats_Analysis_7_1.png)
    



```python

```


---
**Score: 5**