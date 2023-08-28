---
layout: post
title: "Palmer Archipelago Penguins Data Cleaning and Analysis"
author: "Milagros N. Cortez"
categories: projects
tags: [Python, Data Visualization, Data Cleaning, Data Analysis, GLM, GAM]
image: "Screenshot (750).png"
listed:
- Python
- Data Visualization
- Data Cleaning
- Data Analysis
- GLM
- GAM
link: "Palmer_penguins_report.pdf"
type: "PDF"
updated: "12/08/2023"
---
## About

In this report, we clean and analyze data from penguins in the Palmer Archipelago using Python. We also use a Generalized Linear Model and Generalized Additive Model to predict a penguin's sex based on culmen length, culmen depth, flipper length, body mass, and species, and we compare both models. 

## Process
Problems:
- Data which we desired to analyze was in two separate .csv files
- Data is not clean

Solutions: 
- Variables we desired to analyze from the two separate data sets were merged into one data set  
- Rows with NaN values were removed from the data set as well as rows with unknown values that were not listed as possible values or classifications for a variable.
- Variables that involved dates were formatted and labeled as dates

After cleaning the data we explore the following questions:
- What can we initially see from this data set?
- Are there differences in the three types of penguins in the data set? Consider island, clutch completion, sex ratios, and date of eggs.
- What is the relationship between culmen length and depth?
- Is there a difference between culmen length and culmen depth between male and female penguins? Are there differences as well with body mass and flipper length?
- Can we use a Generalized Linear Model (GLM) or a Generalized Additive Model (GAM) to predict penguin sex using the quantitative variables as well as species in our data set? Which of these methods is more effective?
