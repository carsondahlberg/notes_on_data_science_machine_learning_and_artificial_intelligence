Title: Module Basics
Slug: module_basics
Summary: Module Basics
Date: 2016-12-01 12:00
Category: Python
Tags: Basics
Authors: Chris Albon




```python
# Import the module sys
import sys
```


```python
# Import just the sqrt function from the module math
from math import sqrt
```


```python
# Import the pandas module as the alias pd
import pandas as pd
```


```python
# View all the names in a module
dir(pd)
```




    ['Categorical',
     'DataFrame',
     'DateOffset',
     'DateRange',
     'DatetimeIndex',
     'ExcelFile',
     'ExcelWriter',
     'Expr',
     'Float64Index',
     'HDFStore',
     'Index',
     'Int64Index',
     'LooseVersion',
     'MultiIndex',
     'NaT',
     'Panel',
     'Panel4D',
     'Period',
     'PeriodIndex',
     'Series',
     'SparseArray',
     'SparseDataFrame',
     'SparseList',
     'SparsePanel',
     'SparseSeries',
     'SparseTimeSeries',
     'Term',
     'TimeGrouper',
     'TimeSeries',
     'Timestamp',
     'WidePanel',
     '__builtins__',
     '__cached__',
     '__doc__',
     '__docformat__',
     '__file__',
     '__initializing__',
     '__loader__',
     '__name__',
     '__package__',
     '__path__',
     '__version__',
     '_np_version',
     '_np_version_under1p6',
     '_np_version_under1p7',
     '_np_version_under1p8',
     '_sparse',
     'algos',
     'bdate_range',
     'compat',
     'computation',
     'concat',
     'core',
     'crosstab',
     'cut',
     'date_range',
     'datetime',
     'datetools',
     'describe_option',
     'eval',
     'ewma',
     'ewmcorr',
     'ewmcov',
     'ewmstd',
     'ewmvar',
     'ewmvol',
     'expanding_apply',
     'expanding_corr',
     'expanding_corr_pairwise',
     'expanding_count',
     'expanding_cov',
     'expanding_kurt',
     'expanding_max',
     'expanding_mean',
     'expanding_median',
     'expanding_min',
     'expanding_quantile',
     'expanding_skew',
     'expanding_std',
     'expanding_sum',
     'expanding_var',
     'factorize',
     'fama_macbeth',
     'get_dummies',
     'get_option',
     'get_store',
     'groupby',
     'hashtable',
     'index',
     'infer_freq',
     'info',
     'io',
     'isnull',
     'json',
     'lib',
     'load',
     'lreshape',
     'match',
     'melt',
     'merge',
     'msgpack',
     'notnull',
     'np',
     'offsets',
     'ols',
     'option_context',
     'options',
     'ordered_merge',
     'pandas',
     'parser',
     'period_range',
     'pivot',
     'pivot_table',
     'plot_params',
     'pnow',
     'qcut',
     'read_clipboard',
     'read_csv',
     'read_excel',
     'read_fwf',
     'read_gbq',
     'read_hdf',
     'read_html',
     'read_json',
     'read_msgpack',
     'read_pickle',
     'read_sql',
     'read_stata',
     'read_table',
     'reset_option',
     'rolling_apply',
     'rolling_corr',
     'rolling_corr_pairwise',
     'rolling_count',
     'rolling_cov',
     'rolling_kurt',
     'rolling_max',
     'rolling_mean',
     'rolling_median',
     'rolling_min',
     'rolling_quantile',
     'rolling_skew',
     'rolling_std',
     'rolling_sum',
     'rolling_var',
     'rolling_window',
     'save',
     'scatter_matrix',
     'set_eng_float_format',
     'set_option',
     'show_versions',
     'sparse',
     'stats',
     'to_datetime',
     'to_msgpack',
     'to_pickle',
     'to_timedelta',
     'tools',
     'tseries',
     'tslib',
     'unique',
     'util',
     'value_counts',
     'value_range',
     'version',
     'wide_to_long']

