# Power-BI-1-

# In this provided dataset I should perform belew instructions

Import the data and open the Power Query
The expense type column has some spelling and punctuation errors, correct them
Project names are not uniform, make it uniform.
The Currency column has some missing values, based on the amount, create a new custom column.
Condition: amount >= 1000, = INR; amount < 1000, = USD; else = EURO
Formula: (if [Currency] = null and [Amount] >= 1000 then "INR" else if [Currency] = null and [Amount] < 1000 then "USD" else [Currency] )
Convert the "amount" column to INR based on the "currency" column. Use the USD and Euro to INR exchange rates. Assume blank and INR values remain unchanged.
Create a measure to calculate the sum of reimbursed amount in INR.
Use the calculate function and check the total reimbursed amount for Project_B
Create a measure to check the count of declined requests.
Create a slicer visual for the Project and employee
Create a column chart for employees and reimbursement amount.
Create a pie chart for Project vs reimbursement amount

# I learnt 
"Power BI is an end-to-end enterprise business intelligence tool. It supports various layouts and connects with many data sources, offering flexibility in data presentation and analysis."
"Power Query functions as an ETL (Extract, Transform, Load) engine, enabling filtering, sorting, and the addition of new columns, which are essential for data manipulation."
Data Modeling in Power BI focuses on creating connections between tables, primarily involving two kinds of tables: Dimension (Primary) tables and Fact tables
"DAX (Data Analysis Expressions) is the language used to create formulas in Power BI, while M-language is used for scripting in Power Query."
"Effective visuals, such as KPI cards and bar charts, combined with robust data modeling, are central to Power BI’s capabilities in data analysis and reporting.
