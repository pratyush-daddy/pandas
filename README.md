# Different ways to create Pandas Dataframe

### Pandas DataFrame is a 2-dimensional labeled data structure like any table with rows and columns. The size and values of the dataframe are mutable,i.e., can be modified. It is the most commonly used pandas object. Pandas DataFrame can be created in multiple ways. Let’s discuss different ways to create a DataFrame one by one.

#### DataFrame() function is used to create a dataframe in Pandas. The syntax of creating dataframe is:

`pandas.DataFrame(data, index, columns)`

#### where,
#### data: It is a dataset from which dataframe is to be created. It can be list, dictionary, scalar value, series, ndarrays, etc.
#### index: It is optional, by default the index of the dataframe starts from 0 and ends at the last data value(n-1). It defines the row label explicitly.
#### columns: This parameter is used to provide column names in the dataframe. If the column name is not defined by default, it will take a value from 0 to n-1.
