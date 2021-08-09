## Our topic is about Pandas:

![pandas](https://cdn.activestate.com/wp-content/uploads/2020/10/everything-about-pandas.png)

### What is Pandas?

- pandas is a Python package providing fast, flexible, and expressive data structures designed to make working with “relational” or “labeled” data both easy and intuitive

### What kind of data does pandas handle?

>When working with tabular data, such as data stored in spreadsheets or databases, pandas is the right tool for you. 

>Pandas will help you to explore, clean, and process your data. 
>In pandas, a data table is called a DataFrame.

### How do I read and write tabular data?

- pandas supports the integration with many file formats or data sources out of the box (csv, excel, sql, json, parquet). 

>Importing data from each of these data sources is provided by function with the prefix **read_*.** Similarly, the **to_*** methods are used to store data.

### How do I select a subset of a table?

-To select a single column, use square brackets **[]** with the column name of the column of interest.

### How to create plots in pandas?

- pandas provides plotting your data using Matplotlib. 

- You can pick the plot type (scatter, bar, boxplot,…) corresponding to your data.

- Using the plot() method and it can works on both Series and DataFrame.

### How to reshape the layout of tables?

- Change the structure of your data table can be done in multiple ways:
  > You can melt() your data table from wide to long/tidy form or pivot() from long to wide format.
  > With aggregations built-in, a pivot table is created with a single command.

### How to combine data from multiple tables?

- Multiple tables can be concatenated both column wise and row wise as database-like.

- **join/merge** operations are provided to combine multiple tables of data.

### How to manipulate textual data? 

-Pandas provides a wide range of functions to clean textual data and extract useful information from it.

- For example:

 >**Series.str.contains()**, **Series.str.extract()**