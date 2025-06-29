---
title: Pandas&Sklearn
date: 2025-06-30
author: Your Name
cell_count: 450
score: 450
---

```python
# Cell 1 - Pandas: Dropping Columns
import pandas as pd
df0 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df0)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 2 - Scikit-learn: Feature Scaling
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X1 = np.array([[1], [2], [3], [4], [5]])
y1 = np.array([1, 4, 9, 16, 25])
X_train1, X_test1, y_train1, y_test1 = train_test_split(X1, y1, test_size=0.2)
model1 = LinearRegression()
model1.fit(X_train1, y_train1)
print(model1.predict(X_test1))
```

    [20.]
    


```python
# Cell 3 - Pandas: Creating DataFrames
import pandas as pd
df2 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df2)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 4 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X3 = np.array([[1], [2], [3], [4], [5]])
y3 = np.array([1, 4, 9, 16, 25])
X_train3, X_test3, y_train3, y_test3 = train_test_split(X3, y3, test_size=0.2)
model3 = LinearRegression()
model3.fit(X_train3, y_train3)
print(model3.predict(X_test3))
```

    [5.42857143]
    


```python
# Cell 5 - Pandas: Data Selection
import pandas as pd
df4 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df4)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 6 - Scikit-learn: SVM
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X5 = np.array([[1], [2], [3], [4], [5]])
y5 = np.array([1, 4, 9, 16, 25])
X_train5, X_test5, y_train5, y_test5 = train_test_split(X5, y5, test_size=0.2)
model5 = LinearRegression()
model5.fit(X_train5, y_train5)
print(model5.predict(X_test5))
```

    [20.]
    


```python
# Cell 7 - Pandas: Reading CSV
import pandas as pd
df6 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df6)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 8 - Scikit-learn: Pipeline
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X7 = np.array([[1], [2], [3], [4], [5]])
y7 = np.array([1, 4, 9, 16, 25])
X_train7, X_test7, y_train7, y_test7 = train_test_split(X7, y7, test_size=0.2)
model7 = LinearRegression()
model7.fit(X_train7, y_train7)
print(model7.predict(X_test7))
```

    [20.]
    


```python
# Cell 9 - Pandas: Creating DataFrames
import pandas as pd
df8 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df8)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 10 - Scikit-learn: Random Forest
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X9 = np.array([[1], [2], [3], [4], [5]])
y9 = np.array([1, 4, 9, 16, 25])
X_train9, X_test9, y_train9, y_test9 = train_test_split(X9, y9, test_size=0.2)
model9 = LinearRegression()
model9.fit(X_train9, y_train9)
print(model9.predict(X_test9))
```

    [5.42857143]
    


```python
# Cell 11 - Pandas: Reading CSV
import pandas as pd
df10 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df10)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 12 - Scikit-learn: Logistic Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X11 = np.array([[1], [2], [3], [4], [5]])
y11 = np.array([1, 4, 9, 16, 25])
X_train11, X_test11, y_train11, y_test11 = train_test_split(X11, y11, test_size=0.2)
model11 = LinearRegression()
model11.fit(X_train11, y_train11)
print(model11.predict(X_test11))
```

    [20.]
    


```python
# Cell 13 - Pandas: Reading CSV
import pandas as pd
df12 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df12)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 14 - Scikit-learn: Feature Scaling
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X13 = np.array([[1], [2], [3], [4], [5]])
y13 = np.array([1, 4, 9, 16, 25])
X_train13, X_test13, y_train13, y_test13 = train_test_split(X13, y13, test_size=0.2)
model13 = LinearRegression()
model13.fit(X_train13, y_train13)
print(model13.predict(X_test13))
```

    [5.42857143]
    


```python
# Cell 15 - Pandas: Adding Columns
import pandas as pd
df14 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df14)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 16 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X15 = np.array([[1], [2], [3], [4], [5]])
y15 = np.array([1, 4, 9, 16, 25])
X_train15, X_test15, y_train15, y_test15 = train_test_split(X15, y15, test_size=0.2)
model15 = LinearRegression()
model15.fit(X_train15, y_train15)
print(model15.predict(X_test15))
```

    [17.42857143]
    


```python
# Cell 17 - Pandas: Data Selection
import pandas as pd
df16 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df16)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 18 - Scikit-learn: Pipeline
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X17 = np.array([[1], [2], [3], [4], [5]])
y17 = np.array([1, 4, 9, 16, 25])
X_train17, X_test17, y_train17, y_test17 = train_test_split(X17, y17, test_size=0.2)
model17 = LinearRegression()
model17.fit(X_train17, y_train17)
print(model17.predict(X_test17))
```

    [17.42857143]
    


```python
# Cell 19 - Pandas: Descriptive Stats
import pandas as pd
df18 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df18)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 20 - Scikit-learn: Cross Validation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X19 = np.array([[1], [2], [3], [4], [5]])
y19 = np.array([1, 4, 9, 16, 25])
X_train19, X_test19, y_train19, y_test19 = train_test_split(X19, y19, test_size=0.2)
model19 = LinearRegression()
model19.fit(X_train19, y_train19)
print(model19.predict(X_test19))
```

    [5.42857143]
    


```python
# Cell 21 - Pandas: Sorting
import pandas as pd
df20 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df20)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 22 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X21 = np.array([[1], [2], [3], [4], [5]])
y21 = np.array([1, 4, 9, 16, 25])
X_train21, X_test21, y_train21, y_test21 = train_test_split(X21, y21, test_size=0.2)
model21 = LinearRegression()
model21.fit(X_train21, y_train21)
print(model21.predict(X_test21))
```

    [5.42857143]
    


```python
# Cell 23 - Pandas: Data Types
import pandas as pd
df22 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df22)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 24 - Scikit-learn: KNN
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X23 = np.array([[1], [2], [3], [4], [5]])
y23 = np.array([1, 4, 9, 16, 25])
X_train23, X_test23, y_train23, y_test23 = train_test_split(X23, y23, test_size=0.2)
model23 = LinearRegression()
model23.fit(X_train23, y_train23)
print(model23.predict(X_test23))
```

    [-4.]
    


```python
# Cell 25 - Pandas: Creating DataFrames
import pandas as pd
df24 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df24)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 26 - Scikit-learn: Pipeline
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X25 = np.array([[1], [2], [3], [4], [5]])
y25 = np.array([1, 4, 9, 16, 25])
X_train25, X_test25, y_train25, y_test25 = train_test_split(X25, y25, test_size=0.2)
model25 = LinearRegression()
model25.fit(X_train25, y_train25)
print(model25.predict(X_test25))
```

    [20.]
    


```python
# Cell 27 - Pandas: Data Selection
import pandas as pd
df26 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df26)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 28 - Scikit-learn: Train-Test Split
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X27 = np.array([[1], [2], [3], [4], [5]])
y27 = np.array([1, 4, 9, 16, 25])
X_train27, X_test27, y_train27, y_test27 = train_test_split(X27, y27, test_size=0.2)
model27 = LinearRegression()
model27.fit(X_train27, y_train27)
print(model27.predict(X_test27))
```

    [-4.]
    


```python
# Cell 29 - Pandas: Dropping Columns
import pandas as pd
df28 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df28)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 30 - Scikit-learn: Pipeline
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X29 = np.array([[1], [2], [3], [4], [5]])
y29 = np.array([1, 4, 9, 16, 25])
X_train29, X_test29, y_train29, y_test29 = train_test_split(X29, y29, test_size=0.2)
model29 = LinearRegression()
model29.fit(X_train29, y_train29)
print(model29.predict(X_test29))
```

    [20.]
    


```python
# Cell 31 - Pandas: Sorting
import pandas as pd
df30 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df30)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 32 - Scikit-learn: Train-Test Split
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X31 = np.array([[1], [2], [3], [4], [5]])
y31 = np.array([1, 4, 9, 16, 25])
X_train31, X_test31, y_train31, y_test31 = train_test_split(X31, y31, test_size=0.2)
model31 = LinearRegression()
model31.fit(X_train31, y_train31)
print(model31.predict(X_test31))
```

    [20.]
    


```python
# Cell 33 - Pandas: GroupBy
import pandas as pd
df32 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df32)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 34 - Scikit-learn: Random Forest
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X33 = np.array([[1], [2], [3], [4], [5]])
y33 = np.array([1, 4, 9, 16, 25])
X_train33, X_test33, y_train33, y_test33 = train_test_split(X33, y33, test_size=0.2)
model33 = LinearRegression()
model33.fit(X_train33, y_train33)
print(model33.predict(X_test33))
```

    [20.]
    


```python
# Cell 35 - Pandas: Creating DataFrames
import pandas as pd
df34 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df34)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 36 - Scikit-learn: Logistic Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X35 = np.array([[1], [2], [3], [4], [5]])
y35 = np.array([1, 4, 9, 16, 25])
X_train35, X_test35, y_train35, y_test35 = train_test_split(X35, y35, test_size=0.2)
model35 = LinearRegression()
model35.fit(X_train35, y_train35)
print(model35.predict(X_test35))
```

    [20.]
    


```python
# Cell 37 - Pandas: Reading CSV
import pandas as pd
df36 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df36)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 38 - Scikit-learn: Logistic Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X37 = np.array([[1], [2], [3], [4], [5]])
y37 = np.array([1, 4, 9, 16, 25])
X_train37, X_test37, y_train37, y_test37 = train_test_split(X37, y37, test_size=0.2)
model37 = LinearRegression()
model37.fit(X_train37, y_train37)
print(model37.predict(X_test37))
```

    [17.42857143]
    


```python
# Cell 39 - Pandas: Filtering Rows
import pandas as pd
df38 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df38)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 40 - Scikit-learn: Linear Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X39 = np.array([[1], [2], [3], [4], [5]])
y39 = np.array([1, 4, 9, 16, 25])
X_train39, X_test39, y_train39, y_test39 = train_test_split(X39, y39, test_size=0.2)
model39 = LinearRegression()
model39.fit(X_train39, y_train39)
print(model39.predict(X_test39))
```

    [-4.]
    


```python
# Cell 41 - Pandas: Reading CSV
import pandas as pd
df40 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df40)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 42 - Scikit-learn: Encoding Categorical Variables
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X41 = np.array([[1], [2], [3], [4], [5]])
y41 = np.array([1, 4, 9, 16, 25])
X_train41, X_test41, y_train41, y_test41 = train_test_split(X41, y41, test_size=0.2)
model41 = LinearRegression()
model41.fit(X_train41, y_train41)
print(model41.predict(X_test41))
```

    [5.42857143]
    


```python
# Cell 43 - Pandas: Adding Columns
import pandas as pd
df42 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df42)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 44 - Scikit-learn: Pipeline
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X43 = np.array([[1], [2], [3], [4], [5]])
y43 = np.array([1, 4, 9, 16, 25])
X_train43, X_test43, y_train43, y_test43 = train_test_split(X43, y43, test_size=0.2)
model43 = LinearRegression()
model43.fit(X_train43, y_train43)
print(model43.predict(X_test43))
```

    [17.42857143]
    


```python
# Cell 45 - Pandas: Creating DataFrames
import pandas as pd
df44 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df44)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 46 - Scikit-learn: Model Evaluation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X45 = np.array([[1], [2], [3], [4], [5]])
y45 = np.array([1, 4, 9, 16, 25])
X_train45, X_test45, y_train45, y_test45 = train_test_split(X45, y45, test_size=0.2)
model45 = LinearRegression()
model45.fit(X_train45, y_train45)
print(model45.predict(X_test45))
```

    [5.42857143]
    


```python
# Cell 47 - Pandas: Data Types
import pandas as pd
df46 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df46)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 48 - Scikit-learn: KNN
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X47 = np.array([[1], [2], [3], [4], [5]])
y47 = np.array([1, 4, 9, 16, 25])
X_train47, X_test47, y_train47, y_test47 = train_test_split(X47, y47, test_size=0.2)
model47 = LinearRegression()
model47.fit(X_train47, y_train47)
print(model47.predict(X_test47))
```

    [-4.]
    


```python
# Cell 49 - Pandas: Dropping Columns
import pandas as pd
df48 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df48)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 50 - Scikit-learn: Train-Test Split
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X49 = np.array([[1], [2], [3], [4], [5]])
y49 = np.array([1, 4, 9, 16, 25])
X_train49, X_test49, y_train49, y_test49 = train_test_split(X49, y49, test_size=0.2)
model49 = LinearRegression()
model49.fit(X_train49, y_train49)
print(model49.predict(X_test49))
```

    [-4.]
    


```python
# Cell 51 - Pandas: Descriptive Stats
import pandas as pd
df50 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df50)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 52 - Scikit-learn: Model Evaluation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X51 = np.array([[1], [2], [3], [4], [5]])
y51 = np.array([1, 4, 9, 16, 25])
X_train51, X_test51, y_train51, y_test51 = train_test_split(X51, y51, test_size=0.2)
model51 = LinearRegression()
model51.fit(X_train51, y_train51)
print(model51.predict(X_test51))
```

    [11.5]
    


```python
# Cell 53 - Pandas: Data Selection
import pandas as pd
df52 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df52)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 54 - Scikit-learn: Feature Scaling
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X53 = np.array([[1], [2], [3], [4], [5]])
y53 = np.array([1, 4, 9, 16, 25])
X_train53, X_test53, y_train53, y_test53 = train_test_split(X53, y53, test_size=0.2)
model53 = LinearRegression()
model53.fit(X_train53, y_train53)
print(model53.predict(X_test53))
```

    [20.]
    


```python
# Cell 55 - Pandas: Creating DataFrames
import pandas as pd
df54 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df54)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 56 - Scikit-learn: Logistic Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X55 = np.array([[1], [2], [3], [4], [5]])
y55 = np.array([1, 4, 9, 16, 25])
X_train55, X_test55, y_train55, y_test55 = train_test_split(X55, y55, test_size=0.2)
model55 = LinearRegression()
model55.fit(X_train55, y_train55)
print(model55.predict(X_test55))
```

    [5.42857143]
    


