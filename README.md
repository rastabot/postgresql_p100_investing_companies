# postgresql_p100_investing_companies
SQL project fo practicum100 Data Analyst Program

From the given schema, write sql queries that answer the following questions:

1. Calculate how many companies have closed down

2. Print the amount of money raised for news companies in the US. Use data from the company table. Sort the resulting table in descending order of value in the funding_total field 

3. Find the total price of the purchases of companies by other organizations in USD. Select the transactions that were carried out only in cash from 2011 to 2013 inclusive.

4. Print names, last names, and the Twitter accounts of the people whose Twitter usernames begin with 'Silver'.

5. Print all information about the people whose Twitter usernames contain the substring 'money' and whose last name begins with 'K'.

6. For each country, print the total investment that companies registered in that country have received. Sort the data in descending order.

7. Create a table that includes the date the record was created in the table, together with the minimum and maximum values of the attracted investments. In addition to that, leave all records in the table where the minimum value of the investment is not zero and is also not equal to the maximum funding value.

8. Create a field with these categories: high_activity — funds that invest in 100 or more companies middle_activity — funds that invest in 20 to 100 companies low_activity — funds that invest in fewer than 20 companies Print all the fields in the fund table and the new category field.

9. For each of the categories assigned in the previous task, calculate the average number of investment rounds in which the fund participated, rounded to the nearest integer. Print the categories and the average number of investment rounds. Sort the table in ascending order of the average.

10. Get a table with the ten most actively investing countries. Determine the activity of a country by the average number of companies in which the funds of this country invest. For each country, calculate the minimum, maximum, and average number of companies in which funds founded from 2010 to 2012, inclusive, have invested. Make sure to take only the year part of the date. Exclude from the table the countries with funds that have the minimum number of invested companies equal to zero.

11. Print names and last names of all startup employees. Add a field with the name of the educational institution that the employee graduated from if this information is known.

12. For each company, find the number of educational institutions that its employees graduated from. Print the names of the companies and the number of unique names of educational institutions. Create a list of the top 5 companies by the number of universities.

13. Create a list of the closed companies for which the first round of funding was the last one.

14. Create a list of IDs of the employees that work for the companies selected in the previous task.

15. Create a table with the IDs of the employees from the previous task together with the educational institution they have graduated from

16. Count the number of educational institutions for each employee from the previous task

17. Print the average number of educational institutions that employees of different companies have graduated from. Just print one record, there is no need for grouping here. Use a subquery to find the average of the data you got from the statement in the previous task

18. Print the average number of educational institutions that Facebook employees graduated from.

19. Create a table that consists of the following fields: name_of_fund — the name of the fund name_of_company — the name of the company amount — the investments that the company attracted in the round The table must include data on companies with more than six important milestones in their history, and that had funding rounds that took place in 2012 and 2013.

20. Get a table with the following fields: The name of the buying company The price of the purchase The name of the company that was bought The investments invested in the purchased company The date when the company was acquired A ratio that shows how many times the purchase price exceeded the investments in the company, rounded up to the nearest integer. Do not count those purchases in which the purchase price is equal to zero. Apart from that, if the investment in an acquired company is zero, exclude that company from the table too. Sort the table by the purchase price from highest to lowest. Limit the table to the first ten entries

21. Get a table with the names of companies from the social category that received funding from 2010 to 2013, together with the number of the month when the funding round took place

22. For each month from 2010 to 2013, find the number of unique funds registered in the US. Get a table that contains the following fields: The number of the month The number of unique funds from the US The number of purchases The total turnover of transactions per month

23. Create a table with the average investment for each country in 2011, 2012, and 2013. Print the data for each year in a separate field. Sort the table by 2011 average investment from highest to lowest. Note that we only want to consider countries with data across all three of these years
