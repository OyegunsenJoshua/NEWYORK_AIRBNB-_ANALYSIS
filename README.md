# NEWYORK_AIRBNB_ANALYSIS
I created an Insightful Communication on this data set using Microsoft Excel with detailed tables like Power BI. This data set surfaces through statistical series, data cleaning and Vizualizations.

Table of Contents
1. # [Project Overview]
2. # [Key Areas of Analysis]
3. # [Dashboard]
4. # [Tools]
5. # [Exploratory data analysis]

# Project Overview
- Geographical Focus: New York City (Manhattan, Brooklyn, Queens, Bronx, Staten Island)
- Data Sources: Airbnb public dataset (Inside Airbnb, Kaggle.com (Research))
- 
# Key Areas of Analysis:
- Listing distribution by borough and neighborhood.
- Price trends based on location, property type, and seasonality.
- Occupancy rates and availability trends.

# Dashboard


# Tools
The following tools helped in carrying out this survey successfully.

- Microsoft Excel - Data Cleaning, Microsoft Excel - Exploratory Data Analysis, - PowerBI Desktop - Creating Reports of the data Sets.

# Data Cleaning/Preparation
In the data Preparation Phase, the following tasks were perfromed:

- Removing Duplicates:There was no duplicates in the data set.

-  I noticed in the Data Set there was missing values in the "last review date", I used statistical method analysis to analyse the missing vales using the IF(ISBLANK(M2), "30/07/2019", M2). Where "M2" is the default date in the review "column".
  
-  I  Extracted the date month and year function in a readable pattern, E.G Month(A2), Year(A2), Day(A2).

-  I noticed blank cells in The "Host name" cell. I cross referenced the "Host ID" to the "Host name" since the Originator of the file path cannot be contacted.

-  Further More, I double checked the data set and found zero values in the column. Since the data set is referenced to availability of lounges and apartments so there cannot be a free service(zero value), So i decided to calculate the zero values using an average statistical method.

-  To Calculate the average price:
  
-  I used the average function to calculate the mean of the dataset. For example, =AVERAGEIF(J:J, ">0") will give you average prices greater than zero.

-  Then i replaced the zero values with the average, with a new column using this formula. =If(J2 = 0, $Average_price, J2)

-  I used this method to maintain consistency in this dataset so as to not loose it's integrity and ensure all prices are realistic.

   
# Exploratory Data Analysis
The Exploratory Data Analysis answer Key Questions As:
