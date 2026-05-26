# Business-Case-Target-SQL
SQL-based analysis of a sales dataset using queries for business insights.

## **Introduction to Business Case:**
Target is a well-known brand and a major American store. This specific business case offers useful data regarding 100,000 orders placed between 2016 and 2018 and focuses on Target's operations in Brazil. The dataset provides a comprehensive view of various dimensions including the order status, price, payment and freight performance, customer location, product attributes, and customer reviews.

## The data is available in 8 CSV files:

customers.csv
sellers.csv
order_items.csv
geolocation.csv
payments.csv
reviews.csv
orders.csv
products.csv

By analyzing these datasets, valuable insights into Target's operations in Brazil can be gained. The datasets can provide insights into the following aspects,
- order processing
- pricing policies
- the effectiveness of payments 
- shipping
- client demographics
- product attributes
- customer satisfaction levels

## Tools and Databases used:
Google BigQuery

## Insights and Business Recommendations
- Total of 609 orders were unavailable and 625 orders were canceled during the given time period, which makes it to be around 1.2 % of total orders. We can reduce this number by studying the reasons behind order cancellation and item unavailability.
- From the analysis, We can see how the orders trajectory is showing a very abrupt increase in orders volume within a very short time. Looking at the overall trend, it is seen that business is picking up very fast in Brazil so the company has to be ready with an extra workforce. To avoid high risk, it can consider hiring contractual employees
- As Brazilian customers usually tend to buy in the afternoon and night, we can increase staff during this time frame in order to manage the customers’ requests, and services better during this time by reducing the workforce in the morning and dawn.
- We can see from Analysis that only 3 states contribute to maximum volume, and the rest of the states need to be focused on improving the business.
- Avg delivery time is quite high for most of those states from where the company is receiving quite less volume of orders, detailed study is needed further for checking the other reasons behind such a low volume of orders from the majority of states. Huge delivery time can be one of the reasons and need to work on it.
