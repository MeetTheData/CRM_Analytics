# Customer Relationship Management (CRM) Analysis for Marketing data

## PROBLEM STATEMENT
I’m a data analyst, and the Chief Marketing Officer has told me that previous marketing campaigns have not been as effective as they were expected to be. I need to analyze the data set to understand this problem and propose data-driven solutions.

## BRIEF
Performed Data Exploration and Segmentation to study the key characteristic features of Potential customers using Python.
Executed Hypothesis Testing, Statistical Analysis, Anomaly Detection and Trend Analysis, and Feature Engineering to identify sequential demand patterns and Customer Behavior.
Calculated the top 10 Informative features using Random Forest Feature Importance.
Detected Successful Marketing Channels and Underperforming Marketing Campaigns.
Designed Interactive dashboards using Flourish to analyze the trends, give recommendations and publish the findings.

## DATA DESCRIPTION
The dataset for this project is provided by Dr. Omar Romero-Hernandez. It is licensed as CC0: Public Domain.

The dataset is collected from kaggle - https://www.kaggle.com/datasets/jackdaoud/marketing-data?taskId=2986

ID: Customer’s unique identifier
Year_Birth: Customer’s birth year
Education: Customer’s education level
Marital_Status: Customer’s marital status
Income: Customer’s yearly household income
Kidhome: Number of children in customer’s household
Tennhome: Number of teenagers in customer’s household
Dt_Customer: Date of customer’s enrollment with the company
Recency: Number of days since customer’s last purchase
MntWines: Amount spent on wine in the last 2 years
MntFruits: Amount spent on fruits in the last 2 years
MntMeatProducts: Amount spent on meat in the last 2 years
MntFishProducts: Amount spent on fish in the last 2 years
MntSweetProducts: Amount spent on sweets in the last 2 years
MntGoldProds: Amount spent on gold in the last 2 years
NumDealsPurchase: Number of purchases made with a discount
NumWebPurchase: Number of purchases made through the company’s website
NumCatalogPurchase: Number of purchases made using a catalog
NumStorePurchase: Number of purchases made directly in stores
NumWebVisitsMonth: Number of visits to company’s website in the last month
AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
AcceptedCmp2: 2 if customer accepted the offer in the 1st campaign, 0 otherwise
Response: 1 if customer accepted the offer in the last campaign, 0 otherwise
Complain: 1 if a customer complained in the last 2 years, 0 otherwise
Country: Customer’s location

## CONCLUSION

### Summaries:

- The last campaign had twice the amount of engagement than the previous campaigns.
  - The last campaign attracted more customers who had lower income and more dependents compared to the customers who were attracted by most of the previous campaigns.
  - The last campaign had fewer customers purchase from all the purchasing channels than most of the previous campaigns.
  - The products on which customers spend the most are Wine and Meat, but last campaign customers spent 10% less on meat and 50% less on wine compared to the previous campaigns.
  - The last campaign customers purchased more fruits and sweets compared to half of the previous campaigns.
  - Compared to customers who made no purchases in previous campaigns, those who purchased in the last campaign bought more products across all categories and had 5% higher income.
  - Overall, the last campaign effectively targeted low-income customers with more dependents and saw the highest (60%) acceptance in Mexico. However, it performed worse with high-spending products like Wine and Meat compared to previous campaigns.

- Most customers purchase through physical stores, where people tend to spend more amount per purchase. The reason might be the customers had more impulsive purchases when they saw other similar products in stores.

- People with kids:
  - tend to purchase less
  - tend to have a high number of purchases made with a discount

- Advertising campaign acceptance is positively correlated with income and negatively correlated with having kids/teens



### Recommendations for Customer Acquisition and Increasing Revenue:

#### On Acquisition:
`Expand Campaigns with Localized Strategies` <br />
  - Continue the same campaign model for low-income population and leverage the success in Mexico by implementing localized marketing strategies in other regions with similar demographics. <br />
`Targeted Promotions for Families` <br />
  - Since families with children tend to purchase less and focus on discounted products, consider offering exclusive discounts on family-oriented products or bulk-buying options that offer value. <br />

#### On Increasing revenue:
`Focus on Wine and Meat` <br />
  - Introduce targeted promotions or loyalty rewards to previous high-spending customers. <br />
`Cross-sell and Bundle` <br />
  - Bundle wine and meat with other products like fruits and sweets to drive sales across categories especially in low-income demographics. <br />  
`Optimize Customer Segmentation for Higher Spending` <br />
  - Use data-driven segmentation to create personalized offers for high-income and high-spending customers, encouraging them to increase their spending in premium categories like wine and meat. <br />
`Change marketing strategy for worse performing countries` <br />
  - For countries like India where the latest campaign performed poorly, implement previous strategies and optimize them in accordance with their demographics. <br />
`Exclusive In-Store Discounts` <br />
  - Offer exclusive in-store discounts or promotions to drive foot traffic and capitalize on impulsive purchasing behavior resulting in higher Average Order Volume (AOV). <br />


