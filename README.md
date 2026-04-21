# NAME : SAUMYA SHREE
# PRN : 25070123161
# Theory:
* Data preprocessing in python involves cleaning, transforming, and preparing raw data for analysis using tools like Pandas.
* import pandas- This line imports the pandas library.Pandas is used for data handling and analysis.
* import numpy- This line imports the NumPy library to perform numerical and array operations in python.
* pd.DataFrame-It is used to create a structured table (rows and columns) from data like lists, dictionaries, or arrays.
* df1.isna ()- It checks the DataFrame and returns a table showing True for missing (NaN) values and False for non-missing values.
* df1.notna()- It returns a DataFrame showing True for non-missing values and False for missing (NaN) values.
* df1.isna().sum()-It counts the total number of missing (NaN) values in each column of the DataFrame.
* df1.isna().sum(axis=1)- It counts the number of missing (NaN) values in each row of the DataFrame.
* df1.dropna ()-It removes rows containing any missing (NaN) values from the DataFrame.
* df1.dropna(axis=1)-It removes columns that contain any missing (NaN) values from the DataFrame.
* df1.fillna(value='DEFAULT')-It replaces all missing (NaN) values in the DataFrame with the specified value 'DEFAULT'.
* df1.fillna(0)-It replaces all missing (NaN) values in the DataFrame df1 with 0 .
* df1.fillna(df1.mean())-It replaces missing (NaN) values in each column of df1 with that column’s mean value.
* pd.DataFrame(data)-It creates a DataFrame (tabular structure of rows and columns) from the given data (like lists, dictionaries, or arrays).
* df.replace("-", np.nan, inplace=True)-It replaces all occurrences of "-" in the DataFrame df with NaN (missing values) directly in the original DataFrame.
* df["Age"] = pd.to_numeric(df["Age"], errors='coerce') converts the Age column to numeric values, replacing invalid or non-numeric entries with NaN.
* df["Marks"] = pd.to_numeric(df["Marks"], errors='coerce') converts the Marks column to numeric values, replacing any invalid or non-numeric entries with NaN.
* df["Age"].fillna(df["Age"].mean(), inplace=True) replaces missing (NaN) values in the Age column with the mean of that column directly in the original DataFrame.
* df["Marks"].fillna(df["Marks"].median(), inplace=True) replaces missing (NaN) values in the Marks column with the median of that column directly in the original DataFrame.
* df["Department"].str.upper() converts all text values in the Department column to uppercase.
*pd.to_datetime(df["Admission_Date"], format="mixed", dayfirst=True) converts the Admission_Date column to datetime format, handling mixed date formats and interpreting the day before the month.
# Conclusion:
Data preprocessing ensures the dataset is clean, consistent, and ready for analysis by handling missing values, correcting data types, and standardizing formats, which improves the accuracy and reliability of results.

