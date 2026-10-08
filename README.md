Task 19 – Filter Dataset Records
Veda Technology – AI & ML Track
Project Overview

This project demonstrates how to filter dataset records using Python and Pandas. A Student Performance Dataset is created and different conditions are applied to retrieve specific records.

Objective
Learn dataset filtering using Pandas.
Apply Boolean conditions.
Use comparison operators.
Use & (AND) and | (OR) operators.
Filter records using multiple conditions.
Count the number of filtered records.
Technologies Used
Python
Pandas
Jupyter Notebook
Dataset Details

The dataset contains student information including:

Student ID
Name
Age
Gender
Course
Marks
Attendance
City
Filtering Operations

1. Marks Greater Than 80

df[df["Marks"] > 80]

2. Students From Pune

df[df["City"] == "Pune"]

3. Marks Greater Than 80 AND Attendance Greater Than 85

df[(df["Marks"] > 80) & (df["Attendance"] > 85)]

4. Students From Pune OR Mumbai

df[(df["City"] == "Pune") | (df["City"] == "Mumbai")]

5. MCA Students With Marks Greater Than or Equal to 85

df[(df["Course"] == "MCA") & (df["Marks"] >= 85)]

6. Attendance Between 80 and 90

df[(df["Attendance"] >= 80) & (df["Attendance"] <= 90)]
Key Concepts
Pandas DataFrame
Boolean Indexing
Conditional Filtering
Comparison Operators
AND (&)
OR (|)
Multiple Conditions
Record Counting
Output

The notebook displays the original dataset, filtered DataFrames, and the number of records returned by each filtering condition.

Conclusion

This project successfully demonstrates how Pandas can be used to filter relevant records from a dataset. These filtering techniques are useful in data analysis, data preprocessing, machine learning, and artificial intelligence projects.