```python
# Cell 57 - Pandas: Creating DataFrames
import pandas as pd
df56 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df56)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 58 - Scikit-learn: SVM
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X57 = np.array([[1], [2], [3], [4], [5]])
y57 = np.array([1, 4, 9, 16, 25])
X_train57, X_test57, y_train57, y_test57 = train_test_split(X57, y57, test_size=0.2)
model57 = LinearRegression()
model57.fit(X_train57, y_train57)
print(model57.predict(X_test57))
```

    [-4.]
    


```python
# Cell 59 - Pandas: Sorting
import pandas as pd
df58 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df58)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 60 - Scikit-learn: Logistic Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X59 = np.array([[1], [2], [3], [4], [5]])
y59 = np.array([1, 4, 9, 16, 25])
X_train59, X_test59, y_train59, y_test59 = train_test_split(X59, y59, test_size=0.2)
model59 = LinearRegression()
model59.fit(X_train59, y_train59)
print(model59.predict(X_test59))
```

    [17.42857143]
    


```python
# Cell 61 - Pandas: Adding Columns
import pandas as pd
df60 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df60)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 62 - Scikit-learn: Train-Test Split
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X61 = np.array([[1], [2], [3], [4], [5]])
y61 = np.array([1, 4, 9, 16, 25])
X_train61, X_test61, y_train61, y_test61 = train_test_split(X61, y61, test_size=0.2)
model61 = LinearRegression()
model61.fit(X_train61, y_train61)
print(model61.predict(X_test61))
```

    [-4.]
    


```python
# Cell 63 - Pandas: Dropping Columns
import pandas as pd
df62 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df62)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 64 - Scikit-learn: Feature Scaling
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X63 = np.array([[1], [2], [3], [4], [5]])
y63 = np.array([1, 4, 9, 16, 25])
X_train63, X_test63, y_train63, y_test63 = train_test_split(X63, y63, test_size=0.2)
model63 = LinearRegression()
model63.fit(X_train63, y_train63)
print(model63.predict(X_test63))
```

    [20.]
    


```python
# Cell 65 - Pandas: Reading CSV
import pandas as pd
df64 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df64)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 66 - Scikit-learn: Train-Test Split
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X65 = np.array([[1], [2], [3], [4], [5]])
y65 = np.array([1, 4, 9, 16, 25])
X_train65, X_test65, y_train65, y_test65 = train_test_split(X65, y65, test_size=0.2)
model65 = LinearRegression()
model65.fit(X_train65, y_train65)
print(model65.predict(X_test65))
```

    [17.42857143]
    


```python
# Cell 67 - Pandas: Dropping Columns
import pandas as pd
df66 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df66)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 68 - Scikit-learn: Encoding Categorical Variables
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X67 = np.array([[1], [2], [3], [4], [5]])
y67 = np.array([1, 4, 9, 16, 25])
X_train67, X_test67, y_train67, y_test67 = train_test_split(X67, y67, test_size=0.2)
model67 = LinearRegression()
model67.fit(X_train67, y_train67)
print(model67.predict(X_test67))
```

    [-4.]
    


```python
# Cell 69 - Pandas: Filtering Rows
import pandas as pd
df68 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df68)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 70 - Scikit-learn: Model Evaluation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X69 = np.array([[1], [2], [3], [4], [5]])
y69 = np.array([1, 4, 9, 16, 25])
X_train69, X_test69, y_train69, y_test69 = train_test_split(X69, y69, test_size=0.2)
model69 = LinearRegression()
model69.fit(X_train69, y_train69)
print(model69.predict(X_test69))
```

    [-4.]
    


```python
# Cell 71 - Pandas: Merging DataFrames
import pandas as pd
df70 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df70)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 72 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X71 = np.array([[1], [2], [3], [4], [5]])
y71 = np.array([1, 4, 9, 16, 25])
X_train71, X_test71, y_train71, y_test71 = train_test_split(X71, y71, test_size=0.2)
model71 = LinearRegression()
model71.fit(X_train71, y_train71)
print(model71.predict(X_test71))
```

    [-4.]
    


```python
# Cell 73 - Pandas: Handling Missing Data
import pandas as pd
df72 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df72)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 74 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X73 = np.array([[1], [2], [3], [4], [5]])
y73 = np.array([1, 4, 9, 16, 25])
X_train73, X_test73, y_train73, y_test73 = train_test_split(X73, y73, test_size=0.2)
model73 = LinearRegression()
model73.fit(X_train73, y_train73)
print(model73.predict(X_test73))
```

    [11.5]
    


```python
# Cell 75 - Pandas: Adding Columns
import pandas as pd
df74 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df74)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 76 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X75 = np.array([[1], [2], [3], [4], [5]])
y75 = np.array([1, 4, 9, 16, 25])
X_train75, X_test75, y_train75, y_test75 = train_test_split(X75, y75, test_size=0.2)
model75 = LinearRegression()
model75.fit(X_train75, y_train75)
print(model75.predict(X_test75))
```

    [5.42857143]
    


```python
# Cell 77 - Pandas: Data Selection
import pandas as pd
df76 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df76)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 78 - Scikit-learn: Logistic Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X77 = np.array([[1], [2], [3], [4], [5]])
y77 = np.array([1, 4, 9, 16, 25])
X_train77, X_test77, y_train77, y_test77 = train_test_split(X77, y77, test_size=0.2)
model77 = LinearRegression()
model77.fit(X_train77, y_train77)
print(model77.predict(X_test77))
```

    [5.42857143]
    


```python
# Cell 79 - Pandas: Sorting
import pandas as pd
df78 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df78)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 80 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X79 = np.array([[1], [2], [3], [4], [5]])
y79 = np.array([1, 4, 9, 16, 25])
X_train79, X_test79, y_train79, y_test79 = train_test_split(X79, y79, test_size=0.2)
model79 = LinearRegression()
model79.fit(X_train79, y_train79)
print(model79.predict(X_test79))
```

    [5.42857143]
    


```python
# Cell 81 - Pandas: Data Selection
import pandas as pd
df80 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df80)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 82 - Scikit-learn: Linear Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X81 = np.array([[1], [2], [3], [4], [5]])
y81 = np.array([1, 4, 9, 16, 25])
X_train81, X_test81, y_train81, y_test81 = train_test_split(X81, y81, test_size=0.2)
model81 = LinearRegression()
model81.fit(X_train81, y_train81)
print(model81.predict(X_test81))
```

    [17.42857143]
    


```python
# Cell 83 - Pandas: Descriptive Stats
import pandas as pd
df82 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df82)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 84 - Scikit-learn: Random Forest
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X83 = np.array([[1], [2], [3], [4], [5]])
y83 = np.array([1, 4, 9, 16, 25])
X_train83, X_test83, y_train83, y_test83 = train_test_split(X83, y83, test_size=0.2)
model83 = LinearRegression()
model83.fit(X_train83, y_train83)
print(model83.predict(X_test83))
```

    [-4.]
    


```python
# Cell 85 - Pandas: Merging DataFrames
import pandas as pd
df84 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df84)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 86 - Scikit-learn: Train-Test Split
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X85 = np.array([[1], [2], [3], [4], [5]])
y85 = np.array([1, 4, 9, 16, 25])
X_train85, X_test85, y_train85, y_test85 = train_test_split(X85, y85, test_size=0.2)
model85 = LinearRegression()
model85.fit(X_train85, y_train85)
print(model85.predict(X_test85))
```

    [-4.]
    


```python
# Cell 87 - Pandas: Dropping Columns
import pandas as pd
df86 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df86)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 88 - Scikit-learn: Encoding Categorical Variables
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X87 = np.array([[1], [2], [3], [4], [5]])
y87 = np.array([1, 4, 9, 16, 25])
X_train87, X_test87, y_train87, y_test87 = train_test_split(X87, y87, test_size=0.2)
model87 = LinearRegression()
model87.fit(X_train87, y_train87)
print(model87.predict(X_test87))
```

    [20.]
    


```python
# Cell 89 - Pandas: Merging DataFrames
import pandas as pd
df88 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df88)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 90 - Scikit-learn: Model Evaluation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X89 = np.array([[1], [2], [3], [4], [5]])
y89 = np.array([1, 4, 9, 16, 25])
X_train89, X_test89, y_train89, y_test89 = train_test_split(X89, y89, test_size=0.2)
model89 = LinearRegression()
model89.fit(X_train89, y_train89)
print(model89.predict(X_test89))
```

    [17.42857143]
    


```python
# Cell 91 - Pandas: Sorting
import pandas as pd
df90 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df90)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 92 - Scikit-learn: Random Forest
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X91 = np.array([[1], [2], [3], [4], [5]])
y91 = np.array([1, 4, 9, 16, 25])
X_train91, X_test91, y_train91, y_test91 = train_test_split(X91, y91, test_size=0.2)
model91 = LinearRegression()
model91.fit(X_train91, y_train91)
print(model91.predict(X_test91))
```

    [5.42857143]
    


```python
# Cell 93 - Pandas: Descriptive Stats
import pandas as pd
df92 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df92)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 94 - Scikit-learn: Random Forest
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X93 = np.array([[1], [2], [3], [4], [5]])
y93 = np.array([1, 4, 9, 16, 25])
X_train93, X_test93, y_train93, y_test93 = train_test_split(X93, y93, test_size=0.2)
model93 = LinearRegression()
model93.fit(X_train93, y_train93)
print(model93.predict(X_test93))
```

    [5.42857143]
    


```python
# Cell 95 - Pandas: Creating DataFrames
import pandas as pd
df94 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df94)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 96 - Scikit-learn: KNN
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X95 = np.array([[1], [2], [3], [4], [5]])
y95 = np.array([1, 4, 9, 16, 25])
X_train95, X_test95, y_train95, y_test95 = train_test_split(X95, y95, test_size=0.2)
model95 = LinearRegression()
model95.fit(X_train95, y_train95)
print(model95.predict(X_test95))
```

    [5.42857143]
    


```python
# Cell 97 - Pandas: Reading CSV
import pandas as pd
df96 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df96)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 98 - Scikit-learn: Linear Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X97 = np.array([[1], [2], [3], [4], [5]])
y97 = np.array([1, 4, 9, 16, 25])
X_train97, X_test97, y_train97, y_test97 = train_test_split(X97, y97, test_size=0.2)
model97 = LinearRegression()
model97.fit(X_train97, y_train97)
print(model97.predict(X_test97))
```

    [5.42857143]
    


```python
# Cell 99 - Pandas: Descriptive Stats
import pandas as pd
df98 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df98)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 100 - Scikit-learn: Logistic Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X99 = np.array([[1], [2], [3], [4], [5]])
y99 = np.array([1, 4, 9, 16, 25])
X_train99, X_test99, y_train99, y_test99 = train_test_split(X99, y99, test_size=0.2)
model99 = LinearRegression()
model99.fit(X_train99, y_train99)
print(model99.predict(X_test99))
```

    [20.]
    


```python
# Cell 101 - Pandas: Descriptive Stats
import pandas as pd
df100 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df100)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 102 - Scikit-learn: Model Evaluation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X101 = np.array([[1], [2], [3], [4], [5]])
y101 = np.array([1, 4, 9, 16, 25])
X_train101, X_test101, y_train101, y_test101 = train_test_split(X101, y101, test_size=0.2)
model101 = LinearRegression()
model101.fit(X_train101, y_train101)
print(model101.predict(X_test101))
```

    [-4.]
    


```python
# Cell 103 - Pandas: Filtering Rows
import pandas as pd
df102 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df102)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 104 - Scikit-learn: Logistic Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X103 = np.array([[1], [2], [3], [4], [5]])
y103 = np.array([1, 4, 9, 16, 25])
X_train103, X_test103, y_train103, y_test103 = train_test_split(X103, y103, test_size=0.2)
model103 = LinearRegression()
model103.fit(X_train103, y_train103)
print(model103.predict(X_test103))
```

    [-4.]
    


```python
# Cell 105 - Pandas: Reading CSV
import pandas as pd
df104 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df104)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 106 - Scikit-learn: SVM
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X105 = np.array([[1], [2], [3], [4], [5]])
y105 = np.array([1, 4, 9, 16, 25])
X_train105, X_test105, y_train105, y_test105 = train_test_split(X105, y105, test_size=0.2)
model105 = LinearRegression()
model105.fit(X_train105, y_train105)
print(model105.predict(X_test105))
```

    [5.42857143]
    


```python
# Cell 107 - Pandas: Data Selection
import pandas as pd
df106 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df106)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 108 - Scikit-learn: Pipeline
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X107 = np.array([[1], [2], [3], [4], [5]])
y107 = np.array([1, 4, 9, 16, 25])
X_train107, X_test107, y_train107, y_test107 = train_test_split(X107, y107, test_size=0.2)
model107 = LinearRegression()
model107.fit(X_train107, y_train107)
print(model107.predict(X_test107))
```

    [20.]
    


```python
# Cell 109 - Pandas: Filtering Rows
import pandas as pd
df108 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df108)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 110 - Scikit-learn: Random Forest
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X109 = np.array([[1], [2], [3], [4], [5]])
y109 = np.array([1, 4, 9, 16, 25])
X_train109, X_test109, y_train109, y_test109 = train_test_split(X109, y109, test_size=0.2)
model109 = LinearRegression()
model109.fit(X_train109, y_train109)
print(model109.predict(X_test109))
```

    [11.5]
    


```python
# Cell 111 - Pandas: Dropping Columns
import pandas as pd
df110 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df110)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 112 - Scikit-learn: Linear Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X111 = np.array([[1], [2], [3], [4], [5]])
y111 = np.array([1, 4, 9, 16, 25])
X_train111, X_test111, y_train111, y_test111 = train_test_split(X111, y111, test_size=0.2)
model111 = LinearRegression()
model111.fit(X_train111, y_train111)
print(model111.predict(X_test111))
```

    [17.42857143]
    


