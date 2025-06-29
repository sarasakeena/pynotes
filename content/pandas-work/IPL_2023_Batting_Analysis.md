---
title: Ipl 2023 Batting Analysis
date: 2025-06-30
author: Your Name
cell_count: 8
score: 5
---

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```


```python
df = pd.read_csv(r'C:\datasets\ipl_2023_batting.csv')
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
      <th>Player</th>
      <th>Runs</th>
      <th>Matches</th>
      <th>Balls</th>
      <th>Strike Rate</th>
      <th>Average</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Shubman Gill</td>
      <td>890</td>
      <td>17</td>
      <td>550</td>
      <td>162.0</td>
      <td>59.3</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Faf du Plessis</td>
      <td>730</td>
      <td>14</td>
      <td>475</td>
      <td>153.7</td>
      <td>56.1</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Devdutt Padikkal</td>
      <td>421</td>
      <td>15</td>
      <td>360</td>
      <td>117.0</td>
      <td>35.1</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Virat Kohli</td>
      <td>639</td>
      <td>14</td>
      <td>432</td>
      <td>147.9</td>
      <td>53.3</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Ruturaj Gaikwad</td>
      <td>590</td>
      <td>13</td>
      <td>405</td>
      <td>145.6</td>
      <td>49.2</td>
    </tr>
    <tr>
      <th>5</th>
      <td>David Warner</td>
      <td>516</td>
      <td>14</td>
      <td>378</td>
      <td>136.5</td>
      <td>44.0</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Suryakumar Yadav</td>
      <td>605</td>
      <td>13</td>
      <td>370</td>
      <td>163.5</td>
      <td>50.4</td>
    </tr>
    <tr>
      <th>7</th>
      <td>MS Dhoni</td>
      <td>105</td>
      <td>10</td>
      <td>72</td>
      <td>145.8</td>
      <td>26.2</td>
    </tr>
  </tbody>
</table>
</div>




```python
df.info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 8 entries, 0 to 7
    Data columns (total 6 columns):
     #   Column       Non-Null Count  Dtype  
    ---  ------       --------------  -----  
     0   Player       8 non-null      object 
     1   Runs         8 non-null      int64  
     2   Matches      8 non-null      int64  
     3   Balls        8 non-null      int64  
     4   Strike Rate  8 non-null      float64
     5   Average      8 non-null      float64
    dtypes: float64(2), int64(3), object(1)
    memory usage: 516.0+ bytes
    


```python
df.sort_values("Runs", ascending=False)
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
      <th>Player</th>
      <th>Runs</th>
      <th>Matches</th>
      <th>Balls</th>
      <th>Strike Rate</th>
      <th>Average</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Shubman Gill</td>
      <td>890</td>
      <td>17</td>
      <td>550</td>
      <td>162.0</td>
      <td>59.3</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Faf du Plessis</td>
      <td>730</td>
      <td>14</td>
      <td>475</td>
      <td>153.7</td>
      <td>56.1</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Virat Kohli</td>
      <td>639</td>
      <td>14</td>
      <td>432</td>
      <td>147.9</td>
      <td>53.3</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Suryakumar Yadav</td>
      <td>605</td>
      <td>13</td>
      <td>370</td>
      <td>163.5</td>
      <td>50.4</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Ruturaj Gaikwad</td>
      <td>590</td>
      <td>13</td>
      <td>405</td>
      <td>145.6</td>
      <td>49.2</td>
    </tr>
    <tr>
      <th>5</th>
      <td>David Warner</td>
      <td>516</td>
      <td>14</td>
      <td>378</td>
      <td>136.5</td>
      <td>44.0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Devdutt Padikkal</td>
      <td>421</td>
      <td>15</td>
      <td>360</td>
      <td>117.0</td>
      <td>35.1</td>
    </tr>
    <tr>
      <th>7</th>
      <td>MS Dhoni</td>
      <td>105</td>
      <td>10</td>
      <td>72</td>
      <td>145.8</td>
      <td>26.2</td>
    </tr>
  </tbody>
</table>
</div>




```python
plt.figure(figsize=(10,6))
sns.barplot(x="Runs", y="Player", data=df.sort_values("Runs"), palette="crest")
plt.title("Top Run Scorers - IPL 2023")
plt.xlabel("Runs")
plt.ylabel("Player")
plt.grid(True)
plt.tight_layout()
plt.show()
```

    C:\Users\HP\AppData\Local\Temp\ipykernel_12800\3938584462.py:2: FutureWarning: 
    
    Passing `palette` without assigning `hue` is deprecated and will be removed in v0.14.0. Assign the `y` variable to `hue` and set `legend=False` for the same effect.
    
      sns.barplot(x="Runs", y="Player", data=df.sort_values("Runs"), palette="crest")
    


    
![png](/pynotes/images/IPL_2023_Batting_Analysis_4_1.png)
    



```python
df.loc[df["Strike Rate"].idxmax()]
```




    Player         Suryakumar Yadav
    Runs                        605
    Matches                      13
    Balls                       370
    Strike Rate               163.5
    Average                    50.4
    Name: 6, dtype: object




```python
plt.figure(figsize=(8,6))
sns.scatterplot(data=df, x="Strike Rate", y="Average", hue="Player", s=100)
plt.title("Strike Rate vs Batting Average")
plt.grid(True)
plt.show()

```


    
![png](/pynotes/images/IPL_2023_Batting_Analysis_6_0.png)
    



```python

```


---
**Score: 5**