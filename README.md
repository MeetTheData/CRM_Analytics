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

## METHODOLOGY
1. Marketing Analysis.ipynb -
A) Data Cleaning:
Renamning Columns

String Manipulations

Missing values (Imputing with Median)

DataType Conversion

B) Exploratory Data Analysis (EDA):
Outlier Analysis (Replacing with median)

Feature Engineering

Anomaly Detection and Trend Analysis

Correlation Analysis
