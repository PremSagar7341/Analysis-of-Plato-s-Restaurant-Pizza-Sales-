Introduction: Platos resturant is one for the pizza selling restaurant and it is loacted in new jersey. The dataset contains pizza sales data for the year 2015 and dataset contains  approximately 48,000 rows

Problem statement: Platos resturant owner hired a Data Analyst to analyze the pizza sales data to help the company to get more sales. And he also wanted to know on which days the sales are more, on which month the sales are more and top 5 best performing and worst performing pizzas based on this the Owner can take further actions. (like to increase the prduction of best selling pizzas and to give some discounts  or to stop that particular pizza category which is not selling much.)

Project Explanation:

	1) first I have imported data into MYSQL workbench and created a Data Base
	2) based on the problem statement I had wrote SQL queires to find the total revenue, total orders placed, total no.of pizzas sold, avg pizzas sold per order, avg order value, daily trend for toal orders, monthly trend for total orders, top 5 best performing pizzas based on revenue, total orders, and total pizzas sold and bottom 5 worest performing pizzas based on revenue, total orders, and total pizzas sold etc 
	3) and also captured those results into Word Doc. And this Doc is helpful in comparing with the Power BI results . It will be supporting doc whatever we are showing in power BI those values will be matching with the results of sql queries.
	4) Next comes the Power BI part
	5) I have imported data into Power Bi by connecting to Mysql server Database, here data source is MySQLserver DB
	6) I have used some Data cleaning process such as replacing values, creating some custome columns, extrating dayname, month name from date columns etc, for data cleaning I have used Power query editor.
	7)  I have used DAX funcions to create some custom columns and Measures w.r.t our problem statement
	8)  I have created Dyanamic DB by using different different charts and formated those charts

Conclusion
BY using this DB a business owner or a resturant owner can take an decision that which are under performing and which are best performing Pizzas and the Owner can take further actions like to increase the prduction of best selling pizzas and to give some discounts  or to stop that particular pizza category which is not seeling much
![image](https://github.com/PremSagar7341/Analysis-of-Plato-s-Restaurant-Pizza-Sales-/assets/136251588/37a0943d-c693-400a-82d3-e6888210d420)
