# Home Sales Challenge

Downloaded stater code file: Home_Sales_starter_code.ipynb

Renamed the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb.

Imported the necessary PySpark SQL functions for this assignment.

Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.

Created a temporary table called home_sales.

Answered the following questions using SparkSQL:

What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off 
your answer to two decimal places.

What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater 
than or equal to 2,000 square feet? Round off your answer to two decimal places.

What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and 
round off your answer to two decimal places.

Cached temporary table home_sales.

Checked if temporary table is cached.

Using the cached data, ran the query that filters out the view ratings with an average price of greater than or equal to $350,000. 
Determine the runtime and compare it to uncached runtime.

Partitioned by the "date_built" field on the formatted parquet home sales data.

Createed a temporary table for the parquet data.

Ran the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the 
runtime and compare it to uncached runtime.

Uncached the home_sales temporary table.

Verified that the home_sales temporary table is uncached using PySpark.


