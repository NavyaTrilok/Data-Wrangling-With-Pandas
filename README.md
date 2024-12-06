Pandas questions to practice:

1. DataFrame Manipulation:
Given a DataFrame df with columns [‘Name’, ‘Age’, ‘Gender’, ‘Department’, ‘Salary’], perform the following tasks:
1)Filter the DataFrame to include only rows where the Salary is greater than 50,000.
2)Group the DataFrame by Department and calculate the mean Salary for each department.
3)Add a new column Salary_Hike that increases each employee’s salary by 10%.
4)Replace missing values in the Age column with the median age.

2. Data Aggregation:
You have a DataFrame sales_df with columns [‘Date’, ‘Product’, ‘Region’, ‘Sales’]. Perform the following:
1)Create a pivot table that shows the total sales for each Product by Region.
2)Calculate the cumulative sales by Product over time.
3)Find the top 3 Product with the highest total sales.

3. Handling Missing Data:
Consider a DataFrame df with columns [‘ID’, ‘Age’, ‘Gender’, ‘Income’, ‘Spending_Score’]. Some of the data points in Age and Income are missing. Perform the following:
1)Count the number of missing values in each column.
2)Impute the missing Age values with the median age, and Income with the mean income.
3)Drop rows where more than two columns have missing values.

4. Data Transformation:
Given a DataFrame orders_df with columns [‘OrderID’, ‘CustomerID’, ‘Product’, ‘Quantity’, ‘Price’], perform the following:
1)Create a new column Total_Cost that is the product of Quantity and Price.
2)Sort the DataFrame by CustomerID and Total_Cost in descending order.
3)Extract all unique products bought by each customer.
4)Normalise the Price column using min-max scaling.
