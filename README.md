# PIZZA SALES ANALYSIS
## TABLE OF CONTENT
- [PROJECT OVERVIEW](#project-overview)
- [DATA SOURCE](#data-source)
- [TOOLS](#tools)
- [DATA CLEANING AND PREPARATION](#data-cleaning-and-preparation)
- [EXPLORATORY DATA ANALYSIS](#exploratory-data-analysis)
- [RESULT AND FINDING](#result-and-finding)
- [LIMITATIONS](#limitations)
### PROJECT OVERVIEW
This data analysis project provides insights into the sales performance of a pizza company from January to December 2015. By analyzing various aspects of the sales data, i seek to identify ttends, make data-driven recommendations, and give a deeper understanding of the company's performance.
### DATA SOURCE
The primary dataset used for this analysis are "Pizza_Type.csv", "Pizza.csv", "Order Details.csv", "Order.csv" files, containing detailed information about each sales made by the company.
### TOOLS
- Excel- Data cleaning, Data preparation, Data Analysis
- Power BI- ETL, Data Modeling, Report and Analysis
### DATA CLEANING AND PREPARATION
In the initial data preparation phase, i performed the following tasks;
1. Data loading and inspection.
2. VLOOKUP for extracting colums from other csv files into a sheet which serves as the main data for the analysis.
3. Creation of new colums i.e Month, Hour, Days of week, Quarter,Revenue.
4. Handling empty cells.
5. Data cleaning and formatting.
 ### EXPLORATORY DATA ANALYSIS
1. What is the Total Revenue? 
I used price and quantity to get the revenue column and i sum up all the value in the columns.
2. How many order were placed?
Count of order details Id
3. What is the average order value?
Total Revenue divided by Total Order
4. How many total pizza were sold?
Sum of all value in the quantity column.
5. What is the average number of pizza per order?
6. How much quantity was sold per pizza category?
Using a pivot table, i placed category in the row field and sum of quantity in the value fielf.
7. What is the most expensive pizza?
Using a pivot table, i placed pizza id in the row field and max of price in the value field and i find top 1.
8. When are the peak ordering hours?
Using pivot table, i placed Hours in the row field and count of order Id in the value field.
9. What is the average number of pizza ordered per day?
Using pivot table, Order date in the row field and count of order id in the value field then i calculated the average using the count of order Id column.
10. How do order vary by day of the week, month and quarter?
I calculated separately for weekday, month and quarter using pivot table, i placed month, weekday and quarter in the row field and count of order id in the value field and visualize it on a line and bar chart.
11. Which is the top 5 best selling pizzas by number of order and top 5 pizza by quantity?
Using a bar chart, i placed pizza id in the axis x field and sum of quantity in axis y field and i calculated top 5
12. What are the top 3 pizzas per category based on sales and top 3 pizza type by sales?
I used a bar chart and i placed category in axis X , sum of revenue in Y axis and i calculated top 3
13. What percentage of sales comes from category and size?
Using pivot table, i placed category and size in the row field and sum of revenue in the value field and i change the calculation to % Grand total.
14. What is the common pizza size ordered?
Using a pivot table, i placed size in the row field and count of order in the value field and i find the top 1
15. What percentage of sales comes from pizza type?
Using a pivot table, i placed pizza type in the row field and revenue in the value field and i used a bar chart to represent this. 

### RESULT AND FINDING
- Classic Category contributes to Maximum Total Orders.
- The Big Meat Small size contributes to the highest order.
- Orders are high during midday and evening period.
- Highest order comes from the second quarter of the year.
- The month with the highest order is July.
- Orders are very high during weekends.
- Large pizza size has 45.89%  shares of total revenue.
- Classic category has 27% shares of total revenue.
### LIMITATIONS
-I removed the ingredient column and rows with empty value because they would have affected the accuracy of my conclusion from the analysis.




