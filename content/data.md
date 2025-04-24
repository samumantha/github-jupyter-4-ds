# Working with data in Python

:::{objectives}
- Understanding how to structure data in your projects
- Reading data with Pandas from disk or a web resource
:::

:::{note} Example data: Weather data from two Norwegian cities

We will experiment with some example weather data obtained from [Norsk
KlimaServiceSenter](https://seklima.met.no/observations/), Meteorologisk
institutt (MET) (CC BY 4.0).  The data is in CSV format (comma-separated
values) and contains daily and monthly weather data for two cities in Norway:
Oslo and Tromsø. You can browse the data
[here in the lesson repository](https://github.com/coderefinery/data-visualization-python/tree/main/data).

We will use the Pandas library to read the data into a dataframe.

Pandas can read from and write to a large set of formats
([overview of input/output functions and formats](https://pandas.pydata.org/pandas-docs/stable/reference/io.html)).
We will load a CSV file directly from the web. Instead of using a web URL we
could use a local file name instead.

Pandas dataframes are a great data structure for **tabular data**.
:::

## Reading data into a dataframe

We can try this together in a notebook:
Using Pandas we can **merge, join, concatenate, and compare**
dataframes, see <https://pandas.pydata.org/pandas-docs/stable/user_guide/merging.html>.

Let us try to **concatenate** two dataframes: one for Tromsø weather data (we
will now load monthly values) and one for Oslo:
```{code-block} python
---
emphasize-lines: 8
---
import pandas as pd

url_prefix = "https://raw.githubusercontent.com/coderefinery/data-visualization-python/main/data/"

data_tromso = pd.read_csv(url_prefix + "tromso-monthly.csv")
data_oslo = pd.read_csv(url_prefix + "oslo-monthly.csv")

data_monthly = pd.concat([data_tromso, data_oslo], axis=0)

# let us print the combined result
data_monthly
```

### Data preprocessing

There is a problem which we may not see yet: Dates
are not in a standard date format (YYYY-MM-DD). We can fix this:
```python
# replace mm.yyyy to date format
data_monthly["date"] = pd.to_datetime(list(data_monthly["date"]), format="%m.%Y")
```

With Pandas it is possible to do a lot more (adjusting missing values, fixing
inconsistencies, changing format).


## What is in a dataframe?

The name pandas is derived from the term "**pan**el **da**ta".

```{figure} img/pandas/dataframe.svg
:alt: A pandas dataframe object is composed of rows and columns.

A pandas dataframe object is composed of rows and columns.
```

Let us explore these together in the notebook (run these in separate cells):
```python
# print an overview of the dataset
data_monthly

# print the first 5 rows
data_monthly.head()

# print the last 5 rows
data_monthly.tail()

# print all column titles - no parentheses here
data_monthly.columns

# show which data types were detected
data_monthly.dtypes

# print table dimensions - no parentheses here
data_monthly.shape

# print one column
data_monthly["max temperature"]

# get some statistics
data_monthly["max temperature"].describe()

# what was the maximum temperature?
data_monthly["max temperature"].max()

# print all rows where max temperature was above 20
data_monthly[data_monthly["max temperature"] > 20.0]
```


## Where to learn more about pandas

Pandas is extremely powerful and there is a lot that can be done and there are
great resources to explore more:
- [Getting started guide](https://pandas.pydata.org/getting_started.html)
  (including tutorials and a 10 minute flash intro)
- [10 minutes to pandas tutorial](https://pandas.pydata.org/docs/user_guide/10min.html)
- [Pandas documentation](https://pandas.pydata.org/docs/)
- [Cheatsheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)
- [Cookbook](https://pandas.pydata.org/docs/user_guide/cookbook.html#cookbook)
- [Data Carpentry lesson](https://datacarpentry.org/python-ecology-lesson/) "Data Analysis and Visualization in Python for Ecologists"
  (useful not only for ecologists)


::::{challenge} Work with tabular data using Python

You might be an Excel expert, but how about doing the same things you do with Excel with python? What is the advantage compared to doing it with Excel?

1. Try running some of the  commands above in a jupyter notebook and look at their output
2. Calculate the median of the column "max temperature". What is its value? To know how to calculate the median, check the documentation of [Pandas DataFrame class](https://pandas.pydata.org/docs/reference/frame.html).
3. Sort the data by the column "max temperature". Which city was the hottest? Use the Pandas documentation to know how to sort.
4. (Advanced) Compute the differences of max temperatures between Olso and Tromsø for each month (hint: you will need to make a pivot table...)
::::



---

:::{keypoints}
- Loading data with python is easy and through Jupyter notebooks one can interact and understand the data at hand
- Pandas are the most popular option when dealing with tabular data
- There are many more types of data and libraries available, please explore which data you would like to load.
:::
