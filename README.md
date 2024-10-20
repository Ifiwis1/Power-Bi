# Interactive Dashboards
## Furniture Sales Performance 

A furniture sales company aimed to assess the sales performance of their products by category and brand. I performed an analysis to create a dashboard that provides an overview of this performance. 

The dashboard was created using Power BI, with data sourced from an Excel workbook – Furniture_Sales. The workbook contained the following data: Sale id, Item code, Item description, Item category, Item brand, Item cost, Item color, Sale price and Sale profit margin. 

 

Results of the Analysis 
Some of the important findings are stated below: 

Average profit margin for all the products is 32.1% 

There are 4 categories and 3 brands 

Wardrobe has the highest average sale price for the different brands 

Table has the highest average sale profit margin for the different brands 

 
## Executive Summary of a financial report 

Stakeholders requested for a report on the latest sales figures for the sample company. The dashboard was created using Power BI, with data sourced from an Excel workbook – Sample Data. The workbook contained data like the product, units sold, sale price, profit, e.t.c 

Results of the Analysis 
The information they requested for are stated below: 

• Which month and year had the most profit? December 2014 

• Where is the company seeing the most success (by country)? France with profit of 3.3M 

• Which product and segment should the company continue to invest in? Paseo product and the Government segment 

 

## Energy Generation 

 

An organisation involved in the renewable energy sector requested for a one-page dashboard that shows the current energy mix across the EU and UK, and also provides insights into the historical trends. 

The dataset used is a summary of European energy production and consumption from the years 2000-2020 which was provided as an excel workbook - Energy_generation - Dashboard 1. Each row corresponds to a unique combination of country and year. The dataset includes all EU countries, plus the UK. The columns break down the amount of energy produced in that country and year in TWh, in the different energy categories.  

DAX expressions were used to create columns and measures for better analysis.  

Columns created are: 

Total Fossil = Energy[Hard Coal] + Energy[Lignite] + Energy[Gas] + Energy[Other fossil] 

Total Renewable = Energy[Bioenergy] + Energy[Hydro] + Energy[Wind] + Energy[Solar] +Energy[Other renewables] 

Total Electricity Production = Energy[Total Fossil] + Energy[Total Renewable] + Energy[Nuclear] 

Coal = Energy[Hard Coal] + Energy[Lignite] 

Measures created are: 

% Renewable = SUM(Energy[Total Renewable]) / SUM(Energy[Total Electricity Production]) 

% Fossil = SUM(Energy[Total Fossil]) / SUM(Energy[Total Electricity Production]) 

% Nuclear = SUM(Energy[Nuclear]) / SUM(Energy[Total Electricity Production]) 

 

Results of the Analysis 
The following insights were gained form the analysis: 

Germany produced the highest renewables and fossil in 2020 

France produced the highest nuclear energy in 2020 

Over the years, there has been a decline in fossil and nuclear with an increase in renewables 

As at 2020, the energy mix for EU and UK comprises of 38.61% renewables, 24.04% nuclear and 37.35% fossil. 

 

Adventure Works 

This task involved helping the stakeholders better understand how the average sales amounts and number of sales are changing, and how this compares across the product categories. They noticed that the average sales amount (per sales line) has been decreasing and wants to better understand why. A secondary objective is to understand any differences in the average sales amount for each sales territory. 

The dataset used is  of sales data from an imaginary company provided by Microsoft for Power BI and DAX practice. 

Results of the Analysis 
The following insights were gained form the analysis: 

The category with the highest average sales line value is ﻿Bikes﻿ with an average sales line value of ﻿$2,365.22﻿. 

North America has the highest average sales 

 

Adventure Works Sales Executive Summary 

Stakeholders requested for a report on your latest sales figures. The dataset used is the Excel workbook - AdventureWorks Sales - Dashboard 3. The data model was built by using hierarchies and measures. 

They've requested an executive summary and answers to the following questions. 

Which day had the most sales in February 2019? February 25, with a sales amount of $253,915.47. 

Which country is the company seeing the most success in? In the United States, with an order quantity of 132,748. 

Which product category and reseller business types should the company continue to invest in? The company should continue to invest in the Bikes category and the Value Added Reseller and Warehouse reseller businesses. 
