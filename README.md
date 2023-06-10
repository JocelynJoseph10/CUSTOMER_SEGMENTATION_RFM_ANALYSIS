# CUSTOMER_SEGMENTATION_RFM_ANALYSIS
PROBLEM FORMULATION
An online retail store wants to retain some of its customers by providing some coupons and offers and also
to give-away some gift hampers to its existing best customer base. The aim of the project is to find the
customers that are most eligible for the gift hampers and also find the customers whom the company should
retain.


DESCRIPTION ABOUT THE DATASET
Data Description: The dataset includes 51,290 observations under the following 14 variables.
The dataset consists of all the transactions made from April 1, 2018 to February 28, 2021
Category: The category to which the product belongs.
City, state, country: The geographic data from which the order was placed.
Customer_ID: Unique identification number of a customer
Order_date: Date on which the order was placed
Order_priority: The priority of the order placed
Product_ID: Unique identification code of a particular product.
Ship_mode: The type shipping customer preferred
Sub_cat: The sub category to which the product belongs
Discount: The discount percentage availed by the customer on particular product
Profit: The profit that the company gained from this order
Quantity: The number of units that are ordered
Unit_price: The price for one unit of the particular product


DATA CLEANING
● Variable selection: Dropped columns that were not relevant to the analysis like Sno and
Product_ID. Created a new column Sales_Amount from the two available columns of Quantity
and Unit_Price
● Missing Values: Removed 262 observations from the dataset which held either missing
values(251 obs) or 0(9 obs) in the Unit_price column.
● Checked outliers for all numeric columns. Retain all outliers in the dataset.
● All duplicate values for “Customer_ID” column are retained for further analysis.


RFM is recency, frequency and monetary values. RFM analysis is used to segment consumer behavior. The idea
behind this is basically analysis of the last purchase, frequency of purchase and overall expenditure.
methodology :
● Building RFM model.
● Divide the customer list into different groups of three dimensions R,F, M.
● Grouping customers based on buying behavior.
● The parameters are analyzed.
● At Least three parameters are analyzed because analyzing just one parameter may give inaccurate results.
