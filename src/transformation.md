## Data Aggregation Process

Use Azure account, and HDInsight clusters to perform the following aggregate queries.

**1.** Create a table showing the number of salespeople with attrition, containing the "Attrition" and "MonthlyIncome" columns.
Add a new column called "attrition_count" which contains the 'count' function.
Do the same to show the number of salespeople with non-attrition.


**2.** Create a table to show the average, minimum, and maximum monthly income for the salespeople with attrition.
Create two more tables to show the same stats for those with non-attrition, and then for all salespeople.

**3.** Create a table for the attrition salespeople showing the monthly income and the count of the salespeople making that amount of income. 
Requires the GROUPBY command.
Do the same to show the details for those with non-attrition.