```python
# Cell 113 - Pandas: Dropping Columns
import pandas as pd
df112 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df112)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 114 - Scikit-learn: KNN
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X113 = np.array([[1], [2], [3], [4], [5]])
y113 = np.array([1, 4, 9, 16, 25])
X_train113, X_test113, y_train113, y_test113 = train_test_split(X113, y113, test_size=0.2)
model113 = LinearRegression()
model113.fit(X_train113, y_train113)
print(model113.predict(X_test113))
```

    [-4.]
    


```python
# Cell 115 - Pandas: Data Selection
import pandas as pd
df114 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df114)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 116 - Scikit-learn: Model Evaluation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X115 = np.array([[1], [2], [3], [4], [5]])
y115 = np.array([1, 4, 9, 16, 25])
X_train115, X_test115, y_train115, y_test115 = train_test_split(X115, y115, test_size=0.2)
model115 = LinearRegression()
model115.fit(X_train115, y_train115)
print(model115.predict(X_test115))
```

    [17.42857143]
    


```python
# Cell 117 - Pandas: Data Types
import pandas as pd
df116 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df116)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 118 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X117 = np.array([[1], [2], [3], [4], [5]])
y117 = np.array([1, 4, 9, 16, 25])
X_train117, X_test117, y_train117, y_test117 = train_test_split(X117, y117, test_size=0.2)
model117 = LinearRegression()
model117.fit(X_train117, y_train117)
print(model117.predict(X_test117))
```

    [-4.]
    


```python
# Cell 119 - Pandas: Reading CSV
import pandas as pd
df118 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df118)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 120 - Scikit-learn: Train-Test Split
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X119 = np.array([[1], [2], [3], [4], [5]])
y119 = np.array([1, 4, 9, 16, 25])
X_train119, X_test119, y_train119, y_test119 = train_test_split(X119, y119, test_size=0.2)
model119 = LinearRegression()
model119.fit(X_train119, y_train119)
print(model119.predict(X_test119))
```

    [5.42857143]
    


```python
# Cell 121 - Pandas: Sorting
import pandas as pd
df120 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df120)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 122 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X121 = np.array([[1], [2], [3], [4], [5]])
y121 = np.array([1, 4, 9, 16, 25])
X_train121, X_test121, y_train121, y_test121 = train_test_split(X121, y121, test_size=0.2)
model121 = LinearRegression()
model121.fit(X_train121, y_train121)
print(model121.predict(X_test121))
```

    [17.42857143]
    


```python
# Cell 123 - Pandas: Sorting
import pandas as pd
df122 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df122)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 124 - Scikit-learn: Train-Test Split
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X123 = np.array([[1], [2], [3], [4], [5]])
y123 = np.array([1, 4, 9, 16, 25])
X_train123, X_test123, y_train123, y_test123 = train_test_split(X123, y123, test_size=0.2)
model123 = LinearRegression()
model123.fit(X_train123, y_train123)
print(model123.predict(X_test123))
```

    [11.5]
    


```python
# Cell 125 - Pandas: Filtering Rows
import pandas as pd
df124 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df124)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 126 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X125 = np.array([[1], [2], [3], [4], [5]])
y125 = np.array([1, 4, 9, 16, 25])
X_train125, X_test125, y_train125, y_test125 = train_test_split(X125, y125, test_size=0.2)
model125 = LinearRegression()
model125.fit(X_train125, y_train125)
print(model125.predict(X_test125))
```

    [-4.]
    


```python
# Cell 127 - Pandas: Filtering Rows
import pandas as pd
df126 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df126)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 128 - Scikit-learn: Model Evaluation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X127 = np.array([[1], [2], [3], [4], [5]])
y127 = np.array([1, 4, 9, 16, 25])
X_train127, X_test127, y_train127, y_test127 = train_test_split(X127, y127, test_size=0.2)
model127 = LinearRegression()
model127.fit(X_train127, y_train127)
print(model127.predict(X_test127))
```

    [17.42857143]
    


```python
# Cell 129 - Pandas: Creating DataFrames
import pandas as pd
df128 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df128)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 130 - Scikit-learn: Pipeline
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X129 = np.array([[1], [2], [3], [4], [5]])
y129 = np.array([1, 4, 9, 16, 25])
X_train129, X_test129, y_train129, y_test129 = train_test_split(X129, y129, test_size=0.2)
model129 = LinearRegression()
model129.fit(X_train129, y_train129)
print(model129.predict(X_test129))
```

    [17.42857143]
    


```python
# Cell 131 - Pandas: Reading CSV
import pandas as pd
df130 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df130)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 132 - Scikit-learn: Encoding Categorical Variables
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X131 = np.array([[1], [2], [3], [4], [5]])
y131 = np.array([1, 4, 9, 16, 25])
X_train131, X_test131, y_train131, y_test131 = train_test_split(X131, y131, test_size=0.2)
model131 = LinearRegression()
model131.fit(X_train131, y_train131)
print(model131.predict(X_test131))
```

    [-4.]
    


```python
# Cell 133 - Pandas: GroupBy
import pandas as pd
df132 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df132)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 134 - Scikit-learn: Feature Scaling
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X133 = np.array([[1], [2], [3], [4], [5]])
y133 = np.array([1, 4, 9, 16, 25])
X_train133, X_test133, y_train133, y_test133 = train_test_split(X133, y133, test_size=0.2)
model133 = LinearRegression()
model133.fit(X_train133, y_train133)
print(model133.predict(X_test133))
```

    [20.]
    


```python
# Cell 135 - Pandas: Filtering Rows
import pandas as pd
df134 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df134)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 136 - Scikit-learn: Encoding Categorical Variables
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X135 = np.array([[1], [2], [3], [4], [5]])
y135 = np.array([1, 4, 9, 16, 25])
X_train135, X_test135, y_train135, y_test135 = train_test_split(X135, y135, test_size=0.2)
model135 = LinearRegression()
model135.fit(X_train135, y_train135)
print(model135.predict(X_test135))
```

    [20.]
    


```python
# Cell 137 - Pandas: Adding Columns
import pandas as pd
df136 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df136)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 138 - Scikit-learn: Train-Test Split
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X137 = np.array([[1], [2], [3], [4], [5]])
y137 = np.array([1, 4, 9, 16, 25])
X_train137, X_test137, y_train137, y_test137 = train_test_split(X137, y137, test_size=0.2)
model137 = LinearRegression()
model137.fit(X_train137, y_train137)
print(model137.predict(X_test137))
```

    [17.42857143]
    


```python
# Cell 139 - Pandas: Reading CSV
import pandas as pd
df138 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df138)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 140 - Scikit-learn: Pipeline
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X139 = np.array([[1], [2], [3], [4], [5]])
y139 = np.array([1, 4, 9, 16, 25])
X_train139, X_test139, y_train139, y_test139 = train_test_split(X139, y139, test_size=0.2)
model139 = LinearRegression()
model139.fit(X_train139, y_train139)
print(model139.predict(X_test139))
```

    [11.5]
    


```python
# Cell 141 - Pandas: Merging DataFrames
import pandas as pd
df140 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df140)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 142 - Scikit-learn: Encoding Categorical Variables
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X141 = np.array([[1], [2], [3], [4], [5]])
y141 = np.array([1, 4, 9, 16, 25])
X_train141, X_test141, y_train141, y_test141 = train_test_split(X141, y141, test_size=0.2)
model141 = LinearRegression()
model141.fit(X_train141, y_train141)
print(model141.predict(X_test141))
```

    [11.5]
    


```python
# Cell 143 - Pandas: Sorting
import pandas as pd
df142 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df142)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 144 - Scikit-learn: Pipeline
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X143 = np.array([[1], [2], [3], [4], [5]])
y143 = np.array([1, 4, 9, 16, 25])
X_train143, X_test143, y_train143, y_test143 = train_test_split(X143, y143, test_size=0.2)
model143 = LinearRegression()
model143.fit(X_train143, y_train143)
print(model143.predict(X_test143))
```

    [11.5]
    


```python
# Cell 145 - Pandas: Data Types
import pandas as pd
df144 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df144)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 146 - Scikit-learn: Model Evaluation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X145 = np.array([[1], [2], [3], [4], [5]])
y145 = np.array([1, 4, 9, 16, 25])
X_train145, X_test145, y_train145, y_test145 = train_test_split(X145, y145, test_size=0.2)
model145 = LinearRegression()
model145.fit(X_train145, y_train145)
print(model145.predict(X_test145))
```

    [11.5]
    


```python
# Cell 147 - Pandas: Data Types
import pandas as pd
df146 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df146)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 148 - Scikit-learn: Logistic Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X147 = np.array([[1], [2], [3], [4], [5]])
y147 = np.array([1, 4, 9, 16, 25])
X_train147, X_test147, y_train147, y_test147 = train_test_split(X147, y147, test_size=0.2)
model147 = LinearRegression()
model147.fit(X_train147, y_train147)
print(model147.predict(X_test147))
```

    [17.42857143]
    


```python
# Cell 149 - Pandas: Sorting
import pandas as pd
df148 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df148)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 150 - Scikit-learn: Pipeline
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X149 = np.array([[1], [2], [3], [4], [5]])
y149 = np.array([1, 4, 9, 16, 25])
X_train149, X_test149, y_train149, y_test149 = train_test_split(X149, y149, test_size=0.2)
model149 = LinearRegression()
model149.fit(X_train149, y_train149)
print(model149.predict(X_test149))
```

    [-4.]
    


```python
# Cell 151 - Pandas: Creating DataFrames
import pandas as pd
df150 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df150)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 152 - Scikit-learn: Pipeline
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X151 = np.array([[1], [2], [3], [4], [5]])
y151 = np.array([1, 4, 9, 16, 25])
X_train151, X_test151, y_train151, y_test151 = train_test_split(X151, y151, test_size=0.2)
model151 = LinearRegression()
model151.fit(X_train151, y_train151)
print(model151.predict(X_test151))
```

    [17.42857143]
    


```python
# Cell 153 - Pandas: Reading CSV
import pandas as pd
df152 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df152)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 154 - Scikit-learn: Feature Scaling
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X153 = np.array([[1], [2], [3], [4], [5]])
y153 = np.array([1, 4, 9, 16, 25])
X_train153, X_test153, y_train153, y_test153 = train_test_split(X153, y153, test_size=0.2)
model153 = LinearRegression()
model153.fit(X_train153, y_train153)
print(model153.predict(X_test153))
```

    [20.]
    


```python
# Cell 155 - Pandas: Data Selection
import pandas as pd
df154 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df154)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 156 - Scikit-learn: Encoding Categorical Variables
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X155 = np.array([[1], [2], [3], [4], [5]])
y155 = np.array([1, 4, 9, 16, 25])
X_train155, X_test155, y_train155, y_test155 = train_test_split(X155, y155, test_size=0.2)
model155 = LinearRegression()
model155.fit(X_train155, y_train155)
print(model155.predict(X_test155))
```

    [20.]
    


```python
# Cell 157 - Pandas: Dropping Columns
import pandas as pd
df156 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df156)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 158 - Scikit-learn: KNN
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X157 = np.array([[1], [2], [3], [4], [5]])
y157 = np.array([1, 4, 9, 16, 25])
X_train157, X_test157, y_train157, y_test157 = train_test_split(X157, y157, test_size=0.2)
model157 = LinearRegression()
model157.fit(X_train157, y_train157)
print(model157.predict(X_test157))
```

    [-4.]
    


```python
# Cell 159 - Pandas: Data Selection
import pandas as pd
df158 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df158)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 160 - Scikit-learn: Pipeline
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X159 = np.array([[1], [2], [3], [4], [5]])
y159 = np.array([1, 4, 9, 16, 25])
X_train159, X_test159, y_train159, y_test159 = train_test_split(X159, y159, test_size=0.2)
model159 = LinearRegression()
model159.fit(X_train159, y_train159)
print(model159.predict(X_test159))
```

    [11.5]
    


```python
# Cell 161 - Pandas: Merging DataFrames
import pandas as pd
df160 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df160)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 162 - Scikit-learn: SVM
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X161 = np.array([[1], [2], [3], [4], [5]])
y161 = np.array([1, 4, 9, 16, 25])
X_train161, X_test161, y_train161, y_test161 = train_test_split(X161, y161, test_size=0.2)
model161 = LinearRegression()
model161.fit(X_train161, y_train161)
print(model161.predict(X_test161))
```

    [-4.]
    


```python
# Cell 163 - Pandas: Merging DataFrames
import pandas as pd
df162 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df162)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 164 - Scikit-learn: Logistic Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X163 = np.array([[1], [2], [3], [4], [5]])
y163 = np.array([1, 4, 9, 16, 25])
X_train163, X_test163, y_train163, y_test163 = train_test_split(X163, y163, test_size=0.2)
model163 = LinearRegression()
model163.fit(X_train163, y_train163)
print(model163.predict(X_test163))
```

    [5.42857143]
    


```python
# Cell 165 - Pandas: Filtering Rows
import pandas as pd
df164 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df164)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 166 - Scikit-learn: Pipeline
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X165 = np.array([[1], [2], [3], [4], [5]])
y165 = np.array([1, 4, 9, 16, 25])
X_train165, X_test165, y_train165, y_test165 = train_test_split(X165, y165, test_size=0.2)
model165 = LinearRegression()
model165.fit(X_train165, y_train165)
print(model165.predict(X_test165))
```

    [-4.]
    


```python
# Cell 167 - Pandas: Adding Columns
import pandas as pd
df166 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df166)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 168 - Scikit-learn: Linear Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X167 = np.array([[1], [2], [3], [4], [5]])
y167 = np.array([1, 4, 9, 16, 25])
X_train167, X_test167, y_train167, y_test167 = train_test_split(X167, y167, test_size=0.2)
model167 = LinearRegression()
model167.fit(X_train167, y_train167)
print(model167.predict(X_test167))
```

    [-4.]
    


