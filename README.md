# **Time-Series-Regression-Analysis-Corporation-Favorita**

## Business Understanding
Corporation Favorita is currently facing challenges in accurately forecasting sales, resulting in stockouts, overstocking, and lost revenue opportunities. The company aims to leverage its dataset and advanced data manipulation techniques to enhance sales predictions and make data-driven decisions.

## Project Objective
In response to these challenges, this project aims to develop a machine learning model that accurately predicts sales based on time series analysis across various products and stores. The goal is to enable the company to optimize inventory management and ensure the right quantity of products is in stock to meet customer demand.

## Methodoloy
This project adheres to the CRISP-DM (Cross-Industry Standard Process for Data Mining) Framework, a widely recognized approach for data science initiatives.
We aim to develop and evaluate multiple models to accurately forecast sales in a time series context. Leveraging historical data, we will implement and compare the performance of five distinct models:
- ARIMA (AutoRegressive Integrated Moving Average)
- SARIMA (Seasonal AutoRegressive Integrated Moving Average)
- Linear Regression
- XGBoost.
- GradientBoost Regressor

By exploring and contrasting the strengths and limitations of each model, we seek to identify the most performing model for prediction.

## Data Understanding
Three dataframes were extracted from Microsoft SQL Server, and four datasets were sourced from other locations including a GitHub repository and Google Drive for this project. Below is a summary of the features present in these datasets, providing an overview of the data used.

1. `additional_holidays`: Indicator of additional holidays added to the regular calendar holidays.
2. `onpromotion`: Indicator of whether the item was on promotion at the store on a specific date.
3. `store_nbr`: Identifier for the store where the products are sold.
4. `city`: City where the store is located.
5. `family`: Category of the product sold.
6. `type`: Type of holiday or event.
7. `sales`: Total sales for a product category at a particular store on a specific date.
8. `transferred`: Indicator of whether a holiday was moved to another date by the government.
9. `transaction`: Number of transactions made at a particular store on a specific date.
10. `state`: State where the store is located.
11. `cluster`: Grouping of similar stores.
12. `date`: Date of the sales record.
13. `oil_price`: Daily oil price.
14. `type`: Type of store.

## Project Links
- **Published Article**:
- **PowerBI Dashboard**:

### Author Information
- **Name**: Emmanuel Dadson
- **Email Address**: [Emmanuel Dadson](emmanueldadson36@gmail.com)
- **LinkedIn**: [Emmanuel Dadson](https://www.linkedin.com/in/emmanuel-dadson)


