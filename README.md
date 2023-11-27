# Exploratory-Data-Analysis (EDA)
Exploratory data analysis (EDA) is used by data scientists to analyze and investigate data sets and summarize their main characteristics, often employing data visualization methods.
Here, as an aspiring Data Scientist , i have done an EDA of a dataset of employees working in ABC company.
Following are certain steps to perform EDA:
## Step1: Import Python libraries
Import all libraries which are required for our analysis, such as Data Loading, Statistical analysis, Visualizations, Data Transformations, Merge and Joins, etc.

## Step2: Reading dataset
The Pandas library offers a wide range of possibilities for loading data into the pandas DataFrame from files like JSON, .csv, .xlsx, .sql, .pickle, .html, .txt, images etc.
Most of the data are available in a tabular format of CSV files. It is trendy and easy to access. Using the read_csv() function, data can be converted to a pandas DataFrame.

## Step3. Data Preprocessing.
The main goal of data understanding is to gain general insights about the data, which covers the number of rows and columns, values in the data, datatypes, and Missing values in the dataset.
### Deriving statistical summary
Statistics summary gives a high-level idea to identify whether the data has any outliers, data entry error, distribution of data such as the data is normally distributed or left/right skewed.

In python, this can be achieved using describe()

describe() function gives all statistics summary of data

describe()– Provide a statistics summary of data belonging to numerical datatype such as int, float.

### Checking for duplicate , null values
nunique() based on several unique values in each column and the data description, we can identify the continuous and categorical columns in the data. Duplicated data can be handled or removed based on further analysis.

isnull() is widely been in all pre-processing steps to identify null values in the data
In our example, data.isnull().sum() is used to get the number of missing records in each column.

### Dropping or Filling data
we can drop one more columns or rows with null values. 
or can fill it with 0 , mean or median.

## Step4. Data Analysing 
Retreiving meaningfull insights.

## Step5. Data Visualization
There are different forms of graphs like line graph. scatter plot, bar plot etc for the visualization of the data .
Data visualization is essential; we must decide what charts to plot to better understand the data.
Here i have plotted the correlation between the salary and age of the employees using a sactter plot .
Matplotlib is a Python 2D plotting library used to draw basic charts we use Matplotlib.
Seaborn is also a python library built on top of Matplotlib that uses short lines of code to create and style statistical plots from Pandas and Numpy.