```python
# Cell 169 - Pandas: Sorting
import pandas as pd
df168 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df168)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 170 - Scikit-learn: Train-Test Split
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X169 = np.array([[1], [2], [3], [4], [5]])
y169 = np.array([1, 4, 9, 16, 25])
X_train169, X_test169, y_train169, y_test169 = train_test_split(X169, y169, test_size=0.2)
model169 = LinearRegression()
model169.fit(X_train169, y_train169)
print(model169.predict(X_test169))
```

    [20.]
    


```python
# Cell 171 - Pandas: Adding Columns
import pandas as pd
df170 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df170)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 172 - Scikit-learn: Train-Test Split
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X171 = np.array([[1], [2], [3], [4], [5]])
y171 = np.array([1, 4, 9, 16, 25])
X_train171, X_test171, y_train171, y_test171 = train_test_split(X171, y171, test_size=0.2)
model171 = LinearRegression()
model171.fit(X_train171, y_train171)
print(model171.predict(X_test171))
```

    [11.5]
    


```python
# Cell 173 - Pandas: Reading CSV
import pandas as pd
df172 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df172)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 174 - Scikit-learn: Linear Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X173 = np.array([[1], [2], [3], [4], [5]])
y173 = np.array([1, 4, 9, 16, 25])
X_train173, X_test173, y_train173, y_test173 = train_test_split(X173, y173, test_size=0.2)
model173 = LinearRegression()
model173.fit(X_train173, y_train173)
print(model173.predict(X_test173))
```

    [-4.]
    


```python
# Cell 175 - Pandas: Adding Columns
import pandas as pd
df174 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df174)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 176 - Scikit-learn: KNN
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X175 = np.array([[1], [2], [3], [4], [5]])
y175 = np.array([1, 4, 9, 16, 25])
X_train175, X_test175, y_train175, y_test175 = train_test_split(X175, y175, test_size=0.2)
model175 = LinearRegression()
model175.fit(X_train175, y_train175)
print(model175.predict(X_test175))
```

    [-4.]
    


```python
# Cell 177 - Pandas: Merging DataFrames
import pandas as pd
df176 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df176)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 178 - Scikit-learn: KNN
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X177 = np.array([[1], [2], [3], [4], [5]])
y177 = np.array([1, 4, 9, 16, 25])
X_train177, X_test177, y_train177, y_test177 = train_test_split(X177, y177, test_size=0.2)
model177 = LinearRegression()
model177.fit(X_train177, y_train177)
print(model177.predict(X_test177))
```

    [5.42857143]
    


```python
# Cell 179 - Pandas: Adding Columns
import pandas as pd
df178 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df178)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 180 - Scikit-learn: Model Evaluation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X179 = np.array([[1], [2], [3], [4], [5]])
y179 = np.array([1, 4, 9, 16, 25])
X_train179, X_test179, y_train179, y_test179 = train_test_split(X179, y179, test_size=0.2)
model179 = LinearRegression()
model179.fit(X_train179, y_train179)
print(model179.predict(X_test179))
```

    [5.42857143]
    


```python
# Cell 181 - Pandas: Merging DataFrames
import pandas as pd
df180 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df180)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 182 - Scikit-learn: Pipeline
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X181 = np.array([[1], [2], [3], [4], [5]])
y181 = np.array([1, 4, 9, 16, 25])
X_train181, X_test181, y_train181, y_test181 = train_test_split(X181, y181, test_size=0.2)
model181 = LinearRegression()
model181.fit(X_train181, y_train181)
print(model181.predict(X_test181))
```

    [11.5]
    


```python
# Cell 183 - Pandas: Filtering Rows
import pandas as pd
df182 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df182)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 184 - Scikit-learn: Cross Validation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X183 = np.array([[1], [2], [3], [4], [5]])
y183 = np.array([1, 4, 9, 16, 25])
X_train183, X_test183, y_train183, y_test183 = train_test_split(X183, y183, test_size=0.2)
model183 = LinearRegression()
model183.fit(X_train183, y_train183)
print(model183.predict(X_test183))
```

    [17.42857143]
    


```python
# Cell 185 - Pandas: GroupBy
import pandas as pd
df184 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df184)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 186 - Scikit-learn: Train-Test Split
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X185 = np.array([[1], [2], [3], [4], [5]])
y185 = np.array([1, 4, 9, 16, 25])
X_train185, X_test185, y_train185, y_test185 = train_test_split(X185, y185, test_size=0.2)
model185 = LinearRegression()
model185.fit(X_train185, y_train185)
print(model185.predict(X_test185))
```

    [17.42857143]
    


```python
# Cell 187 - Pandas: Merging DataFrames
import pandas as pd
df186 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df186)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 188 - Scikit-learn: Encoding Categorical Variables
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X187 = np.array([[1], [2], [3], [4], [5]])
y187 = np.array([1, 4, 9, 16, 25])
X_train187, X_test187, y_train187, y_test187 = train_test_split(X187, y187, test_size=0.2)
model187 = LinearRegression()
model187.fit(X_train187, y_train187)
print(model187.predict(X_test187))
```

    [17.42857143]
    


```python
# Cell 189 - Pandas: Sorting
import pandas as pd
df188 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df188)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 190 - Scikit-learn: Encoding Categorical Variables
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X189 = np.array([[1], [2], [3], [4], [5]])
y189 = np.array([1, 4, 9, 16, 25])
X_train189, X_test189, y_train189, y_test189 = train_test_split(X189, y189, test_size=0.2)
model189 = LinearRegression()
model189.fit(X_train189, y_train189)
print(model189.predict(X_test189))
```

    [11.5]
    


```python
# Cell 191 - Pandas: Data Types
import pandas as pd
df190 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df190)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 192 - Scikit-learn: Feature Scaling
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X191 = np.array([[1], [2], [3], [4], [5]])
y191 = np.array([1, 4, 9, 16, 25])
X_train191, X_test191, y_train191, y_test191 = train_test_split(X191, y191, test_size=0.2)
model191 = LinearRegression()
model191.fit(X_train191, y_train191)
print(model191.predict(X_test191))
```

    [5.42857143]
    


```python
# Cell 193 - Pandas: Sorting
import pandas as pd
df192 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df192)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 194 - Scikit-learn: Train-Test Split
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X193 = np.array([[1], [2], [3], [4], [5]])
y193 = np.array([1, 4, 9, 16, 25])
X_train193, X_test193, y_train193, y_test193 = train_test_split(X193, y193, test_size=0.2)
model193 = LinearRegression()
model193.fit(X_train193, y_train193)
print(model193.predict(X_test193))
```

    [17.42857143]
    


```python
# Cell 195 - Pandas: GroupBy
import pandas as pd
df194 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df194)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 196 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X195 = np.array([[1], [2], [3], [4], [5]])
y195 = np.array([1, 4, 9, 16, 25])
X_train195, X_test195, y_train195, y_test195 = train_test_split(X195, y195, test_size=0.2)
model195 = LinearRegression()
model195.fit(X_train195, y_train195)
print(model195.predict(X_test195))
```

    [17.42857143]
    


```python
# Cell 197 - Pandas: Descriptive Stats
import pandas as pd
df196 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df196)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 198 - Scikit-learn: Cross Validation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X197 = np.array([[1], [2], [3], [4], [5]])
y197 = np.array([1, 4, 9, 16, 25])
X_train197, X_test197, y_train197, y_test197 = train_test_split(X197, y197, test_size=0.2)
model197 = LinearRegression()
model197.fit(X_train197, y_train197)
print(model197.predict(X_test197))
```

    [5.42857143]
    


```python
# Cell 199 - Pandas: Handling Missing Data
import pandas as pd
df198 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df198)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 200 - Scikit-learn: Logistic Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X199 = np.array([[1], [2], [3], [4], [5]])
y199 = np.array([1, 4, 9, 16, 25])
X_train199, X_test199, y_train199, y_test199 = train_test_split(X199, y199, test_size=0.2)
model199 = LinearRegression()
model199.fit(X_train199, y_train199)
print(model199.predict(X_test199))
```

    [11.5]
    


```python
# Cell 201 - Pandas: Handling Missing Data
import pandas as pd
df200 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df200)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 202 - Scikit-learn: Cross Validation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X201 = np.array([[1], [2], [3], [4], [5]])
y201 = np.array([1, 4, 9, 16, 25])
X_train201, X_test201, y_train201, y_test201 = train_test_split(X201, y201, test_size=0.2)
model201 = LinearRegression()
model201.fit(X_train201, y_train201)
print(model201.predict(X_test201))
```

    [20.]
    


```python
# Cell 203 - Pandas: GroupBy
import pandas as pd
df202 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df202)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 204 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X203 = np.array([[1], [2], [3], [4], [5]])
y203 = np.array([1, 4, 9, 16, 25])
X_train203, X_test203, y_train203, y_test203 = train_test_split(X203, y203, test_size=0.2)
model203 = LinearRegression()
model203.fit(X_train203, y_train203)
print(model203.predict(X_test203))
```

    [11.5]
    


```python
# Cell 205 - Pandas: Reading CSV
import pandas as pd
df204 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df204)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 206 - Scikit-learn: KNN
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X205 = np.array([[1], [2], [3], [4], [5]])
y205 = np.array([1, 4, 9, 16, 25])
X_train205, X_test205, y_train205, y_test205 = train_test_split(X205, y205, test_size=0.2)
model205 = LinearRegression()
model205.fit(X_train205, y_train205)
print(model205.predict(X_test205))
```

    [17.42857143]
    


```python
# Cell 207 - Pandas: Merging DataFrames
import pandas as pd
df206 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df206)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 208 - Scikit-learn: Linear Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X207 = np.array([[1], [2], [3], [4], [5]])
y207 = np.array([1, 4, 9, 16, 25])
X_train207, X_test207, y_train207, y_test207 = train_test_split(X207, y207, test_size=0.2)
model207 = LinearRegression()
model207.fit(X_train207, y_train207)
print(model207.predict(X_test207))
```

    [11.5]
    


```python
# Cell 209 - Pandas: Adding Columns
import pandas as pd
df208 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df208)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 210 - Scikit-learn: Encoding Categorical Variables
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X209 = np.array([[1], [2], [3], [4], [5]])
y209 = np.array([1, 4, 9, 16, 25])
X_train209, X_test209, y_train209, y_test209 = train_test_split(X209, y209, test_size=0.2)
model209 = LinearRegression()
model209.fit(X_train209, y_train209)
print(model209.predict(X_test209))
```

    [17.42857143]
    


```python
# Cell 211 - Pandas: GroupBy
import pandas as pd
df210 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df210)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 212 - Scikit-learn: Train-Test Split
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X211 = np.array([[1], [2], [3], [4], [5]])
y211 = np.array([1, 4, 9, 16, 25])
X_train211, X_test211, y_train211, y_test211 = train_test_split(X211, y211, test_size=0.2)
model211 = LinearRegression()
model211.fit(X_train211, y_train211)
print(model211.predict(X_test211))
```

    [-4.]
    


```python
# Cell 213 - Pandas: Sorting
import pandas as pd
df212 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df212)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 214 - Scikit-learn: Pipeline
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X213 = np.array([[1], [2], [3], [4], [5]])
y213 = np.array([1, 4, 9, 16, 25])
X_train213, X_test213, y_train213, y_test213 = train_test_split(X213, y213, test_size=0.2)
model213 = LinearRegression()
model213.fit(X_train213, y_train213)
print(model213.predict(X_test213))
```

    [20.]
    


```python
# Cell 215 - Pandas: Merging DataFrames
import pandas as pd
df214 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df214)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 216 - Scikit-learn: SVM
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X215 = np.array([[1], [2], [3], [4], [5]])
y215 = np.array([1, 4, 9, 16, 25])
X_train215, X_test215, y_train215, y_test215 = train_test_split(X215, y215, test_size=0.2)
model215 = LinearRegression()
model215.fit(X_train215, y_train215)
print(model215.predict(X_test215))
```

    [5.42857143]
    


```python
# Cell 217 - Pandas: Data Types
import pandas as pd
df216 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df216)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 218 - Scikit-learn: Model Evaluation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X217 = np.array([[1], [2], [3], [4], [5]])
y217 = np.array([1, 4, 9, 16, 25])
X_train217, X_test217, y_train217, y_test217 = train_test_split(X217, y217, test_size=0.2)
model217 = LinearRegression()
model217.fit(X_train217, y_train217)
print(model217.predict(X_test217))
```

    [-4.]
    


```python
# Cell 219 - Pandas: Handling Missing Data
import pandas as pd
df218 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df218)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 220 - Scikit-learn: SVM
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X219 = np.array([[1], [2], [3], [4], [5]])
y219 = np.array([1, 4, 9, 16, 25])
X_train219, X_test219, y_train219, y_test219 = train_test_split(X219, y219, test_size=0.2)
model219 = LinearRegression()
model219.fit(X_train219, y_train219)
print(model219.predict(X_test219))
```

    [5.42857143]
    


```python
# Cell 221 - Pandas: Handling Missing Data
import pandas as pd
df220 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df220)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 222 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X221 = np.array([[1], [2], [3], [4], [5]])
y221 = np.array([1, 4, 9, 16, 25])
X_train221, X_test221, y_train221, y_test221 = train_test_split(X221, y221, test_size=0.2)
model221 = LinearRegression()
model221.fit(X_train221, y_train221)
print(model221.predict(X_test221))
```

    [20.]
    


```python
# Cell 223 - Pandas: Adding Columns
import pandas as pd
df222 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df222)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 224 - Scikit-learn: Train-Test Split
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X223 = np.array([[1], [2], [3], [4], [5]])
y223 = np.array([1, 4, 9, 16, 25])
X_train223, X_test223, y_train223, y_test223 = train_test_split(X223, y223, test_size=0.2)
model223 = LinearRegression()
model223.fit(X_train223, y_train223)
print(model223.predict(X_test223))
```

    [20.]
    


