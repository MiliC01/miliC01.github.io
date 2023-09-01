---
layout: post
title: "Provincial Energy Generation in Canada from 2008 to 2022 Power BI Dashboard"
author: "Milagros N. Cortez"
categories: projects
tags: [Microsoft Excel, DAX, Power BI]
image: "Screenshot (800).png"
listed:
- Microsoft Excel
- DAX
- Power BI
link: https://app.powerbi.com/groups/me/reports/e53e5a78-61ad-4ebb-8da9-b705824102ca?ctid=5c98fb47-d3b9-4649-9d94-f88cbdd9729c&pbi_source=linkShare
type: "DASHBOARD"
updated: "31/08/2023"
---
## About

I created a dashboard in Power BI to compare the electricity generation of each province and territory in Canada for 15 years spanning from 2008 to 2022. The data for this dashboard can be found in Kaggle uploaded by Jacob Sharples under the name of [Provincial Electricity Generation, Canada](https://www.kaggle.com/datasets/jacobsharples/provincial-energy-production-canada). The data was downloaded into a .csv file and converted into a .xlsx file, the variables in the data set include:

- Date: consiists of the month and year of the entry
- Province: the name of the province or territory
- Producer: includes electric utilities or industries (non-utility companies)
- Generation Type: ways in which the electricity is produced including hydraulic turbine, nuclear steam turbine, combustible fuel, tidal power turbine, wind power turbine, solar, annd other.
- Megawatt_hours: amount of megawatt hours produced

Before creating the dashboard in Power BI the data was transformed and processed DAX and Excel to ensure data completeness and validity. Additionally, in the Excel file four pivot tables were created:

- Producer_Year: Shows the average megawatt hours of each produder in each year
- Province_Generation_Type: shows the sum of megawatt hours broken down by generation type from each province and terrritory for each year
- Year_Generation_Type_Breakdown: shows the average megawatt hours for each generation type in each month for each year
- MegawatH_Year_Province: shows teh sum of megawatt hours for each province from 2008 to 2022

A table of the data used to create the pivot tables is under canada_energy. The Excel file and a pdf of the dashboard can be found [here](https://github.com/MiliC01/Provincial-Electricity-Generation-PowerBI-Excel).
