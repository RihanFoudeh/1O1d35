# Read: Class 12

## _Pandas_ in Python:

### Importing:

```python
In [1]: import numpy as np

In [2]: import pandas as pd
```

#### Object Creation:

* Creating a Series by passing a list of values, letting pandas create a default integer index:

```python
In [3]: s = pd.Series([1, 3, 5, np.nan, 6, 8])
```

* Creating a DataFrame by passing a NumPy array, with a datetime index and labeled columns:

```python
In [5]: dates = pd.date_range('20130101', periods=6)
```

# class pandas

* class pandas.DataFrame(data=None, index=None, columns=None, dtype=None, copy=False)

* Two-dimensional, size-mutable, potentially heterogeneous tabular data. Data structure also contains labeled axes (rows and columns). Arithmetic operations align on both row and column labels. Can be thought of as a dict-like container for Series objects. The primary pandas data structure.

## Parameters

* datandarray (structured or homogeneous), Iterable, dict, or DataFrame Dict can contain Series, arrays, constants, dataclass or list-like objects. If data is a dict, column order follows insertion-order.
* Changed in version 0.25.0: If data is a list of dicts, column order follows insertion-order.

* DataFrame.to_numpy() gives a NumPy representation of the underlying data. Note that this can be an expensive operation when your DataFrame has columns with different data types, which comes down to a fundamental difference between pandas and NumPy: NumPy arrays have one dtype for the entire array, while pandas DataFrames have one dtype per column. When you call DataFrame.to_numpy(), pandas will find the NumPy dtype that can hold all of the dtypes in the DataFrame. This may end up being object, which requires casting every value to a Python object.
* DataFrame.to_numpy() does not include the index or column labels in the output.
* describe() shows a quick statistic summary of your data.
