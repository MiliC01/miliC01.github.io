---
layout: post
title: "SQL & Python Business Data Cleaning & EDA"
author: "Milagros N. Cortez"
categories: projects
tags: [SQL, Python, Data Cleaning, Data Visualization, Pandas, Seaborn, MatPlotLib]
image: "Screenshot (796).jpg"
listed:
- SQL
- Python
- Data Cleaning
- Data Visualization
- Pandas
- Seaborn
- MatPlotLib
link: https://github.com/MiliC01/SQL-Business-Analysis
type: "LINK"
updated: "30/08/2023"
---

## About

In this project, we clean and do an exploratory data analysis (EDA) on sales data for a business. The data was uploaded in Kaggle by Igor Panteleev under the name of [Business Analysis (junior)](https://www.kaggle.com/datasets/sticktogethertm/business-analysis-junior) and can be downloaded in a .xlsx format. The data is divided into two data sheets under the names 2019 and 2020. Both data sets have the variables:
- Order Number
- Client ID
- Product Code
- Date of Delivery
- Delivery Amount

## Process

We start by cleaning and doing our EDA in SQL. Given that the data has null values we use the TOP, DELETE, ORDER BY, AND, IS NULL functions to clean the data. Following this, we start our data analysis asking the following questions:
1) Are there new clients in 2020?
2) How much did the seller earn on new products in 2020?
3) What is the average, minimum, and maximum delivery amount in 2019 and 2020?
4) What are the total delivery amounts for each client in 2019 and 2020?
5) How many products were ordered by each client in 2019 and 2020, and how many clients ordered more products in 2019 and 2020?
6) Find the product with the biggest increase in 2020 compared to 2019
7) Calculate the amount of deliveries for each month and each year.
8) Calculate how many deliveries the seller made each month and for what amount.

We then continue with our EDA using the functions *, TOP, DISTINCT, COUNT, AS, MAX, MIN, AVG, SUM, WHERE, >, <, AND, ON, GROUP BY, ORDER BY, INNER JOIN, DESC, UNION ALL, and temporary tables to retrieve and transform data to answer questions 1 to 6. For questions 7 and 8 we export the cleaned data back into an Excel file and import it to a Julyter markdown file in order to create tables and graphs to visualize our findings.