```python
# Cell 225 - Pandas: GroupBy
import pandas as pd
df224 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df224)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 226 - Scikit-learn: Cross Validation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X225 = np.array([[1], [2], [3], [4], [5]])
y225 = np.array([1, 4, 9, 16, 25])
X_train225, X_test225, y_train225, y_test225 = train_test_split(X225, y225, test_size=0.2)
model225 = LinearRegression()
model225.fit(X_train225, y_train225)
print(model225.predict(X_test225))
```

    [11.5]
    


```python
# Cell 227 - Pandas: Filtering Rows
import pandas as pd
df226 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df226)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 228 - Scikit-learn: SVM
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X227 = np.array([[1], [2], [3], [4], [5]])
y227 = np.array([1, 4, 9, 16, 25])
X_train227, X_test227, y_train227, y_test227 = train_test_split(X227, y227, test_size=0.2)
model227 = LinearRegression()
model227.fit(X_train227, y_train227)
print(model227.predict(X_test227))
```

    [20.]
    


```python
# Cell 229 - Pandas: Creating DataFrames
import pandas as pd
df228 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df228)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 230 - Scikit-learn: Encoding Categorical Variables
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X229 = np.array([[1], [2], [3], [4], [5]])
y229 = np.array([1, 4, 9, 16, 25])
X_train229, X_test229, y_train229, y_test229 = train_test_split(X229, y229, test_size=0.2)
model229 = LinearRegression()
model229.fit(X_train229, y_train229)
print(model229.predict(X_test229))
```

    [5.42857143]
    


```python
# Cell 231 - Pandas: Data Types
import pandas as pd
df230 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df230)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 232 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X231 = np.array([[1], [2], [3], [4], [5]])
y231 = np.array([1, 4, 9, 16, 25])
X_train231, X_test231, y_train231, y_test231 = train_test_split(X231, y231, test_size=0.2)
model231 = LinearRegression()
model231.fit(X_train231, y_train231)
print(model231.predict(X_test231))
```

    [17.42857143]
    


```python
# Cell 233 - Pandas: Sorting
import pandas as pd
df232 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df232)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 234 - Scikit-learn: SVM
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X233 = np.array([[1], [2], [3], [4], [5]])
y233 = np.array([1, 4, 9, 16, 25])
X_train233, X_test233, y_train233, y_test233 = train_test_split(X233, y233, test_size=0.2)
model233 = LinearRegression()
model233.fit(X_train233, y_train233)
print(model233.predict(X_test233))
```

    [11.5]
    


```python
# Cell 235 - Pandas: GroupBy
import pandas as pd
df234 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df234)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 236 - Scikit-learn: Feature Scaling
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X235 = np.array([[1], [2], [3], [4], [5]])
y235 = np.array([1, 4, 9, 16, 25])
X_train235, X_test235, y_train235, y_test235 = train_test_split(X235, y235, test_size=0.2)
model235 = LinearRegression()
model235.fit(X_train235, y_train235)
print(model235.predict(X_test235))
```

    [5.42857143]
    


```python
# Cell 237 - Pandas: Filtering Rows
import pandas as pd
df236 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df236)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 238 - Scikit-learn: Feature Scaling
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X237 = np.array([[1], [2], [3], [4], [5]])
y237 = np.array([1, 4, 9, 16, 25])
X_train237, X_test237, y_train237, y_test237 = train_test_split(X237, y237, test_size=0.2)
model237 = LinearRegression()
model237.fit(X_train237, y_train237)
print(model237.predict(X_test237))
```

    [5.42857143]
    


```python
# Cell 239 - Pandas: Filtering Rows
import pandas as pd
df238 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df238)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 240 - Scikit-learn: Random Forest
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X239 = np.array([[1], [2], [3], [4], [5]])
y239 = np.array([1, 4, 9, 16, 25])
X_train239, X_test239, y_train239, y_test239 = train_test_split(X239, y239, test_size=0.2)
model239 = LinearRegression()
model239.fit(X_train239, y_train239)
print(model239.predict(X_test239))
```

    [17.42857143]
    


```python
# Cell 241 - Pandas: Handling Missing Data
import pandas as pd
df240 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df240)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 242 - Scikit-learn: Random Forest
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X241 = np.array([[1], [2], [3], [4], [5]])
y241 = np.array([1, 4, 9, 16, 25])
X_train241, X_test241, y_train241, y_test241 = train_test_split(X241, y241, test_size=0.2)
model241 = LinearRegression()
model241.fit(X_train241, y_train241)
print(model241.predict(X_test241))
```

    [5.42857143]
    


```python
# Cell 243 - Pandas: Descriptive Stats
import pandas as pd
df242 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df242)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 244 - Scikit-learn: Encoding Categorical Variables
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X243 = np.array([[1], [2], [3], [4], [5]])
y243 = np.array([1, 4, 9, 16, 25])
X_train243, X_test243, y_train243, y_test243 = train_test_split(X243, y243, test_size=0.2)
model243 = LinearRegression()
model243.fit(X_train243, y_train243)
print(model243.predict(X_test243))
```

    [20.]
    


```python
# Cell 245 - Pandas: Data Types
import pandas as pd
df244 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df244)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 246 - Scikit-learn: Logistic Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X245 = np.array([[1], [2], [3], [4], [5]])
y245 = np.array([1, 4, 9, 16, 25])
X_train245, X_test245, y_train245, y_test245 = train_test_split(X245, y245, test_size=0.2)
model245 = LinearRegression()
model245.fit(X_train245, y_train245)
print(model245.predict(X_test245))
```

    [20.]
    


```python
# Cell 247 - Pandas: Adding Columns
import pandas as pd
df246 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df246)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 248 - Scikit-learn: Random Forest
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X247 = np.array([[1], [2], [3], [4], [5]])
y247 = np.array([1, 4, 9, 16, 25])
X_train247, X_test247, y_train247, y_test247 = train_test_split(X247, y247, test_size=0.2)
model247 = LinearRegression()
model247.fit(X_train247, y_train247)
print(model247.predict(X_test247))
```

    [5.42857143]
    


```python
# Cell 249 - Pandas: Data Selection
import pandas as pd
df248 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df248)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 250 - Scikit-learn: KNN
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X249 = np.array([[1], [2], [3], [4], [5]])
y249 = np.array([1, 4, 9, 16, 25])
X_train249, X_test249, y_train249, y_test249 = train_test_split(X249, y249, test_size=0.2)
model249 = LinearRegression()
model249.fit(X_train249, y_train249)
print(model249.predict(X_test249))
```

    [5.42857143]
    


```python
# Cell 251 - Pandas: Creating DataFrames
import pandas as pd
df250 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df250)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 252 - Scikit-learn: Logistic Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X251 = np.array([[1], [2], [3], [4], [5]])
y251 = np.array([1, 4, 9, 16, 25])
X_train251, X_test251, y_train251, y_test251 = train_test_split(X251, y251, test_size=0.2)
model251 = LinearRegression()
model251.fit(X_train251, y_train251)
print(model251.predict(X_test251))
```

    [5.42857143]
    


```python
# Cell 253 - Pandas: Adding Columns
import pandas as pd
df252 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df252)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 254 - Scikit-learn: Feature Scaling
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X253 = np.array([[1], [2], [3], [4], [5]])
y253 = np.array([1, 4, 9, 16, 25])
X_train253, X_test253, y_train253, y_test253 = train_test_split(X253, y253, test_size=0.2)
model253 = LinearRegression()
model253.fit(X_train253, y_train253)
print(model253.predict(X_test253))
```

    [17.42857143]
    


```python
# Cell 255 - Pandas: Data Types
import pandas as pd
df254 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df254)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 256 - Scikit-learn: Random Forest
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X255 = np.array([[1], [2], [3], [4], [5]])
y255 = np.array([1, 4, 9, 16, 25])
X_train255, X_test255, y_train255, y_test255 = train_test_split(X255, y255, test_size=0.2)
model255 = LinearRegression()
model255.fit(X_train255, y_train255)
print(model255.predict(X_test255))
```

    [11.5]
    


```python
# Cell 257 - Pandas: Dropping Columns
import pandas as pd
df256 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df256)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 258 - Scikit-learn: Encoding Categorical Variables
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X257 = np.array([[1], [2], [3], [4], [5]])
y257 = np.array([1, 4, 9, 16, 25])
X_train257, X_test257, y_train257, y_test257 = train_test_split(X257, y257, test_size=0.2)
model257 = LinearRegression()
model257.fit(X_train257, y_train257)
print(model257.predict(X_test257))
```

    [17.42857143]
    


```python
# Cell 259 - Pandas: Merging DataFrames
import pandas as pd
df258 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df258)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 260 - Scikit-learn: Pipeline
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X259 = np.array([[1], [2], [3], [4], [5]])
y259 = np.array([1, 4, 9, 16, 25])
X_train259, X_test259, y_train259, y_test259 = train_test_split(X259, y259, test_size=0.2)
model259 = LinearRegression()
model259.fit(X_train259, y_train259)
print(model259.predict(X_test259))
```

    [20.]
    


```python
# Cell 261 - Pandas: GroupBy
import pandas as pd
df260 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df260)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 262 - Scikit-learn: Model Evaluation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X261 = np.array([[1], [2], [3], [4], [5]])
y261 = np.array([1, 4, 9, 16, 25])
X_train261, X_test261, y_train261, y_test261 = train_test_split(X261, y261, test_size=0.2)
model261 = LinearRegression()
model261.fit(X_train261, y_train261)
print(model261.predict(X_test261))
```

    [17.42857143]
    


```python
# Cell 263 - Pandas: GroupBy
import pandas as pd
df262 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df262)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 264 - Scikit-learn: Linear Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X263 = np.array([[1], [2], [3], [4], [5]])
y263 = np.array([1, 4, 9, 16, 25])
X_train263, X_test263, y_train263, y_test263 = train_test_split(X263, y263, test_size=0.2)
model263 = LinearRegression()
model263.fit(X_train263, y_train263)
print(model263.predict(X_test263))
```

    [20.]
    


```python
# Cell 265 - Pandas: Sorting
import pandas as pd
df264 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df264)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 266 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X265 = np.array([[1], [2], [3], [4], [5]])
y265 = np.array([1, 4, 9, 16, 25])
X_train265, X_test265, y_train265, y_test265 = train_test_split(X265, y265, test_size=0.2)
model265 = LinearRegression()
model265.fit(X_train265, y_train265)
print(model265.predict(X_test265))
```

    [11.5]
    


```python
# Cell 267 - Pandas: Merging DataFrames
import pandas as pd
df266 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df266)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 268 - Scikit-learn: Cross Validation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X267 = np.array([[1], [2], [3], [4], [5]])
y267 = np.array([1, 4, 9, 16, 25])
X_train267, X_test267, y_train267, y_test267 = train_test_split(X267, y267, test_size=0.2)
model267 = LinearRegression()
model267.fit(X_train267, y_train267)
print(model267.predict(X_test267))
```

    [20.]
    


```python
# Cell 269 - Pandas: Sorting
import pandas as pd
df268 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df268)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 270 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X269 = np.array([[1], [2], [3], [4], [5]])
y269 = np.array([1, 4, 9, 16, 25])
X_train269, X_test269, y_train269, y_test269 = train_test_split(X269, y269, test_size=0.2)
model269 = LinearRegression()
model269.fit(X_train269, y_train269)
print(model269.predict(X_test269))
```

    [-4.]
    


```python
# Cell 271 - Pandas: Data Types
import pandas as pd
df270 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df270)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 272 - Scikit-learn: Model Evaluation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X271 = np.array([[1], [2], [3], [4], [5]])
y271 = np.array([1, 4, 9, 16, 25])
X_train271, X_test271, y_train271, y_test271 = train_test_split(X271, y271, test_size=0.2)
model271 = LinearRegression()
model271.fit(X_train271, y_train271)
print(model271.predict(X_test271))
```

    [20.]
    


```python
# Cell 273 - Pandas: Data Types
import pandas as pd
df272 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df272)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 274 - Scikit-learn: Model Evaluation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X273 = np.array([[1], [2], [3], [4], [5]])
y273 = np.array([1, 4, 9, 16, 25])
X_train273, X_test273, y_train273, y_test273 = train_test_split(X273, y273, test_size=0.2)
model273 = LinearRegression()
model273.fit(X_train273, y_train273)
print(model273.predict(X_test273))
```

    [-4.]
    


```python
# Cell 275 - Pandas: Adding Columns
import pandas as pd
df274 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df274)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 276 - Scikit-learn: Train-Test Split
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X275 = np.array([[1], [2], [3], [4], [5]])
y275 = np.array([1, 4, 9, 16, 25])
X_train275, X_test275, y_train275, y_test275 = train_test_split(X275, y275, test_size=0.2)
model275 = LinearRegression()
model275.fit(X_train275, y_train275)
print(model275.predict(X_test275))
```

    [20.]
    


```python
# Cell 277 - Pandas: Handling Missing Data
import pandas as pd
df276 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df276)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 278 - Scikit-learn: KNN
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X277 = np.array([[1], [2], [3], [4], [5]])
y277 = np.array([1, 4, 9, 16, 25])
X_train277, X_test277, y_train277, y_test277 = train_test_split(X277, y277, test_size=0.2)
model277 = LinearRegression()
model277.fit(X_train277, y_train277)
print(model277.predict(X_test277))
```

    [20.]
    


```python
# Cell 279 - Pandas: Adding Columns
import pandas as pd
df278 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df278)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 280 - Scikit-learn: Linear Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X279 = np.array([[1], [2], [3], [4], [5]])
y279 = np.array([1, 4, 9, 16, 25])
X_train279, X_test279, y_train279, y_test279 = train_test_split(X279, y279, test_size=0.2)
model279 = LinearRegression()
model279.fit(X_train279, y_train279)
print(model279.predict(X_test279))
```

    [17.42857143]
    


```python
# Cell 281 - Pandas: GroupBy
import pandas as pd
df280 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df280)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 282 - Scikit-learn: Logistic Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X281 = np.array([[1], [2], [3], [4], [5]])
y281 = np.array([1, 4, 9, 16, 25])
X_train281, X_test281, y_train281, y_test281 = train_test_split(X281, y281, test_size=0.2)
model281 = LinearRegression()
model281.fit(X_train281, y_train281)
print(model281.predict(X_test281))
```

    [-4.]
    


