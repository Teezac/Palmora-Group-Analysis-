# Palmora-Group-Analysis-

Step 1: Data Preparation

Import the employee data into Power BI.

Perform proper cleaning, such as:

1.	Remove employees with missing salaries or departments marked as "NULL".

2.	Assign a generic gender (e.g., “Undisclosed”) to employees who didn’t specify their gender.

Step 2 Gender Distribution Analysis

1.	Create a bar chart:

o	Axis: Region or Department

o	Value: Count of Employees by Gender

2.	Use a slicer to filter by region/department.

3.	Use a pie chart to show overall gender distribution

**Visualizations:**

•	Bar Chart: "Gender Distribution by Region"

•	Pie Chart: "Overall Gender Distribution"

 **Measures:**

DAX

CopyEdit

Gender Count = COUNT('Employee'[Gender])

Gender Percentage = 

DIVIDE(
    CALCULATE(COUNT('Employee'[Gender])),
    CALCULATE(COUNT('Employee'[Gender]), ALL('Employee'[Gender]))

Step 3: Ratings Insights Based on Gender

Steps:

1.	Create a histogram or box plot:

o	Axis: Rating

o	Value: Count of Employees by Gender

2.	Use a slicer to filter by gender.

3.	Create a measure to calculate average rating by gender.

Visualization:

•	Histogram: "Ratings Distribution by Gender"

Ratings Insights Based on Gender

 Steps:

1.	Create a histogram or box plot:

o	Axis: Rating

o	Value: Count of Employees by Gender

2.	Use a slicer to filter by gender.

3.	Calculate the average rating by gender using a measure.
📈 Visualization:

•	Histogram Title: "Ratings Distribution by Gender"

•	Box Plot Title: "Ratings Comparison by Gender"

Salary Structure and Gender Pay Gap Analysis
  
  Steps:

1.	Create a scatter plot:

o	X-axis: Salary

o	Y-axis: Gender

2.	Calculate the average salary by gender using a measure.

3.	Identify departments and regions with significant pay gaps.







