# NEWYORK_AIRBNB_ANALYSIS
I created an Insightful Communication on this data set using Microsoft Excel with detailed tables like Power BI. This data set surfaces through statistical series, data cleaning and Vizualizations.

Table of Contents
1. # [Project Overview]
2. # [Key Areas of Analysis]
3. # [Dashboard]
4. # [Tools]
5. # [Data Cleaning/Preparation]
6. # [Conclusion]

# Project Overview
- Geographical Focus: New York City (Manhattan, Brooklyn, Queens, Bronx, Staten Island)
- Data Sources: Airbnb public dataset (Inside Airbnb, Kaggle.com (Research))
  
# Key Areas of Analysis:
- Listing distribution by borough and neighborhood.
- Price trends based on location, property type, and seasonality.
- Occupancy rates and availability trends.

# Dashboard

  <img src="https://github.com/![Air Bnb Analysis](https://github.com/user-attachments/assets/4d7f28c0-9ac7-4d0c-b0eb-07d6f5b58168)
" width="400" height="250" alt="Image">

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

# Key Insights

1. Price Trends & Distribution
- Median Price: Airbnb prices vary significantly by borough. For example, Manhattan and Brooklyn tend to have higher average prices compared to Queens, Bronx, and Staten Island.
- Luxury Listings: Higher-priced listings are often concentrated in downtown Manhattan (SoHo, Tribeca, Midtown) and luxury waterfront areas in Brooklyn.
Budget-Friendly Areas: Queens and the Bronx offer more affordable Airbnb options.

2. Neighborhood Popularity:
- Most Listings: Manhattan and Brooklyn have the highest density of Airbnb listings.
- High Demand Areas: Neighborhoods like Williamsburg, Greenwich Village, and the Lower East Side show high occupancy rates due to tourism and nightlife.
- Up-and-Coming Areas: Neighborhoods like Bushwick and Astoria are gaining traction due to lower prices and a growing number of trendy attractions.
  
3. Availability & Booking Trends:
- Highly Available Listings: Some properties are listed but rarely booked, affecting their ranking on Airbnb.
- Seasonality Effect: Prices and bookings peak during summer months (June–August) and major holidays (Thanksgiving, Christmas, New Year’s Eve).
  
4. Reviews & Guest Satisfaction:
High Ratings: The majority of listings have ratings above 4.5, suggesting guests generally have positive experiences.

# Recommendations
1. For Hosts: Optimizing Listings for Higher Bookings
- Price Competitively:- Use dynamic pricing tools (e.g., Airbnb Smart Pricing, Beyond Pricing) to adjust rates based on demand.
- Compare prices with similar listings in the same neighborhood to stay competitive.

1. Enhance Listing Quality:
- High-quality photos and detailed descriptions improve booking rates.
- Emphasize unique features (e.g, rooftop views, proximity to landmarks).
2. Improve Guest Experience:
- Address common complaints like cleanliness, communication, and noise issues.
- Provide self-check-in options technological keypad locks for flexibility.

   Impact of reviews on Airbnb Listings:
  - Encourage guests to leave reviews by providing excellent services and sending nicely reminders after their stay.
   
# Conclusion
- The analysis of the Airbnb dataset provides valuable insights into pricing trends, neighborhood popularity, guest satisfaction, and regulatory impacts. Key findings highlight that location, pricing strategy, and listing quality significantly influence occupancy rates and revenue.

- For hosts, optimizing pricing, maintaining high ratings, and offering a great guest experience can lead to higher bookings. Investors can benefit from targeting high-demand areas and focusing on mid-to-long-term stays to comply with local regulations. Travelers can find better deals by booking in advance and exploring alternative neighborhoods.

- However, Airbnb’s impact on housing availability and affordability remains a concern in cities like New York, requiring policymakers to enforce regulations that balance tourism growth with local housing needs.
