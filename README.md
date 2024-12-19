# Superstore Products Data Analysis Final Capstone NAYA Project

## Project Overview
This project aims to provide a comprehensive overview of products of Superstore retail business located in the United States which is specialized on selling Office Supplies and Technology products, furniture etc. focusing on products sales, and profitability, with a specific emphasis on high- and low-profit products, impact of discount strategies and uncovering opportunities for product bundling.

## Initial Research Question of the project
How can the company optimize its product portfolio by identifying high- and low-profit products, determining the impact of discount strategies on sales and margins, and uncovering potential opportunities for product bundling?

## Data description
- The data source [Superstore Sales DataSet](https://www.kaggle.com/datasets/aashwinkumar/superstore-sales-dataset) be downloaded from  www.kaggle.com. 
- The dataset contains the orders for 4 years (2011-2014) and consists of 51290 records with 21 features that can be divided in following kinds:
  - Sales data - order date, order ID, quantity, and sales
  - Product information - product ID, quantity, category and subcategory
  - Geographical segmentation - country, state, and city
  - Profit - profits generated from sales transactions
  - Consumer segmentation - customer ID, segment, and region
- Data preprocessing steps contained:
  - formatting data types
  - dropping rows with missing values of sales
  - treatment outliers using IQR (Interquartile Range)
  - adding derived columns
- The final dataset shape: 44152 rows, 22 columns, no missing values

## Documentation and Presentation
- [Python notebook](): full flow of the project.
- [Report](): a detailed report covering descriptive analysis, impact of discount strategies, product bundling ppportunities, A/B testing, tableau dashboard and conclusions.
 

