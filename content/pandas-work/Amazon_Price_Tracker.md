---
title: Amazon Price Tracker
date: 2025-06-29
author: Your Name
cell_count: 7
score: 5
---

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

```


```python
df = pd.read_csv("amazon_products.csv")
df
```


    ---------------------------------------------------------------------------

    FileNotFoundError                         Traceback (most recent call last)

    Cell In[5], line 1
    ----> 1 df = pd.read_csv("amazon_products.csv")
          2 df
    

    File ~\AppData\Roaming\Python\Python312\site-packages\pandas\io\parsers\readers.py:1026, in read_csv(filepath_or_buffer, sep, delimiter, header, names, index_col, usecols, dtype, engine, converters, true_values, false_values, skipinitialspace, skiprows, skipfooter, nrows, na_values, keep_default_na, na_filter, verbose, skip_blank_lines, parse_dates, infer_datetime_format, keep_date_col, date_parser, date_format, dayfirst, cache_dates, iterator, chunksize, compression, thousands, decimal, lineterminator, quotechar, quoting, doublequote, escapechar, comment, encoding, encoding_errors, dialect, on_bad_lines, delim_whitespace, low_memory, memory_map, float_precision, storage_options, dtype_backend)
       1013 kwds_defaults = _refine_defaults_read(
       1014     dialect,
       1015     delimiter,
       (...)   1022     dtype_backend=dtype_backend,
       1023 )
       1024 kwds.update(kwds_defaults)
    -> 1026 return _read(filepath_or_buffer, kwds)
    

    File ~\AppData\Roaming\Python\Python312\site-packages\pandas\io\parsers\readers.py:620, in _read(filepath_or_buffer, kwds)
        617 _validate_names(kwds.get("names", None))
        619 # Create the parser.
    --> 620 parser = TextFileReader(filepath_or_buffer, **kwds)
        622 if chunksize or iterator:
        623     return parser
    

    File ~\AppData\Roaming\Python\Python312\site-packages\pandas\io\parsers\readers.py:1620, in TextFileReader.__init__(self, f, engine, **kwds)
       1617     self.options["has_index_names"] = kwds["has_index_names"]
       1619 self.handles: IOHandles | None = None
    -> 1620 self._engine = self._make_engine(f, self.engine)
    

    File ~\AppData\Roaming\Python\Python312\site-packages\pandas\io\parsers\readers.py:1880, in TextFileReader._make_engine(self, f, engine)
       1878     if "b" not in mode:
       1879         mode += "b"
    -> 1880 self.handles = get_handle(
       1881     f,
       1882     mode,
       1883     encoding=self.options.get("encoding", None),
       1884     compression=self.options.get("compression", None),
       1885     memory_map=self.options.get("memory_map", False),
       1886     is_text=is_text,
       1887     errors=self.options.get("encoding_errors", "strict"),
       1888     storage_options=self.options.get("storage_options", None),
       1889 )
       1890 assert self.handles is not None
       1891 f = self.handles.handle
    

    File ~\AppData\Roaming\Python\Python312\site-packages\pandas\io\common.py:873, in get_handle(path_or_buf, mode, encoding, compression, memory_map, is_text, errors, storage_options)
        868 elif isinstance(handle, str):
        869     # Check whether the filename is to be opened in binary mode.
        870     # Binary mode does not support 'encoding' and 'newline'.
        871     if ioargs.encoding and "b" not in ioargs.mode:
        872         # Encoding
    --> 873         handle = open(
        874             handle,
        875             ioargs.mode,
        876             encoding=ioargs.encoding,
        877             errors=errors,
        878             newline="",
        879         )
        880     else:
        881         # Binary mode
        882         handle = open(handle, ioargs.mode)
    

    FileNotFoundError: [Errno 2] No such file or directory: 'amazon_products.csv'



```python
!pip install seaborn

```

    Collecting seaborn
      Using cached seaborn-0.13.2-py3-none-any.whl.metadata (5.4 kB)
    Requirement already satisfied: numpy!=1.24.0,>=1.20 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from seaborn) (2.3.1)
    Requirement already satisfied: pandas>=1.2 in c:\users\hp\appdata\roaming\python\python312\site-packages (from seaborn) (2.2.3)
    Requirement already satisfied: matplotlib!=3.6.1,>=3.4 in c:\users\hp\appdata\roaming\python\python312\site-packages (from seaborn) (3.9.2)
    Requirement already satisfied: contourpy>=1.0.1 in c:\users\hp\appdata\roaming\python\python312\site-packages (from matplotlib!=3.6.1,>=3.4->seaborn) (1.3.0)
    Requirement already satisfied: cycler>=0.10 in c:\users\hp\appdata\roaming\python\python312\site-packages (from matplotlib!=3.6.1,>=3.4->seaborn) (0.12.1)
    Requirement already satisfied: fonttools>=4.22.0 in c:\users\hp\appdata\roaming\python\python312\site-packages (from matplotlib!=3.6.1,>=3.4->seaborn) (4.53.1)
    Requirement already satisfied: kiwisolver>=1.3.1 in c:\users\hp\appdata\roaming\python\python312\site-packages (from matplotlib!=3.6.1,>=3.4->seaborn) (1.4.5)
    Requirement already satisfied: packaging>=20.0 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from matplotlib!=3.6.1,>=3.4->seaborn) (24.2)
    Requirement already satisfied: pillow>=8 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from matplotlib!=3.6.1,>=3.4->seaborn) (11.2.1)
    Requirement already satisfied: pyparsing>=2.3.1 in c:\users\hp\appdata\roaming\python\python312\site-packages (from matplotlib!=3.6.1,>=3.4->seaborn) (3.1.4)
    Requirement already satisfied: python-dateutil>=2.7 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from matplotlib!=3.6.1,>=3.4->seaborn) (2.9.0.post0)
    Requirement already satisfied: pytz>=2020.1 in c:\users\hp\appdata\roaming\python\python312\site-packages (from pandas>=1.2->seaborn) (2024.1)
    Requirement already satisfied: tzdata>=2022.7 in c:\users\hp\appdata\roaming\python\python312\site-packages (from pandas>=1.2->seaborn) (2025.1)
    Requirement already satisfied: six>=1.5 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from python-dateutil>=2.7->matplotlib!=3.6.1,>=3.4->seaborn) (1.17.0)
    Using cached seaborn-0.13.2-py3-none-any.whl (294 kB)
    Installing collected packages: seaborn
    Successfully installed seaborn-0.13.2
    


```python
df.info()
df.describe()
```


```python
deals = df[df["Price"] <= 1000].sort_values("Price")
deals
```


```python
top_reviews = df.sort_values("Reviews", ascending=False).head(5)
top_reviews
```


```python
plt.figure(figsize=(10,6))
sns.scatterplot(data=df, x="Rating", y="Price", size="Reviews", hue="Product", legend=False)
plt.title("Product Price vs Rating")
plt.xlabel("Rating")
plt.ylabel("Price")
plt.grid(True)
plt.show()
```


---
**Score: 5**