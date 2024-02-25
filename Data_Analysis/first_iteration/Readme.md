# Essential Libraries for running the codes

This README file provides essential information for running the project on an external machine. To ensure the smooth execution of the code, it is crucial to follow these instructions and import the necessary Python libraries.

```python
import matplotlib.pyplot as plt
import seaborn as sns
from chart_studio import plotly as py
import plotly.graph_objs as go
from plotly.offline import download_plotlyjs, init_notebook_mode, plot, iplot
%matplotlib inline
import numpy as np
from pandas.api.types import is_string_dtype
from pandas.api.types import is_numeric_dtype
import pandas as pd
