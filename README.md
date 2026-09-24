# Numpy-and-panda-assignment
NumPy and Pandas Data Analysis
Project Overview

This project focuses on performing basic data analysis using NumPy and Pandas in Python.

The assignment demonstrates how to work with NumPy arrays, Pandas Series, and Pandas DataFrames. It includes numerical calculations, indexing, slicing, filtering, grouping, and data manipulation using real-world temperature and transaction datasets.

Objectives

The main objectives of this project are:

To create and work with NumPy arrays.
To perform numerical calculations using NumPy.
To understand array indexing and slicing.
To create and manipulate Pandas Series.
To create and analyze Pandas DataFrames.
To apply filtering and aggregation techniques.
To understand basic real-world data analysis using Python.
Technologies Used
Python
NumPy
Pandas
Google Colab
Installation

NumPy and Pandas can be installed using:

!pip install numpy pandas

Import the libraries:

import numpy as np
import pandas as pd
Project Structure
NumPy-Pandas-Data-Analysis/
│
├── numpy_pandas_assignment.ipynb
├── README.md
└── requirements.txt
Assignment Tasks
1. NumPy Array Operations

A one-dimensional NumPy array was created using weekly temperature data.


The following operations were performed:

Checked the shape of the array.
Checked the data type.
Counted the number of elements.
Converted Celsius temperatures to Fahrenheit.
Found maximum temperature.
Found minimum temperature.
Calculated mean temperature.
Performed array indexing and slicing.
2. NumPy 2D Array

A two-dimensional array was created containing temperature data for two weeks.

The following operations were performed:

Checked the shape.
Checked the data type.
Counted total elements.
Extracted Week 1 temperatures.
Extracted Week 2 temperatures.
Extracted weekend temperatures.
Used 2D array slicing.
3. Pandas Series

A Pandas Series was created containing student marks with custom rank labels.



The following operations were performed:

Accessed values using integer positions.
Used loc for label-based indexing.
Used iloc for position-based indexing.
Applied Boolean filtering.
Modified Series values.
Removed an entry.
Calculated CGPA.
4. Pandas DataFrame

A transaction DataFrame was created containing:

Transaction ID
Product Category
Region
Amount

The DataFrame was used to perform:

Data exploration.
Head and tail inspection.
Shape and column inspection.
Data type inspection.
Column selection.
Row filtering.
Category value counts.
Unique value identification.
Grouping by Region.
Mean amount calculation.
5. DataFrame Manipulation

The following manipulations were performed:

Updated the amount for Transaction ID 102.
Created a Discount column.
Calculated a 10% discount.
Removed Transaction ID 109.
Deleted the Discount column.
Key Concepts Learned

Through this assignment, the following concepts were practiced:

NumPy
Array creation
Array properties
Mathematical operations
Indexing
Slicing
1D arrays
2D arrays
Aggregation functions
Pandas
Series creation
DataFrame creation
loc
iloc
Boolean filtering
head()
tail()
shape
dtypes
value_counts()
unique()
groupby()
Data manipulation
Sample NumPy Conversion

The Celsius-to-Fahrenheit conversion was performed using:


Sample DataFrame Analysis

Mean transaction amount by region was calculated using:

transactions.groupby('Region')['Amount'].mean()
Conclusion

This project provided practical experience in using NumPy and Pandas for data analysis. NumPy was used for numerical calculations and array operations, while Pandas was used for structured data manipulation and analysis.

The assignment helped build a foundation in Python data analysis techniques such as indexing, slicing, filtering, aggregation, grouping, and data modification.



Aspiring Data Analyst

Skills Practiced
Python
NumPy
Pandas
Data Analysis
Data Manipulation
Data Exploration