```python
# Cell 283 - Pandas: Sorting
import pandas as pd
df282 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df282)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 284 - Scikit-learn: Pipeline
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X283 = np.array([[1], [2], [3], [4], [5]])
y283 = np.array([1, 4, 9, 16, 25])
X_train283, X_test283, y_train283, y_test283 = train_test_split(X283, y283, test_size=0.2)
model283 = LinearRegression()
model283.fit(X_train283, y_train283)
print(model283.predict(X_test283))
```

    [11.5]
    


```python
# Cell 285 - Pandas: Merging DataFrames
import pandas as pd
df284 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df284)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 286 - Scikit-learn: Linear Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X285 = np.array([[1], [2], [3], [4], [5]])
y285 = np.array([1, 4, 9, 16, 25])
X_train285, X_test285, y_train285, y_test285 = train_test_split(X285, y285, test_size=0.2)
model285 = LinearRegression()
model285.fit(X_train285, y_train285)
print(model285.predict(X_test285))
```

    [11.5]
    


```python
# Cell 287 - Pandas: Data Types
import pandas as pd
df286 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df286)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 288 - Scikit-learn: Encoding Categorical Variables
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X287 = np.array([[1], [2], [3], [4], [5]])
y287 = np.array([1, 4, 9, 16, 25])
X_train287, X_test287, y_train287, y_test287 = train_test_split(X287, y287, test_size=0.2)
model287 = LinearRegression()
model287.fit(X_train287, y_train287)
print(model287.predict(X_test287))
```

    [5.42857143]
    


```python
# Cell 289 - Pandas: Creating DataFrames
import pandas as pd
df288 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df288)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 290 - Scikit-learn: Cross Validation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X289 = np.array([[1], [2], [3], [4], [5]])
y289 = np.array([1, 4, 9, 16, 25])
X_train289, X_test289, y_train289, y_test289 = train_test_split(X289, y289, test_size=0.2)
model289 = LinearRegression()
model289.fit(X_train289, y_train289)
print(model289.predict(X_test289))
```

    [11.5]
    


```python
# Cell 291 - Pandas: Dropping Columns
import pandas as pd
df290 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df290)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 292 - Scikit-learn: Logistic Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X291 = np.array([[1], [2], [3], [4], [5]])
y291 = np.array([1, 4, 9, 16, 25])
X_train291, X_test291, y_train291, y_test291 = train_test_split(X291, y291, test_size=0.2)
model291 = LinearRegression()
model291.fit(X_train291, y_train291)
print(model291.predict(X_test291))
```

    [-4.]
    


```python
# Cell 293 - Pandas: Sorting
import pandas as pd
df292 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df292)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 294 - Scikit-learn: SVM
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X293 = np.array([[1], [2], [3], [4], [5]])
y293 = np.array([1, 4, 9, 16, 25])
X_train293, X_test293, y_train293, y_test293 = train_test_split(X293, y293, test_size=0.2)
model293 = LinearRegression()
model293.fit(X_train293, y_train293)
print(model293.predict(X_test293))
```

    [20.]
    


```python
# Cell 295 - Pandas: Handling Missing Data
import pandas as pd
df294 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df294)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 296 - Scikit-learn: SVM
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X295 = np.array([[1], [2], [3], [4], [5]])
y295 = np.array([1, 4, 9, 16, 25])
X_train295, X_test295, y_train295, y_test295 = train_test_split(X295, y295, test_size=0.2)
model295 = LinearRegression()
model295.fit(X_train295, y_train295)
print(model295.predict(X_test295))
```

    [5.42857143]
    


```python
# Cell 297 - Pandas: GroupBy
import pandas as pd
df296 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df296)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 298 - Scikit-learn: Logistic Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X297 = np.array([[1], [2], [3], [4], [5]])
y297 = np.array([1, 4, 9, 16, 25])
X_train297, X_test297, y_train297, y_test297 = train_test_split(X297, y297, test_size=0.2)
model297 = LinearRegression()
model297.fit(X_train297, y_train297)
print(model297.predict(X_test297))
```

    [17.42857143]
    


```python
# Cell 299 - Pandas: Data Types
import pandas as pd
df298 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df298)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 300 - Scikit-learn: Train-Test Split
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X299 = np.array([[1], [2], [3], [4], [5]])
y299 = np.array([1, 4, 9, 16, 25])
X_train299, X_test299, y_train299, y_test299 = train_test_split(X299, y299, test_size=0.2)
model299 = LinearRegression()
model299.fit(X_train299, y_train299)
print(model299.predict(X_test299))
```

    [-4.]
    


```python
# Cell 301 - Pandas: Descriptive Stats
import pandas as pd
df300 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df300)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 302 - Scikit-learn: Pipeline
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X301 = np.array([[1], [2], [3], [4], [5]])
y301 = np.array([1, 4, 9, 16, 25])
X_train301, X_test301, y_train301, y_test301 = train_test_split(X301, y301, test_size=0.2)
model301 = LinearRegression()
model301.fit(X_train301, y_train301)
print(model301.predict(X_test301))
```

    [17.42857143]
    


```python
# Cell 303 - Pandas: Descriptive Stats
import pandas as pd
df302 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df302)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 304 - Scikit-learn: Feature Scaling
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X303 = np.array([[1], [2], [3], [4], [5]])
y303 = np.array([1, 4, 9, 16, 25])
X_train303, X_test303, y_train303, y_test303 = train_test_split(X303, y303, test_size=0.2)
model303 = LinearRegression()
model303.fit(X_train303, y_train303)
print(model303.predict(X_test303))
```

    [-4.]
    


```python
# Cell 305 - Pandas: Reading CSV
import pandas as pd
df304 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df304)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 306 - Scikit-learn: Train-Test Split
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X305 = np.array([[1], [2], [3], [4], [5]])
y305 = np.array([1, 4, 9, 16, 25])
X_train305, X_test305, y_train305, y_test305 = train_test_split(X305, y305, test_size=0.2)
model305 = LinearRegression()
model305.fit(X_train305, y_train305)
print(model305.predict(X_test305))
```

    [-4.]
    


```python
# Cell 307 - Pandas: Sorting
import pandas as pd
df306 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df306)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 308 - Scikit-learn: Encoding Categorical Variables
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X307 = np.array([[1], [2], [3], [4], [5]])
y307 = np.array([1, 4, 9, 16, 25])
X_train307, X_test307, y_train307, y_test307 = train_test_split(X307, y307, test_size=0.2)
model307 = LinearRegression()
model307.fit(X_train307, y_train307)
print(model307.predict(X_test307))
```

    [-4.]
    


```python
# Cell 309 - Pandas: Dropping Columns
import pandas as pd
df308 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df308)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 310 - Scikit-learn: Random Forest
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X309 = np.array([[1], [2], [3], [4], [5]])
y309 = np.array([1, 4, 9, 16, 25])
X_train309, X_test309, y_train309, y_test309 = train_test_split(X309, y309, test_size=0.2)
model309 = LinearRegression()
model309.fit(X_train309, y_train309)
print(model309.predict(X_test309))
```

    [5.42857143]
    


```python
# Cell 311 - Pandas: Reading CSV
import pandas as pd
df310 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df310)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 312 - Scikit-learn: Model Evaluation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X311 = np.array([[1], [2], [3], [4], [5]])
y311 = np.array([1, 4, 9, 16, 25])
X_train311, X_test311, y_train311, y_test311 = train_test_split(X311, y311, test_size=0.2)
model311 = LinearRegression()
model311.fit(X_train311, y_train311)
print(model311.predict(X_test311))
```

    [11.5]
    


```python
# Cell 313 - Pandas: Adding Columns
import pandas as pd
df312 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df312)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 314 - Scikit-learn: Feature Scaling
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X313 = np.array([[1], [2], [3], [4], [5]])
y313 = np.array([1, 4, 9, 16, 25])
X_train313, X_test313, y_train313, y_test313 = train_test_split(X313, y313, test_size=0.2)
model313 = LinearRegression()
model313.fit(X_train313, y_train313)
print(model313.predict(X_test313))
```

    [-4.]
    


```python
# Cell 315 - Pandas: Merging DataFrames
import pandas as pd
df314 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df314)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 316 - Scikit-learn: Logistic Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X315 = np.array([[1], [2], [3], [4], [5]])
y315 = np.array([1, 4, 9, 16, 25])
X_train315, X_test315, y_train315, y_test315 = train_test_split(X315, y315, test_size=0.2)
model315 = LinearRegression()
model315.fit(X_train315, y_train315)
print(model315.predict(X_test315))
```

    [11.5]
    


```python
# Cell 317 - Pandas: Merging DataFrames
import pandas as pd
df316 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df316)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 318 - Scikit-learn: Encoding Categorical Variables
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X317 = np.array([[1], [2], [3], [4], [5]])
y317 = np.array([1, 4, 9, 16, 25])
X_train317, X_test317, y_train317, y_test317 = train_test_split(X317, y317, test_size=0.2)
model317 = LinearRegression()
model317.fit(X_train317, y_train317)
print(model317.predict(X_test317))
```

    [17.42857143]
    


```python
# Cell 319 - Pandas: Dropping Columns
import pandas as pd
df318 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df318)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 320 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X319 = np.array([[1], [2], [3], [4], [5]])
y319 = np.array([1, 4, 9, 16, 25])
X_train319, X_test319, y_train319, y_test319 = train_test_split(X319, y319, test_size=0.2)
model319 = LinearRegression()
model319.fit(X_train319, y_train319)
print(model319.predict(X_test319))
```

    [17.42857143]
    


```python
# Cell 321 - Pandas: Data Types
import pandas as pd
df320 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df320)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 322 - Scikit-learn: Feature Scaling
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X321 = np.array([[1], [2], [3], [4], [5]])
y321 = np.array([1, 4, 9, 16, 25])
X_train321, X_test321, y_train321, y_test321 = train_test_split(X321, y321, test_size=0.2)
model321 = LinearRegression()
model321.fit(X_train321, y_train321)
print(model321.predict(X_test321))
```

    [5.42857143]
    


```python
# Cell 323 - Pandas: Filtering Rows
import pandas as pd
df322 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df322)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 324 - Scikit-learn: Pipeline
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X323 = np.array([[1], [2], [3], [4], [5]])
y323 = np.array([1, 4, 9, 16, 25])
X_train323, X_test323, y_train323, y_test323 = train_test_split(X323, y323, test_size=0.2)
model323 = LinearRegression()
model323.fit(X_train323, y_train323)
print(model323.predict(X_test323))
```

    [5.42857143]
    


```python
# Cell 325 - Pandas: Creating DataFrames
import pandas as pd
df324 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df324)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 326 - Scikit-learn: Random Forest
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X325 = np.array([[1], [2], [3], [4], [5]])
y325 = np.array([1, 4, 9, 16, 25])
X_train325, X_test325, y_train325, y_test325 = train_test_split(X325, y325, test_size=0.2)
model325 = LinearRegression()
model325.fit(X_train325, y_train325)
print(model325.predict(X_test325))
```

    [-4.]
    


```python
# Cell 327 - Pandas: GroupBy
import pandas as pd
df326 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df326)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 328 - Scikit-learn: Pipeline
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X327 = np.array([[1], [2], [3], [4], [5]])
y327 = np.array([1, 4, 9, 16, 25])
X_train327, X_test327, y_train327, y_test327 = train_test_split(X327, y327, test_size=0.2)
model327 = LinearRegression()
model327.fit(X_train327, y_train327)
print(model327.predict(X_test327))
```

    [5.42857143]
    


```python
# Cell 329 - Pandas: Data Types
import pandas as pd
df328 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df328)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 330 - Scikit-learn: SVM
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X329 = np.array([[1], [2], [3], [4], [5]])
y329 = np.array([1, 4, 9, 16, 25])
X_train329, X_test329, y_train329, y_test329 = train_test_split(X329, y329, test_size=0.2)
model329 = LinearRegression()
model329.fit(X_train329, y_train329)
print(model329.predict(X_test329))
```

    [-4.]
    


```python
# Cell 331 - Pandas: Descriptive Stats
import pandas as pd
df330 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df330)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 332 - Scikit-learn: Model Evaluation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X331 = np.array([[1], [2], [3], [4], [5]])
y331 = np.array([1, 4, 9, 16, 25])
X_train331, X_test331, y_train331, y_test331 = train_test_split(X331, y331, test_size=0.2)
model331 = LinearRegression()
model331.fit(X_train331, y_train331)
print(model331.predict(X_test331))
```

    [20.]
    


```python
# Cell 333 - Pandas: Handling Missing Data
import pandas as pd
df332 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df332)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 334 - Scikit-learn: Model Evaluation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X333 = np.array([[1], [2], [3], [4], [5]])
y333 = np.array([1, 4, 9, 16, 25])
X_train333, X_test333, y_train333, y_test333 = train_test_split(X333, y333, test_size=0.2)
model333 = LinearRegression()
model333.fit(X_train333, y_train333)
print(model333.predict(X_test333))
```

    [20.]
    


```python
# Cell 335 - Pandas: Reading CSV
import pandas as pd
df334 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df334)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 336 - Scikit-learn: Pipeline
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X335 = np.array([[1], [2], [3], [4], [5]])
y335 = np.array([1, 4, 9, 16, 25])
X_train335, X_test335, y_train335, y_test335 = train_test_split(X335, y335, test_size=0.2)
model335 = LinearRegression()
model335.fit(X_train335, y_train335)
print(model335.predict(X_test335))
```

    [17.42857143]
    


```python
# Cell 337 - Pandas: GroupBy
import pandas as pd
df336 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df336)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 338 - Scikit-learn: Feature Scaling
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X337 = np.array([[1], [2], [3], [4], [5]])
y337 = np.array([1, 4, 9, 16, 25])
X_train337, X_test337, y_train337, y_test337 = train_test_split(X337, y337, test_size=0.2)
model337 = LinearRegression()
model337.fit(X_train337, y_train337)
print(model337.predict(X_test337))
```

    [-4.]
    


