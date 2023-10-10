# Big_Mart_sales

### Sales Prediction for Big Mart Outlets
The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and predict the sales of each product at a particular outlet.

Using this model, BigMart will try to understand the properties of products and outlets which play a key role in increasing sales.

Please note that the data may have missing values as some stores might not report all the data due to technical glitches. Hence, it will be required to treat them accordingly. 

**Data Collection: Analytics vidya:** https://datahack.analyticsvidhya.com/contest/wns-analytics-hackathon-2018-1/

### Problem Statement: 
Your client is a large MNC and they have 9 broad verticals across the organisation. One of the problem your client is facing is around identifying the right people for promotion (only for manager position and below) and prepare them in time. Currently the process, they are following is:

- They first identify a set of employees based on recommendations/ past performance
- Selected employees go through the separate training and evaluation program for each vertical. These programs are based on the required skill of each vertical
- At the end of the program, based on various factors such as training performance, KPI completion (only employees with KPIs completed greater than 60% are considered) etc., employee gets promotion.
  
For above mentioned process, the final promotions are only announced after the evaluation and this leads to delay in transition to their new roles. Hence, company needs your help in identifying the eligible candidates at a particular checkpoint so that they can expedite the entire promotion cycle. 

They have provided multiple attributes around Employee's past and current performance along with demographics. Now, The task is to predict whether a potential promotee at checkpoint in the test set will be promoted or not after the evaluation process.

 

### Data Dictionary
We have train (8523) and test (5681) data set, train data set has both input and output variable(s). You need to predict the sales for test data set.

Train file: CSV containing the item outlet information with sales value


| Variable	| Description |
|--|--|
| Item_Identifier	| Unique product ID |
| Item_Weight	| Weight of product |
| Item_Fat_Content	| Whether the product is low fat or not |
| Item_Visibility	| The % of total display area of all products in a store allocated to the particular product |
| Item_Type	|The category to which the product belongs |
| Item_MRP | Maximum Retail Price (list price) of the product |
| Outlet_Identifier	| Unique store ID |
| Outlet_Establishment_Year	| The year in which store was established |
| Outlet_Size	| The size of the store in terms of ground area covered |
| Outlet_Location_Type | The type of city in which the store is located |
| Outlet_Type	| Whether the outlet is just a grocery store or some sort of supermarket |
| Item_Outlet_Sales	| Sales of the product in the particular store. This is the outcome variable to be predicted. |



 
### Evaluation Metric:
The evaluation metric for this competition is F1 Score.

### Public and Private Split:
Test data is further randomly divided into Public (40%) and Private (60%) data.

- Your initial responses will be checked and scored on the Public data.
- The final rankings would be based on your private score which will be published once the competition is over.
