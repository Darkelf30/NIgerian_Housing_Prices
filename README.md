# Nigerian Housing Analysis

![](Real_estate_pic.jpg)

## Introduction
Shelter is one of man's basic needs. Alongside, food and clothing, comfortable shelter is what many strive for. Nigerians are not left out and where possible, Nigerians also aim to own theor own homes. However, for many, astronomical costs of homes is a limiting factor. Many factors are thought to determine the cost of a house in Nigeria which include (but are not limited to) location, number of bedrooms, number of bathrooms, parking space, and so on.
This analysis gives an overview of the Nigerian housing market using a simple dataset gotten from kaggle.

**_Disclaimer_**: _All datasets and reports do not represent my company, institution, or country. The dataset used for the creation of this report can be found for free on [Kaggle](https://www.kaggle.com/datasets/abdullahiyunus/nigeria-houses-and-prices-dataset)

## Business Objectives
1.  What's the average cost price for a house in Nigeria?
2.  What's the expected number of bedrooms, bathrooms for a house? How many cars can we expect the parking space to hold?
3.  Houw does the average housing price vary by region?
4.  What's the typical cost for a bungalow (of different types) and a duplex (of different types)
5.  What are the top 10 most expensive cities in terms of housing costs?

## Skills demonstrated:
The following Microsoft Excel skills were incorporated
* Macros 
* Dashboard design 
* Pivot Tables and Pivot Charts
* Filters and Filter design
* Data transformation in Excel Power Query
* Data modelling in Power Pivot
* Measures and DAX (Data Analysis Expressions)

## Data Transformation
This was carried out in Excel Power pivot and it involved performing the following steps:
1.  Ensuring that the datatypes are uniform
2.  Ensuring that the cities were properly represented under their respective states

## Data Modelling
This was performed using the Data modelling tab of Excel Power Pivot. A seperate file named [Zones](Zones.jpg) was imported that contains each states and the regions they fall under. This file was connected to the nigerian housing data file using the state field as the key column. A one-to-many relationship was thus formed.

Raw Data              |         
:--------------------:|
![](Raw_Data.png)

Cleaned Data
:-----------------------:
![](Transformed_Data.png)

Zones Data
:-----------------------:
![](Zones.png)

Data Model
:-----------------------:
![](Data_Model.png)

## Data Analysis and Visualization
The analysis steps were carried out in Excel using Pivot Tables and Pivot charts. The dashboard that was designed can be found and interacted with [here](Analysis File.xls). This workbook consists of the following sheets:
1.  The Home Page with some interactive buttons for navigation
2.  The Interactive Dashboard
3.  The Raw Data (named Raw Data)
4.  The Transformed Data (named Insurance Policies - Data)
5.  Other sheets containing the Pivot tables and pivot charts