```python
# Cell 339 - Pandas: Dropping Columns
import pandas as pd
df338 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df338)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 340 - Scikit-learn: Logistic Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X339 = np.array([[1], [2], [3], [4], [5]])
y339 = np.array([1, 4, 9, 16, 25])
X_train339, X_test339, y_train339, y_test339 = train_test_split(X339, y339, test_size=0.2)
model339 = LinearRegression()
model339.fit(X_train339, y_train339)
print(model339.predict(X_test339))
```

    [-4.]
    


```python
# Cell 341 - Pandas: Data Types
import pandas as pd
df340 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df340)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 342 - Scikit-learn: KNN
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X341 = np.array([[1], [2], [3], [4], [5]])
y341 = np.array([1, 4, 9, 16, 25])
X_train341, X_test341, y_train341, y_test341 = train_test_split(X341, y341, test_size=0.2)
model341 = LinearRegression()
model341.fit(X_train341, y_train341)
print(model341.predict(X_test341))
```

    [5.42857143]
    


```python
# Cell 343 - Pandas: Filtering Rows
import pandas as pd
df342 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df342)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 344 - Scikit-learn: Cross Validation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X343 = np.array([[1], [2], [3], [4], [5]])
y343 = np.array([1, 4, 9, 16, 25])
X_train343, X_test343, y_train343, y_test343 = train_test_split(X343, y343, test_size=0.2)
model343 = LinearRegression()
model343.fit(X_train343, y_train343)
print(model343.predict(X_test343))
```

    [11.5]
    


```python
# Cell 345 - Pandas: Data Types
import pandas as pd
df344 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df344)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 346 - Scikit-learn: Feature Scaling
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X345 = np.array([[1], [2], [3], [4], [5]])
y345 = np.array([1, 4, 9, 16, 25])
X_train345, X_test345, y_train345, y_test345 = train_test_split(X345, y345, test_size=0.2)
model345 = LinearRegression()
model345.fit(X_train345, y_train345)
print(model345.predict(X_test345))
```

    [-4.]
    


```python
# Cell 347 - Pandas: Data Selection
import pandas as pd
df346 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df346)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 348 - Scikit-learn: SVM
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X347 = np.array([[1], [2], [3], [4], [5]])
y347 = np.array([1, 4, 9, 16, 25])
X_train347, X_test347, y_train347, y_test347 = train_test_split(X347, y347, test_size=0.2)
model347 = LinearRegression()
model347.fit(X_train347, y_train347)
print(model347.predict(X_test347))
```

    [5.42857143]
    


```python
# Cell 349 - Pandas: Descriptive Stats
import pandas as pd
df348 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df348)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 350 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X349 = np.array([[1], [2], [3], [4], [5]])
y349 = np.array([1, 4, 9, 16, 25])
X_train349, X_test349, y_train349, y_test349 = train_test_split(X349, y349, test_size=0.2)
model349 = LinearRegression()
model349.fit(X_train349, y_train349)
print(model349.predict(X_test349))
```

    [5.42857143]
    


```python
# Cell 351 - Pandas: Filtering Rows
import pandas as pd
df350 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df350)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 352 - Scikit-learn: Linear Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X351 = np.array([[1], [2], [3], [4], [5]])
y351 = np.array([1, 4, 9, 16, 25])
X_train351, X_test351, y_train351, y_test351 = train_test_split(X351, y351, test_size=0.2)
model351 = LinearRegression()
model351.fit(X_train351, y_train351)
print(model351.predict(X_test351))
```

    [5.42857143]
    


```python
# Cell 353 - Pandas: Creating DataFrames
import pandas as pd
df352 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df352)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 354 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X353 = np.array([[1], [2], [3], [4], [5]])
y353 = np.array([1, 4, 9, 16, 25])
X_train353, X_test353, y_train353, y_test353 = train_test_split(X353, y353, test_size=0.2)
model353 = LinearRegression()
model353.fit(X_train353, y_train353)
print(model353.predict(X_test353))
```

    [20.]
    


```python
# Cell 355 - Pandas: Merging DataFrames
import pandas as pd
df354 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df354)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 356 - Scikit-learn: Encoding Categorical Variables
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X355 = np.array([[1], [2], [3], [4], [5]])
y355 = np.array([1, 4, 9, 16, 25])
X_train355, X_test355, y_train355, y_test355 = train_test_split(X355, y355, test_size=0.2)
model355 = LinearRegression()
model355.fit(X_train355, y_train355)
print(model355.predict(X_test355))
```

    [-4.]
    


```python
# Cell 357 - Pandas: Descriptive Stats
import pandas as pd
df356 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df356)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 358 - Scikit-learn: SVM
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X357 = np.array([[1], [2], [3], [4], [5]])
y357 = np.array([1, 4, 9, 16, 25])
X_train357, X_test357, y_train357, y_test357 = train_test_split(X357, y357, test_size=0.2)
model357 = LinearRegression()
model357.fit(X_train357, y_train357)
print(model357.predict(X_test357))
```

    [5.42857143]
    


```python
# Cell 359 - Pandas: Merging DataFrames
import pandas as pd
df358 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df358)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 360 - Scikit-learn: SVM
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X359 = np.array([[1], [2], [3], [4], [5]])
y359 = np.array([1, 4, 9, 16, 25])
X_train359, X_test359, y_train359, y_test359 = train_test_split(X359, y359, test_size=0.2)
model359 = LinearRegression()
model359.fit(X_train359, y_train359)
print(model359.predict(X_test359))
```

    [5.42857143]
    


```python
# Cell 361 - Pandas: Reading CSV
import pandas as pd
df360 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df360)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 362 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X361 = np.array([[1], [2], [3], [4], [5]])
y361 = np.array([1, 4, 9, 16, 25])
X_train361, X_test361, y_train361, y_test361 = train_test_split(X361, y361, test_size=0.2)
model361 = LinearRegression()
model361.fit(X_train361, y_train361)
print(model361.predict(X_test361))
```

    [-4.]
    


```python
# Cell 363 - Pandas: Descriptive Stats
import pandas as pd
df362 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df362)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 364 - Scikit-learn: Linear Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X363 = np.array([[1], [2], [3], [4], [5]])
y363 = np.array([1, 4, 9, 16, 25])
X_train363, X_test363, y_train363, y_test363 = train_test_split(X363, y363, test_size=0.2)
model363 = LinearRegression()
model363.fit(X_train363, y_train363)
print(model363.predict(X_test363))
```

    [17.42857143]
    


```python
# Cell 365 - Pandas: GroupBy
import pandas as pd
df364 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df364)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 366 - Scikit-learn: SVM
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X365 = np.array([[1], [2], [3], [4], [5]])
y365 = np.array([1, 4, 9, 16, 25])
X_train365, X_test365, y_train365, y_test365 = train_test_split(X365, y365, test_size=0.2)
model365 = LinearRegression()
model365.fit(X_train365, y_train365)
print(model365.predict(X_test365))
```

    [17.42857143]
    


```python
# Cell 367 - Pandas: Handling Missing Data
import pandas as pd
df366 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df366)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 368 - Scikit-learn: Logistic Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X367 = np.array([[1], [2], [3], [4], [5]])
y367 = np.array([1, 4, 9, 16, 25])
X_train367, X_test367, y_train367, y_test367 = train_test_split(X367, y367, test_size=0.2)
model367 = LinearRegression()
model367.fit(X_train367, y_train367)
print(model367.predict(X_test367))
```

    [20.]
    


```python
# Cell 369 - Pandas: Reading CSV
import pandas as pd
df368 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df368)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 370 - Scikit-learn: Feature Scaling
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X369 = np.array([[1], [2], [3], [4], [5]])
y369 = np.array([1, 4, 9, 16, 25])
X_train369, X_test369, y_train369, y_test369 = train_test_split(X369, y369, test_size=0.2)
model369 = LinearRegression()
model369.fit(X_train369, y_train369)
print(model369.predict(X_test369))
```

    [17.42857143]
    


```python
# Cell 371 - Pandas: Data Selection
import pandas as pd
df370 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df370)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 372 - Scikit-learn: Cross Validation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X371 = np.array([[1], [2], [3], [4], [5]])
y371 = np.array([1, 4, 9, 16, 25])
X_train371, X_test371, y_train371, y_test371 = train_test_split(X371, y371, test_size=0.2)
model371 = LinearRegression()
model371.fit(X_train371, y_train371)
print(model371.predict(X_test371))
```

    [5.42857143]
    


```python
# Cell 373 - Pandas: Merging DataFrames
import pandas as pd
df372 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df372)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 374 - Scikit-learn: Logistic Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X373 = np.array([[1], [2], [3], [4], [5]])
y373 = np.array([1, 4, 9, 16, 25])
X_train373, X_test373, y_train373, y_test373 = train_test_split(X373, y373, test_size=0.2)
model373 = LinearRegression()
model373.fit(X_train373, y_train373)
print(model373.predict(X_test373))
```

    [11.5]
    


```python
# Cell 375 - Pandas: Sorting
import pandas as pd
df374 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df374)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 376 - Scikit-learn: Model Evaluation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X375 = np.array([[1], [2], [3], [4], [5]])
y375 = np.array([1, 4, 9, 16, 25])
X_train375, X_test375, y_train375, y_test375 = train_test_split(X375, y375, test_size=0.2)
model375 = LinearRegression()
model375.fit(X_train375, y_train375)
print(model375.predict(X_test375))
```

    [17.42857143]
    


```python
# Cell 377 - Pandas: Data Selection
import pandas as pd
df376 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df376)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 378 - Scikit-learn: Encoding Categorical Variables
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X377 = np.array([[1], [2], [3], [4], [5]])
y377 = np.array([1, 4, 9, 16, 25])
X_train377, X_test377, y_train377, y_test377 = train_test_split(X377, y377, test_size=0.2)
model377 = LinearRegression()
model377.fit(X_train377, y_train377)
print(model377.predict(X_test377))
```

    [-4.]
    


```python
# Cell 379 - Pandas: Handling Missing Data
import pandas as pd
df378 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df378)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 380 - Scikit-learn: Linear Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X379 = np.array([[1], [2], [3], [4], [5]])
y379 = np.array([1, 4, 9, 16, 25])
X_train379, X_test379, y_train379, y_test379 = train_test_split(X379, y379, test_size=0.2)
model379 = LinearRegression()
model379.fit(X_train379, y_train379)
print(model379.predict(X_test379))
```

    [20.]
    


```python
# Cell 381 - Pandas: Creating DataFrames
import pandas as pd
df380 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df380)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 382 - Scikit-learn: Feature Scaling
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X381 = np.array([[1], [2], [3], [4], [5]])
y381 = np.array([1, 4, 9, 16, 25])
X_train381, X_test381, y_train381, y_test381 = train_test_split(X381, y381, test_size=0.2)
model381 = LinearRegression()
model381.fit(X_train381, y_train381)
print(model381.predict(X_test381))
```

    [20.]
    


```python
# Cell 383 - Pandas: Dropping Columns
import pandas as pd
df382 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df382)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 384 - Scikit-learn: KNN
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X383 = np.array([[1], [2], [3], [4], [5]])
y383 = np.array([1, 4, 9, 16, 25])
X_train383, X_test383, y_train383, y_test383 = train_test_split(X383, y383, test_size=0.2)
model383 = LinearRegression()
model383.fit(X_train383, y_train383)
print(model383.predict(X_test383))
```

    [5.42857143]
    


```python
# Cell 385 - Pandas: Data Selection
import pandas as pd
df384 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df384)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 386 - Scikit-learn: Pipeline
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X385 = np.array([[1], [2], [3], [4], [5]])
y385 = np.array([1, 4, 9, 16, 25])
X_train385, X_test385, y_train385, y_test385 = train_test_split(X385, y385, test_size=0.2)
model385 = LinearRegression()
model385.fit(X_train385, y_train385)
print(model385.predict(X_test385))
```

    [11.5]
    


```python
# Cell 387 - Pandas: Handling Missing Data
import pandas as pd
df386 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df386)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 388 - Scikit-learn: Feature Scaling
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X387 = np.array([[1], [2], [3], [4], [5]])
y387 = np.array([1, 4, 9, 16, 25])
X_train387, X_test387, y_train387, y_test387 = train_test_split(X387, y387, test_size=0.2)
model387 = LinearRegression()
model387.fit(X_train387, y_train387)
print(model387.predict(X_test387))
```

    [17.42857143]
    


```python
# Cell 389 - Pandas: Handling Missing Data
import pandas as pd
df388 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df388)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 390 - Scikit-learn: Feature Scaling
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X389 = np.array([[1], [2], [3], [4], [5]])
y389 = np.array([1, 4, 9, 16, 25])
X_train389, X_test389, y_train389, y_test389 = train_test_split(X389, y389, test_size=0.2)
model389 = LinearRegression()
model389.fit(X_train389, y_train389)
print(model389.predict(X_test389))
```

    [11.5]
    


```python
# Cell 391 - Pandas: Adding Columns
import pandas as pd
df390 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df390)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 392 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X391 = np.array([[1], [2], [3], [4], [5]])
y391 = np.array([1, 4, 9, 16, 25])
X_train391, X_test391, y_train391, y_test391 = train_test_split(X391, y391, test_size=0.2)
model391 = LinearRegression()
model391.fit(X_train391, y_train391)
print(model391.predict(X_test391))
```

    [20.]
    


```python
# Cell 393 - Pandas: Adding Columns
import pandas as pd
df392 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df392)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 394 - Scikit-learn: Pipeline
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X393 = np.array([[1], [2], [3], [4], [5]])
y393 = np.array([1, 4, 9, 16, 25])
X_train393, X_test393, y_train393, y_test393 = train_test_split(X393, y393, test_size=0.2)
model393 = LinearRegression()
model393.fit(X_train393, y_train393)
print(model393.predict(X_test393))
```

    [11.5]
    


