In this program, we demonstrate how to use the Pandas library to work with Series and DataFrame data structures. We cover basic operations and data selection in both 1D Series and 2D DataFrame. The code is written in Python, and it requires the Pandas library to be installed.

Series Data Structure (1D)
A Series is a one-dimensional labeled array, similar to a Python list or array, but with additional functionality.
Creating a Series:
We create a Series called 's1' with the values [10, 20, 30, 40, 50, 60].

Accessing Index and Data Types:
We print the index and data types of the Series.

Accessing Values:
We access the value at index location 3 in the Series.

Series with Custom Index:
We create another Series called 's2' with values [10, 20, 30, 40, 50, 60] and custom index labels ['a', 'b', 'c', 'd', 'e', 'f'].

Data Selection in Series:
We demonstrate various methods to select data from the Series, including single label, slicing, and conditional filtering.

DataFrame Data Structure (2D)
A DataFrame is a 2D labeled data structure with columns of potentially different types.
Creating a DataFrame:
We create a DataFrame called 'df' from a dictionary 'dic1' containing 'Name', 'Age', and 'Weight' as columns and corresponding data.

Accessing Index, Columns, and Values:
We print the index, columns, and values attributes of the DataFrame.

Changing Row Index:
As a bonus step, we change the row index labels to 'R1', 'R2', 'R3', 'R4'.

Data Selection in a DataFrame
We create a DataFrame 'df' with custom index labels ['a', 'b', 'c', 'd'] using the dictionary 'dic1'.
Accessing Columns:
We demonstrate different ways to select columns from the DataFrame.

Accessing Rows:
We show how to select rows using index locations and label-based selection using the 'loc' and 'iloc' methods.

Note: The code provided in this program is meant for illustrative purposes and may not include all possible operations and scenarios. Feel free to modify and extend it to explore further functionalities of Pandas Series and DataFrame.

Prerequisites:

Python installed
Pandas library installed (pip install pandas)
Run the Code:
To run the code, you can copy and paste the provided snippets into a Python script or an interactive Python environment (e.g., Jupyter Notebook). Ensure that you have Pandas installed before running the code.

Enjoy exploring and analyzing data with Pandas!
