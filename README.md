# Instacart-Grocery-Basket-Analysis-Master
**Instacart Grocery Basket Analysis**

Instacart is an online grocery store that operates through an app. They want to uncover more information about their sales patterns. 
My rule as a data analyst is to perform an initial data exploratory analysis of some of their data in order to derive insights and suggest strategies for better segmentation based on the provided criteria. 
The Instacart stakeholders are most interested in the variety of customers and their purchasing behaviors in their database. 
My analysis will include creating a targeted marketing strategy by helping the stockholder with following questions. 

**Key Questions**


1.	What the busiest days of the week and hours of the day are?
2.	Are there particular times of the day when people spend the most money?
3.	Which departments have the highest frequency of product orders?
4.	What are the different types of customers in the system and how their ordering behaviors differ?
5.	What's the distribution among users in regards to their brand loyalty?
6.	Are there differences in ordering habits based on a customer's loyalty status?
7.	Is there difference in ordering habits based on a customer's region?
8.	Is there a connection between age and family status in terms of ordering habits?
9.	What different classifications does the demographic information suggest? 
10.	What difference can you find in ordering habits of different customer profiles?

Over all, the process was very smooth. I worked on orders.csv, products.csv, customers.csv, department.csv, order_product_prior,csv and few more data. 
I started by importing the data into Jupyter to do descriptive analysis, followed by subsetting, consistency checks, combining and exporting, deriving new variables, grouping data and aggregating variables, data visualization, and lastly coding etiquette and exporting it into excel. 
In between each step, I export the data in separate excel sheets. 
The skills/tool/procedures that were used in Jupyter were the following: Data wrangling, Data merging, deriving variables, grouping data, aggregating data, Reporting in Excel and population flows. 
Writing commands in python was very easy and clean. 
I used many libraries such as Pandas, NumPy, OS, Mathplotlib.pyplot, seaborn and SciPy. 
The only challenge that I face was while creating new variables, but I was able to solve the problem by loc and aggregation. 
All these procedures helped me answer the questions of stockholder. The answers to the main questions that the stockholder have are the following:

**Solution**
1.	The busiest days of the week are the first day of the week and last day of the week. And from 4 to 5 am is the busiest hour of the day.
2.	Looking at the graph, people spend most money at the morning before 10 am.  
3.	Looking at the graph, the department ID 10.25 has the highest ordering behaviour. 
4.	There are three types of customers, Regular customer, loyal customers and new customers. Their ordering behaviors differ based on the number of the products they order. 
5.	The Regular customer has the highest number of orders, then loyal customer and then new customers. 
6.	Yes, based on customer’s loyalty status, the number of regular customers, loyal customer and New customer are highest respectively. The number of New customers ordering the product is almost half of the number of the regular customer. And the number of loyal customers ordering the product is at the middle of both. 
7.	Yes, the value count in all four regions differ. The region Three, Four, Two and One are highest respectively. The number of orders in region one is almost half of the region three. 
8.	Yes, single adults have the highest number of orders in compare to young parents and seniors, with second lowest and lowest number of orders respectively.  
9.	The family status plays rule on the ordering habits of customers as mentioned above. The Age plays rule on the ordering habits of customers as mentioned above. The Region plays rule on the ordering habits of customers as mentioned above. The income and certain types of goods does not seem to have impact of ordering habits of customers. 
10.	I can see an increase in their mean of ordering behavior from seniors, single adult and young parents, with lowest, second highest and highest number of orders respectively. 


**My recommendation** 
Intacart should focus on the regular customer, region three, single adults, department ID 10.25, first day and last day of the week, morning orders. 
Things that I would do differently to improve is to do sub-setting and make the data lighter. 


