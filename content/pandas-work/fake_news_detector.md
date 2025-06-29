---
title: Fake News Detector
date: 2025-06-29
author: Your Name
cell_count: 6
score: 5
---

```python
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score

```


```python
data = {
    "text": [
        "NASA confirms water on Mars",
        "You won't believe what this actor did!",
        "Government passes new education bill",
        "Scientists find cure for cancer in lemons",
        "President addresses the nation",
        "Shocking! Aliens spotted in Delhi",
        "Stock market hits all-time high",
        "Celebrity marries alien in secret ceremony"
    ],
    "label": ["real", "fake", "real", "fake", "real", "fake", "real", "fake"]
}

df = pd.DataFrame(data)
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
      <th>text</th>
      <th>label</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>NASA confirms water on Mars</td>
      <td>real</td>
    </tr>
    <tr>
      <th>1</th>
      <td>You won't believe what this actor did!</td>
      <td>fake</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Government passes new education bill</td>
      <td>real</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Scientists find cure for cancer in lemons</td>
      <td>fake</td>
    </tr>
    <tr>
      <th>4</th>
      <td>President addresses the nation</td>
      <td>real</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Shocking! Aliens spotted in Delhi</td>
      <td>fake</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Stock market hits all-time high</td>
      <td>real</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Celebrity marries alien in secret ceremony</td>
      <td>fake</td>
    </tr>
  </tbody>
</table>
</div>




```python
X = df["text"]
y = df["label"]

vectorizer = TfidfVectorizer()
X_vec = vectorizer.fit_transform(X)

X_train, X_test, y_train, y_test = train_test_split(X_vec, y, test_size=0.25, random_state=42)

```


```python
model = LogisticRegression()
model.fit(X_train, y_train)

y_pred = model.predict(X_test)
print("Accuracy:", accuracy_score(y_test, y_pred))

```

    Accuracy: 0.0
    


```python
sample = ["Aliens built the pyramids"]
sample_vec = vectorizer.transform(sample)
print("Prediction:", model.predict(sample_vec)[0])

```

    Prediction: real
    


```python

```


---
**Score: 5**