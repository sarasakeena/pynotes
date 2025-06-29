---
title: Amazon Price Tracker
date: 2025-06-30
author: Your Name
cell_count: 10
score: 10
---

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

```


```python
df = pd.read_csv(r'C:\Users\HP\Desktop\amazon_products.csv')
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
      <th>Product</th>
      <th>Price</th>
      <th>Rating</th>
      <th>Reviews</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Bluetooth Earphones</td>
      <td>1599</td>
      <td>4.2</td>
      <td>1532</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Smartphone Cover</td>
      <td>299</td>
      <td>4.0</td>
      <td>412</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Wireless Mouse</td>
      <td>649</td>
      <td>4.4</td>
      <td>845</td>
    </tr>
    <tr>
      <th>3</th>
      <td>LED Monitor</td>
      <td>10499</td>
      <td>4.5</td>
      <td>135</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Keyboard</td>
      <td>999</td>
      <td>4.1</td>
      <td>675</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Phone Tripod</td>
      <td>749</td>
      <td>4.3</td>
      <td>238</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Portable SSD</td>
      <td>5499</td>
      <td>4.7</td>
      <td>324</td>
    </tr>
    <tr>
      <th>7</th>
      <td>USB Hub</td>
      <td>799</td>
      <td>4.2</td>
      <td>147</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Webcam</td>
      <td>2399</td>
      <td>4.1</td>
      <td>510</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Laptop Stand</td>
      <td>1499</td>
      <td>4.3</td>
      <td>289</td>
    </tr>
  </tbody>
</table>
</div>




```python
df.info()
df.describe()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 10 entries, 0 to 9
    Data columns (total 4 columns):
     #   Column   Non-Null Count  Dtype  
    ---  ------   --------------  -----  
     0   Product  10 non-null     object 
     1   Price    10 non-null     int64  
     2   Rating   10 non-null     float64
     3   Reviews  10 non-null     int64  
    dtypes: float64(1), int64(2), object(1)
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
      <th>Price</th>
      <th>Rating</th>
      <th>Reviews</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>10.000000</td>
      <td>10.000000</td>
      <td>10.000000</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>2499.000000</td>
      <td>4.280000</td>
      <td>510.700000</td>
    </tr>
    <tr>
      <th>std</th>
      <td>3184.772798</td>
      <td>0.209762</td>
      <td>424.702262</td>
    </tr>
    <tr>
      <th>min</th>
      <td>299.000000</td>
      <td>4.000000</td>
      <td>135.000000</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>761.500000</td>
      <td>4.125000</td>
      <td>250.750000</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>1249.000000</td>
      <td>4.250000</td>
      <td>368.000000</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>2199.000000</td>
      <td>4.375000</td>
      <td>633.750000</td>
    </tr>
    <tr>
      <th>max</th>
      <td>10499.000000</td>
      <td>4.700000</td>
      <td>1532.000000</td>
    </tr>
  </tbody>
</table>
</div>




```python
deals = df[df["Price"] <= 1000].sort_values("Price")
deals
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
      <th>Product</th>
      <th>Price</th>
      <th>Rating</th>
      <th>Reviews</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1</th>
      <td>Smartphone Cover</td>
      <td>299</td>
      <td>4.0</td>
      <td>412</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Wireless Mouse</td>
      <td>649</td>
      <td>4.4</td>
      <td>845</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Phone Tripod</td>
      <td>749</td>
      <td>4.3</td>
      <td>238</td>
    </tr>
    <tr>
      <th>7</th>
      <td>USB Hub</td>
      <td>799</td>
      <td>4.2</td>
      <td>147</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Keyboard</td>
      <td>999</td>
      <td>4.1</td>
      <td>675</td>
    </tr>
  </tbody>
</table>
</div>




```python
top_reviews = df.sort_values("Reviews", ascending=False).head(5)
top_reviews
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
      <th>Product</th>
      <th>Price</th>
      <th>Rating</th>
      <th>Reviews</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Bluetooth Earphones</td>
      <td>1599</td>
      <td>4.2</td>
      <td>1532</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Wireless Mouse</td>
      <td>649</td>
      <td>4.4</td>
      <td>845</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Keyboard</td>
      <td>999</td>
      <td>4.1</td>
      <td>675</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Webcam</td>
      <td>2399</td>
      <td>4.1</td>
      <td>510</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Smartphone Cover</td>
      <td>299</td>
      <td>4.0</td>
      <td>412</td>
    </tr>
  </tbody>
</table>
</div>




```python
plt.figure(figsize=(10,6))
sns.scatterplot(data=df, x="Rating", y="Price", size="Reviews", hue="Product", legend=False)
plt.title("Product Price vs Rating")
plt.xlabel("Rating")
plt.ylabel("Price")
plt.grid(True)
plt.show()
```


    
![png](/pynotes/images/Amazon_Price_Tracker_5_0.png)
    



```python
## ⭐ Product Ratings Summary

We now analyze the overall product rating distribution.

```


```python
plt.figure(figsize=(8,5))
sns.histplot(df["Rating"], bins=5, kde=True, color='skyblue')
plt.title("Distribution of Product Ratings")
plt.xlabel("Rating")
plt.ylabel("Number of Products")
plt.grid(True)
plt.show()

```


```python
## 💸 Price Per Rating Point

Helps identify cost-effective products based on value-for-rating.

```


```python
df["Price_per_rating"] = df["Price"] / df["Rating"]
df.sort_values("Price_per_rating")

```


---
**Score: 10**