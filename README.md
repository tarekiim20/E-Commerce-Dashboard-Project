# E-Commerce-Dashboard-Project
Interactive dashboard for an E-commerce virtual business. 

## Introduction
I have built an interactive dashboard for an e-commerce business where I tried to answer their business needs to improve sales and reduce operating costs. The dashboard is for a virtual company and the data source(data warehouse) is in the repo.

Their Operating costs are composed of 5 different things:
1. COGS (Cost of goods sold): This is the lowest price paid for the product and it is the price of it being manufactured.
2. Freight Costs: These are the price of the product being shipped.
3. Fulfillment cost (Warehousing): These are the costs for storing the product for long periods.
4. Shipping costs: Delivery of the product to the customer.
5. Profit/Loss: The Price of the product sold will be considered as profit.

## Data modeling and preprocessing

![Data Model](https://github.com/user-attachments/assets/fc483f75-77c1-44fd-b35d-22af40d1e9c7)

Here we can see the final model of the data that is created after some process of cleaning the data like:
1. Removing Null Values
2. Replacing incorrect inputs
3. Fixing Data types


## Executives Summary
After modeling and cleaning the data, I have answered some important questions for executives like:
- how the company is performing ?
-  What is the total profit ?
-  what is the total profit margin by category?
-  in which states the company is selling the most?

all that and more can be answered with one interactive dashboard:

![Executive Summary](https://github.com/user-attachments/assets/47877ed0-8719-4169-b27c-e8b2ac770171)

## Market Basket Analysis
When customers buy something from the store they usually combine it with other things. This sheet of the dashboard answers:
- What are the combinations of the products sold at most?
- What is the profit margin for each product?
- What is the total sales for each product?

![Market Basket Analysis](https://github.com/user-attachments/assets/279d69c7-ef57-4fc0-bddf-912d9c4fba3a)

## Shipping Metrics
Shipping is composing a lot of the operational costs. And can perform a major role in taking actions to reduce the unit price cost of a product. But how shipping can be that effective?

Let's take an example:
If we are selling a container of goods that container would cost (for example) $100. But if the container was shipped in parts (10 goods per package) the shipping costs would be $500. or $50/good.  So actually when we sell more products it is better in terms of the unit price of the product. This decrease can be translated into more profits or even more customer satisfaction by adding discounts.

### What-if Analysis for the Shipping Costs
Now, how much each product when shipped together will eventually save for the company? And actually which products when shipped in parts makes more profits compared to other products? and What if we increased the quantity of the product sold? how much we are going to save. 

All these questions can be answered by a what-if analysis dashboard, which I have built to have an interactive slicer to answer the question of what if? 

![Shipping Metrics](https://github.com/user-attachments/assets/69d582a7-75c1-420c-915c-52a1cadd7451)


from the slicer of the quantity we can see what if we increase the quantity of the product from 6 to 7 ? what if it was 8 or even 20.

## Conclusion
In this project I have completed all major portions of the data analytics and visualization pipeline. I went from data cleanup and exploration to identifying insights in the ecommerce dataset. And built interactive dashboard-style pages for executives and provided specific business recommendations. The executives can now easily explore key KPIs and drill down into the details, such as sales, customers, and expenses. This will enable the company to make more informed decisions about future cross-sell promotions, logistics related to shipping items, and further ways to reduce their operating costs. I covered many topics in this project, like

1. Data modeling
2. Exploratory data analysis
3. DAX functions
4. Report design. 


 
