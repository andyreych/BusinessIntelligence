# Final Project CTS3452
In this project, my team formed by Johana Danton , Decoda Williams , and myself Andy Rey decided to use the database of Northwind Traders, a fictitious organization that manages orders, products, customers, suppliers, and many other aspects of a small business to acts as a sample database to create the reports to solve business tasks using business intelligence tools such as Microsoft SQL Server, and Visual Studio. Furthermore, this project is classified in different data analysis phases such as: Ask, Prepare, Process, Analyze, Share, and Act. This phases have the goal to communicate our findings to the stakeholders of Northwind Traders in a concise manner and follow a clear path of our data analysis using the skills learned in our Business Intelligence Reporting Services Class (CTS3452).

# Ask phase
Stakeholders and upper management of Northwind Traders are asking the business intelligence team to create reports to answer the following questions:
* What was the sum of sales by each year of the company?
* How much each product category made in sales in each year followed by the product?
* Was the company able to hit the sales target each year?
* How much each product category made in sales represented in percentages last year?
* Which months were considered the most profitable ones last year?
* Who are our VIP customers and their country of origin?
* How many orders each employee have handled in total?


Important Notes:
* A VIP Customer is a customer that have orders totalling over $20,0000.
* The sales target varies from each year, from 1996 the sales target was $x, 1997 was x, and the current year 1998 the sales target is $x
                 

# Prepare phase
Since all of Northwind Traders data is stored internally in our database our team decided to create a diagram of the necessary tables to create the reports to answer the stakeholder questions.



Based on this diagram the business intelligence team decided to create the following reports:
* Sales by Year (1996-1997-1998)
* Times Sales Data for the year 1997. 
* Pie Charts by Product Category representing sales in percentages for the 1997 year. 
* Total Orders by Employee for the whole years(1996-1997-1998) 
* A list of VIP Customers that have orders totalling over $20,0000.

The business intelligence team decided to run SQL Queries in Microsoft SQL Server Management Studio for each Report: 
* Sales by Year (1996-1997-1998)
 ![image](https://user-images.githubusercontent.com/121314771/226076446-6ded7a5b-b604-4e86-b9ec-afa11f281828.png)




*VIP Customers
![image](https://user-images.githubusercontent.com/121314771/226076982-e5066e8d-5aca-4322-a185-01ca479bd638.png)

 

Even though all of our queries could answer the questions made by management, it is necessary to process this data and move it into Visual Studio to be able to process it and clean it to make it useful for our purposes.


# Process Phase
- We decided to create two tables for the report named "Sales by Year" in which we created one tabular report using Year as a parent group, followed by the category , and then the total sales by product. In addition, we created a matrix report using the sum of sales values for each year and added an indicator for each year to indicate whether the target sales was met.
![image](https://user-images.githubusercontent.com/121314771/222940445-de152ada-e3af-4016-bfc7-0998dfbd9421.png)
![image](https://user-images.githubusercontent.com/121314771/222940570-0d24df99-a7b2-48ee-b28e-f8045f40e7bb.png)

As we can see the report uses Years as toolkits to help the user get details for each grouping level. 

