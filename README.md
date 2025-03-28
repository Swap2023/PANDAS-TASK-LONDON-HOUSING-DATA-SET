# PANDAS#-TASK-LONDON-HOUSING-DATA-SET.

**#LONDON HOUSING DATA

**Q. 1) Convert the Datatype of 'Date' column to Date-Time format. 
Q. 2) Add a new column ''year'' in the dataframe, which contains years only.(B.2) Add a new column ''month'' as 2nd column in the dataframe, which contains month only.
Q. 3) Remove the columns 'year' and 'month' from the dataframe. 
Q. 4) Show all the records where 'No. of Crimes' is 0. And, how many such records are there ?
Q. 5) What is the maximum & minimum 'average_price' per year in england ?
Q. 6) What is the Maximum & Minimum No. of Crimes recorded per area ? 
Q. 7) Show the total count of records of each area, where average price is less than 100000.

The commands that we used in this project :

* import pandas as pd -- To import Pandas library
* pd.read_csv - To import the CSV file in Jupyter notebook
* df.count() - It counts the no. of non-null values of each column.
* df.isnull().sum() - It detects the missing values from the dataframe.
* import seaborn as sns - To import the Seaborn library.
* import matplotlib.pyplot as plt - To import the Matplotlib library.
* sns.heatmap(df.isnull()) - It will show the all columns & missing values in them in heat map form.
* plt.show() - To show the plot.
* df.dtypes - To show the datatype of each column.
* pd.to_datetime(df.Date_Time_Col) - Converts the data-type of Date-Time Column into datetime[ns] datatype.
* df.Time_Col.dt.year - Creating a new column with only year values
* df.Time_Col.dt.month - Creating a new column with only month values.
* df.insert( index , ‘new_column_name’, new_column_values) - To insert a New column at a particular position with values in it.
* df.drop(['Col_name'] , axis=1 , inplace = True) - To drop a column from the dataframe permanently.
* df.groupby(‘Col_name’) - To form groups of all unique values of the column.
* df[df.Col_1 = = ‘Element1’] - Filtering – We are accessing all records with Element1 only of Col_1.
* df.groupby(‘Col_1’)[‘Col_2’] .mean( ) - To create groups - Two Keys – Apply on Col_2 grouped by Col_1.****