```python
# Cell 395 - Pandas: Adding Columns
import pandas as pd
df394 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df394)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 396 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X395 = np.array([[1], [2], [3], [4], [5]])
y395 = np.array([1, 4, 9, 16, 25])
X_train395, X_test395, y_train395, y_test395 = train_test_split(X395, y395, test_size=0.2)
model395 = LinearRegression()
model395.fit(X_train395, y_train395)
print(model395.predict(X_test395))
```

    [5.42857143]
    


```python
# Cell 397 - Pandas: Sorting
import pandas as pd
df396 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df396)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 398 - Scikit-learn: Linear Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X397 = np.array([[1], [2], [3], [4], [5]])
y397 = np.array([1, 4, 9, 16, 25])
X_train397, X_test397, y_train397, y_test397 = train_test_split(X397, y397, test_size=0.2)
model397 = LinearRegression()
model397.fit(X_train397, y_train397)
print(model397.predict(X_test397))
```

    [20.]
    


```python
# Cell 399 - Pandas: Merging DataFrames
import pandas as pd
df398 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df398)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 400 - Scikit-learn: Train-Test Split
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X399 = np.array([[1], [2], [3], [4], [5]])
y399 = np.array([1, 4, 9, 16, 25])
X_train399, X_test399, y_train399, y_test399 = train_test_split(X399, y399, test_size=0.2)
model399 = LinearRegression()
model399.fit(X_train399, y_train399)
print(model399.predict(X_test399))
```

    [5.42857143]
    


```python
# Cell 401 - Pandas: Adding Columns
import pandas as pd
df400 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df400)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 402 - Scikit-learn: KNN
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X401 = np.array([[1], [2], [3], [4], [5]])
y401 = np.array([1, 4, 9, 16, 25])
X_train401, X_test401, y_train401, y_test401 = train_test_split(X401, y401, test_size=0.2)
model401 = LinearRegression()
model401.fit(X_train401, y_train401)
print(model401.predict(X_test401))
```

    [5.42857143]
    


```python
# Cell 403 - Pandas: Sorting
import pandas as pd
df402 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df402)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 404 - Scikit-learn: KNN
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X403 = np.array([[1], [2], [3], [4], [5]])
y403 = np.array([1, 4, 9, 16, 25])
X_train403, X_test403, y_train403, y_test403 = train_test_split(X403, y403, test_size=0.2)
model403 = LinearRegression()
model403.fit(X_train403, y_train403)
print(model403.predict(X_test403))
```

    [-4.]
    


```python
# Cell 405 - Pandas: Data Types
import pandas as pd
df404 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df404)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 406 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X405 = np.array([[1], [2], [3], [4], [5]])
y405 = np.array([1, 4, 9, 16, 25])
X_train405, X_test405, y_train405, y_test405 = train_test_split(X405, y405, test_size=0.2)
model405 = LinearRegression()
model405.fit(X_train405, y_train405)
print(model405.predict(X_test405))
```

    [11.5]
    


```python
# Cell 407 - Pandas: Creating DataFrames
import pandas as pd
df406 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df406)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 408 - Scikit-learn: SVM
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X407 = np.array([[1], [2], [3], [4], [5]])
y407 = np.array([1, 4, 9, 16, 25])
X_train407, X_test407, y_train407, y_test407 = train_test_split(X407, y407, test_size=0.2)
model407 = LinearRegression()
model407.fit(X_train407, y_train407)
print(model407.predict(X_test407))
```

    [20.]
    


```python
# Cell 409 - Pandas: Filtering Rows
import pandas as pd
df408 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df408)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 410 - Scikit-learn: Random Forest
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X409 = np.array([[1], [2], [3], [4], [5]])
y409 = np.array([1, 4, 9, 16, 25])
X_train409, X_test409, y_train409, y_test409 = train_test_split(X409, y409, test_size=0.2)
model409 = LinearRegression()
model409.fit(X_train409, y_train409)
print(model409.predict(X_test409))
```

    [5.42857143]
    


```python
# Cell 411 - Pandas: Sorting
import pandas as pd
df410 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df410)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 412 - Scikit-learn: KNN
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X411 = np.array([[1], [2], [3], [4], [5]])
y411 = np.array([1, 4, 9, 16, 25])
X_train411, X_test411, y_train411, y_test411 = train_test_split(X411, y411, test_size=0.2)
model411 = LinearRegression()
model411.fit(X_train411, y_train411)
print(model411.predict(X_test411))
```

    [20.]
    


```python
# Cell 413 - Pandas: Handling Missing Data
import pandas as pd
df412 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df412)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 414 - Scikit-learn: Train-Test Split
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X413 = np.array([[1], [2], [3], [4], [5]])
y413 = np.array([1, 4, 9, 16, 25])
X_train413, X_test413, y_train413, y_test413 = train_test_split(X413, y413, test_size=0.2)
model413 = LinearRegression()
model413.fit(X_train413, y_train413)
print(model413.predict(X_test413))
```

    [5.42857143]
    


```python
# Cell 415 - Pandas: GroupBy
import pandas as pd
df414 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df414)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 416 - Scikit-learn: SVM
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X415 = np.array([[1], [2], [3], [4], [5]])
y415 = np.array([1, 4, 9, 16, 25])
X_train415, X_test415, y_train415, y_test415 = train_test_split(X415, y415, test_size=0.2)
model415 = LinearRegression()
model415.fit(X_train415, y_train415)
print(model415.predict(X_test415))
```

    [11.5]
    


```python
# Cell 417 - Pandas: Filtering Rows
import pandas as pd
df416 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df416)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 418 - Scikit-learn: Model Evaluation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X417 = np.array([[1], [2], [3], [4], [5]])
y417 = np.array([1, 4, 9, 16, 25])
X_train417, X_test417, y_train417, y_test417 = train_test_split(X417, y417, test_size=0.2)
model417 = LinearRegression()
model417.fit(X_train417, y_train417)
print(model417.predict(X_test417))
```

    [-4.]
    


```python
# Cell 419 - Pandas: Reading CSV
import pandas as pd
df418 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df418)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 420 - Scikit-learn: Model Evaluation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X419 = np.array([[1], [2], [3], [4], [5]])
y419 = np.array([1, 4, 9, 16, 25])
X_train419, X_test419, y_train419, y_test419 = train_test_split(X419, y419, test_size=0.2)
model419 = LinearRegression()
model419.fit(X_train419, y_train419)
print(model419.predict(X_test419))
```

    [-4.]
    


```python
# Cell 421 - Pandas: Dropping Columns
import pandas as pd
df420 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df420)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 422 - Scikit-learn: SVM
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X421 = np.array([[1], [2], [3], [4], [5]])
y421 = np.array([1, 4, 9, 16, 25])
X_train421, X_test421, y_train421, y_test421 = train_test_split(X421, y421, test_size=0.2)
model421 = LinearRegression()
model421.fit(X_train421, y_train421)
print(model421.predict(X_test421))
```

    [17.42857143]
    


```python
# Cell 423 - Pandas: Dropping Columns
import pandas as pd
df422 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df422)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 424 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X423 = np.array([[1], [2], [3], [4], [5]])
y423 = np.array([1, 4, 9, 16, 25])
X_train423, X_test423, y_train423, y_test423 = train_test_split(X423, y423, test_size=0.2)
model423 = LinearRegression()
model423.fit(X_train423, y_train423)
print(model423.predict(X_test423))
```

    [-4.]
    


```python
# Cell 425 - Pandas: Data Selection
import pandas as pd
df424 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df424)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 426 - Scikit-learn: Feature Scaling
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X425 = np.array([[1], [2], [3], [4], [5]])
y425 = np.array([1, 4, 9, 16, 25])
X_train425, X_test425, y_train425, y_test425 = train_test_split(X425, y425, test_size=0.2)
model425 = LinearRegression()
model425.fit(X_train425, y_train425)
print(model425.predict(X_test425))
```

    [-4.]
    


```python
# Cell 427 - Pandas: Merging DataFrames
import pandas as pd
df426 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df426)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 428 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X427 = np.array([[1], [2], [3], [4], [5]])
y427 = np.array([1, 4, 9, 16, 25])
X_train427, X_test427, y_train427, y_test427 = train_test_split(X427, y427, test_size=0.2)
model427 = LinearRegression()
model427.fit(X_train427, y_train427)
print(model427.predict(X_test427))
```

    [20.]
    


```python
# Cell 429 - Pandas: Creating DataFrames
import pandas as pd
df428 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df428)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 430 - Scikit-learn: Pipeline
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X429 = np.array([[1], [2], [3], [4], [5]])
y429 = np.array([1, 4, 9, 16, 25])
X_train429, X_test429, y_train429, y_test429 = train_test_split(X429, y429, test_size=0.2)
model429 = LinearRegression()
model429.fit(X_train429, y_train429)
print(model429.predict(X_test429))
```

    [5.42857143]
    


```python
# Cell 431 - Pandas: Data Selection
import pandas as pd
df430 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df430)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 432 - Scikit-learn: Encoding Categorical Variables
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X431 = np.array([[1], [2], [3], [4], [5]])
y431 = np.array([1, 4, 9, 16, 25])
X_train431, X_test431, y_train431, y_test431 = train_test_split(X431, y431, test_size=0.2)
model431 = LinearRegression()
model431.fit(X_train431, y_train431)
print(model431.predict(X_test431))
```

    [-4.]
    


```python
# Cell 433 - Pandas: Data Selection
import pandas as pd
df432 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df432)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 434 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X433 = np.array([[1], [2], [3], [4], [5]])
y433 = np.array([1, 4, 9, 16, 25])
X_train433, X_test433, y_train433, y_test433 = train_test_split(X433, y433, test_size=0.2)
model433 = LinearRegression()
model433.fit(X_train433, y_train433)
print(model433.predict(X_test433))
```

    [5.42857143]
    


```python
# Cell 435 - Pandas: Adding Columns
import pandas as pd
df434 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df434)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 436 - Scikit-learn: Decision Trees
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X435 = np.array([[1], [2], [3], [4], [5]])
y435 = np.array([1, 4, 9, 16, 25])
X_train435, X_test435, y_train435, y_test435 = train_test_split(X435, y435, test_size=0.2)
model435 = LinearRegression()
model435.fit(X_train435, y_train435)
print(model435.predict(X_test435))
```

    [11.5]
    


```python
# Cell 437 - Pandas: GroupBy
import pandas as pd
df436 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df436)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 438 - Scikit-learn: Model Evaluation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X437 = np.array([[1], [2], [3], [4], [5]])
y437 = np.array([1, 4, 9, 16, 25])
X_train437, X_test437, y_train437, y_test437 = train_test_split(X437, y437, test_size=0.2)
model437 = LinearRegression()
model437.fit(X_train437, y_train437)
print(model437.predict(X_test437))
```

    [-4.]
    


```python
# Cell 439 - Pandas: Data Selection
import pandas as pd
df438 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df438)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 440 - Scikit-learn: Encoding Categorical Variables
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X439 = np.array([[1], [2], [3], [4], [5]])
y439 = np.array([1, 4, 9, 16, 25])
X_train439, X_test439, y_train439, y_test439 = train_test_split(X439, y439, test_size=0.2)
model439 = LinearRegression()
model439.fit(X_train439, y_train439)
print(model439.predict(X_test439))
```

    [20.]
    


```python
# Cell 441 - Pandas: Dropping Columns
import pandas as pd
df440 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df440)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 442 - Scikit-learn: Linear Regression
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X441 = np.array([[1], [2], [3], [4], [5]])
y441 = np.array([1, 4, 9, 16, 25])
X_train441, X_test441, y_train441, y_test441 = train_test_split(X441, y441, test_size=0.2)
model441 = LinearRegression()
model441.fit(X_train441, y_train441)
print(model441.predict(X_test441))
```

    [11.5]
    


```python
# Cell 443 - Pandas: Dropping Columns
import pandas as pd
df442 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df442)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 444 - Scikit-learn: Model Evaluation
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X443 = np.array([[1], [2], [3], [4], [5]])
y443 = np.array([1, 4, 9, 16, 25])
X_train443, X_test443, y_train443, y_test443 = train_test_split(X443, y443, test_size=0.2)
model443 = LinearRegression()
model443.fit(X_train443, y_train443)
print(model443.predict(X_test443))
```

    [20.]
    


```python
# Cell 445 - Pandas: Filtering Rows
import pandas as pd
df444 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df444)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 446 - Scikit-learn: Encoding Categorical Variables
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X445 = np.array([[1], [2], [3], [4], [5]])
y445 = np.array([1, 4, 9, 16, 25])
X_train445, X_test445, y_train445, y_test445 = train_test_split(X445, y445, test_size=0.2)
model445 = LinearRegression()
model445.fit(X_train445, y_train445)
print(model445.predict(X_test445))
```

    [17.42857143]
    


```python
# Cell 447 - Pandas: Merging DataFrames
import pandas as pd
df446 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df446)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 448 - Scikit-learn: Pipeline
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X447 = np.array([[1], [2], [3], [4], [5]])
y447 = np.array([1, 4, 9, 16, 25])
X_train447, X_test447, y_train447, y_test447 = train_test_split(X447, y447, test_size=0.2)
model447 = LinearRegression()
model447.fit(X_train447, y_train447)
print(model447.predict(X_test447))
```

    [5.42857143]
    


```python
# Cell 449 - Pandas: Handling Missing Data
import pandas as pd
df448 = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})
print(df448)
```

       A  B
    0  1  4
    1  2  5
    2  3  6
    


```python
# Cell 450 - Scikit-learn: Train-Test Split
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
X449 = np.array([[1], [2], [3], [4], [5]])
y449 = np.array([1, 4, 9, 16, 25])
X_train449, X_test449, y_train449, y_test449 = train_test_split(X449, y449, test_size=0.2)
model449 = LinearRegression()
model449.fit(X_train449, y_train449)
print(model449.predict(X_test449))
```

    [-4.]
    


---
**Score: 450**