---
title: Student Analysis
date: 2025-06-29
author: Your Name
cell_count: 4
score: 0
---

```python
import pandas as pd
from io import StringIO

data = """Name,Math,Physics,Chemistry
Sara,88,92,85
Ali,76,81,79
Afia,95,90,96
John,55,60,58
Lina,66,74,70"""

df = pd.read_csv(StringIO(data))
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
      <th>Name</th>
      <th>Math</th>
      <th>Physics</th>
      <th>Chemistry</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Sara</td>
      <td>88</td>
      <td>92</td>
      <td>85</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Ali</td>
      <td>76</td>
      <td>81</td>
      <td>79</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Afia</td>
      <td>95</td>
      <td>90</td>
      <td>96</td>
    </tr>
    <tr>
      <th>3</th>
      <td>John</td>
      <td>55</td>
      <td>60</td>
      <td>58</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Lina</td>
      <td>66</td>
      <td>74</td>
      <td>70</td>
    </tr>
  </tbody>
</table>
</div>




```python
df['Total'] = df[['Math', 'Physics', 'Chemistry']].sum(axis=1)
df['Average'] = df['Total'] / 3
df['Result'] = df[['Math', 'Physics', 'Chemistry']].apply(lambda row: 'Pass' if (row >= 40).all() else 'Fail', axis=1)
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
      <th>Name</th>
      <th>Math</th>
      <th>Physics</th>
      <th>Chemistry</th>
      <th>Total</th>
      <th>Average</th>
      <th>Result</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Sara</td>
      <td>88</td>
      <td>92</td>
      <td>85</td>
      <td>265</td>
      <td>88.333333</td>
      <td>Pass</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Ali</td>
      <td>76</td>
      <td>81</td>
      <td>79</td>
      <td>236</td>
      <td>78.666667</td>
      <td>Pass</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Afia</td>
      <td>95</td>
      <td>90</td>
      <td>96</td>
      <td>281</td>
      <td>93.666667</td>
      <td>Pass</td>
    </tr>
    <tr>
      <th>3</th>
      <td>John</td>
      <td>55</td>
      <td>60</td>
      <td>58</td>
      <td>173</td>
      <td>57.666667</td>
      <td>Pass</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Lina</td>
      <td>66</td>
      <td>74</td>
      <td>70</td>
      <td>210</td>
      <td>70.000000</td>
      <td>Pass</td>
    </tr>
  </tbody>
</table>
</div>




```python
import matplotlib.pyplot as plt

df.plot(x='Name', y='Total', kind='bar', title='Total Marks by Student')
plt.show()

```


    
![png](/pynotes/images/student_analysis_2_0.png)
    



```python

```


---
**Score: 0**