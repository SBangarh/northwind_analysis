# Northwind analysis

## Purpose
To showcase my ability to write a variety of SQL statements and draw insights from a relational database

## Process
*Note*: There are a ton of research questions I could have pursued and still can; however, I have to balance showing enough queries to communicate my knowledge and redundancy.

As executives are usually concerned about revenue and profits, I thought I would explore Products, Categories, Revenue, and Profit margin. My example case can be found below:
- Problem statement: The executives want to better understand product breakdown by category and furthermore by revenue and profit margin. They also want to see the number of customers and revenue per country as well as the top selling product

I started by querying appropriate databases to visualize the data. There were nulls, but they were not relevant to my problem statement, so I elected not to handle them. Next, I checked for duplicates and nulls in those tables to ensure my data was ready for analysis. 

I went about exploring the tables individually and together. I used categories with the most products as my starting point. From there I explored products and categories with the highest revenue and then broke revenue by category down to a year-year basis. Next, I explored 


## Results
- The Beverage product category had the highest revenue every year; however it had the lowest profit margin of all product categories every year. This suggests the beverages are loss leaders.

- Every product category had a negative profit margin, but they improved year over year and were approaching profitablility. This sugessts the company is still young and growing its sales.

- The USA had the most customers and highest revenue while Germany, Austria, Brazil, and France rounded off the top 5. I found it interesting that Austria had two customers, but was ranked third in sales. 

- For the top five countries by revenue, only Austria had its most ordered product in a Beverage category. Interesting, considering Beverages accounted for the most revenue, yet it was only the top category in four countries: Austria, Norway, Poland, and Venezuela
