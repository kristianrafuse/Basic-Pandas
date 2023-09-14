Basic Pandas
-------
Using Pandas and Jupyter Notebook I create a report that analyzes district-wide standardized test results, performs the necessary calculations and creates a high-level view of key metrics that are stored in several DataFrames.

District Summary
------
* Total number of unique schools
* Total students
* Total budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

School Summary
-------
* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

Analysis
-------
* Sort the schools by % Overall Passing in descending order and display the top 5 rows.
* Sort the schools by % Overall Passing in ascending order and display the top 5 rows.
* Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.
* Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.
* Create a table that breaks down school performance based on average spending ranges (per student).
* Use pd.cut to categorize spending based on the bins.
* Calculate mean scores per spending range.
* Create a new DataFrame that shows school performance based on the "School Type".
