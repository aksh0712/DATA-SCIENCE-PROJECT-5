DATA-SCIENCE_PROJECT-5

Marketing Insights for E-Commerce Company.

BUSINESS OBJECTIVE: One of the Leading E-Commerce Company would like to get marketing insights from the data to define marketing strategies going forward. Also, expecting to build an analytical dashboard to monitor various KPI’s & business metrics. Role: Advanced Data Preparation - Built an enriched customer profile by deriving KPI’s such as monthly average purchase, cash advance, average transaction per purchase etc. Applied data reduction technique using factor analysis for identifying important variables.

Solution Data Pipelines

1.	Import essential packages and import Customer’s data, import discount coupons in discount coupons feature headings contains white spaces so first get rid off that space. Then create discount percentage column which includes discount percentage amount. Now import Marketing spend and online sales. In online sales change transaction date format, also include month column in online sales. Now import tax data and merge all data files into one file.
2.	Find following Key Process Indicators 
a.	Average Order Value = Total Revenue / Transaction per Customer 
b.	Profit Margin – is the commonly used profitability ratio. It represents how much percentage of total sales has earned as the gain.
c.	Purchase Frequency – is the sum of total number of transactions / total number customers.
d.	Repeat Rate – [ number of customers who have purchased before / Total number of customers] x 100
e.	Churn Rate – is the annual percentage at which customers stop subscribing.
f.	Customer Lifetime Value – is the prediction of the net profit / revenue attributed to the entire future relationship with a customer.
3.	Now let us complete some business objectives. 
a.	Calculate Invoice Amount for each transaction at item level.
b.	Find how many customers are acquired every month.
c.	How customers are retained month on month basis.
d.	Find Revenue generated from existing / new customers on month on month basis
e.	Find the role of discount in generating revenue.
f.	Find revenue by category, by month, by week, by day. Find number of orders by category, by month, by week, by day. Find Average order value by category, by month, by week, by day. Find Number of customers by category, by month, by week, by day. Find Quantity purchased by category, by month, by week, by day.
g.	Find the Trend / Seasonality of sales by category, location, month.
h.	Find out how number of order and sales varies on different days.
i.	Calculate the Revenue, Marketing spends, percentage of marketing spend out of revenue, Tax, percentage of delivery charges by month.
j.	Find out the presence of product in the transaction.
k.	Find out Which product was purchased mostly based on the quantity
4.	Perform customer segmentation – Divide the customers into premium, gold, silver, standard and define the strategy on the same (i.e., heuristic, value based, RFM).
Dividing the customers into segments was a prerequisite hence, segmentation has been incurred on the dataset. It enables us to target a specific segment likely to be interested.
5.	To define the strategy to each segment we used scientific approach of clustering (K-Means) and along with that we understood the profiles.
6.	To determine which of the products are sold together (mostly) for that we performed
a.	Market Basket Analysis – For Market Basket Analysis we need to find mostly used products, least used products, mostly clicked products and top products in overall.
b.	Apply association rules and apriori algorithm to extract the cross-selling products.
c.	Performed analysis of cross selling products that are likely to be purchased together that results in more effective pricing strategies.
