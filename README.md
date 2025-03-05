# Analysis of Connecticut’s Real Estate Market

## PowerBI Dashboard
Link: 


## Table of Contents
* [PowerBI Dashboard](#PowerBI-dashboard)
* [Motivation](#motivation)
* [Questions](#questions)
* [Normalizing the Data](#Normalizing-the-Data)
* [Problems and Hurdles](#problems-and-hurdles)
* [Technologies Used](#technologies-used)
* [Sources](#Data-Sources)
* [Conclusion](#conclusion)

## Motivation:
Recently, my brother moved to Connecticut and became interested in buying a house. Knowing my passion for real estate, he asked me to help him find the best location and understand the key factors to consider when purchasing a home. As I researched, I realized there was an opportunity to dive deeper into this topic and make it the focus of my capstone project. By analyzing property sales data, I aim to uncover market trends, pricing patterns, and regional differences that can help not only my brother but also investors, buyers, and policymakers make informed decisions. 

## Questions:
•	What are the average, median, and standard deviation of sale prices?
•	How do property values compare between urban and rural areas?
•	What percentage of properties were sold above or below the assessed     value?
•	Which months have the highest number of property sales?
•	How did the market behave before and after COVID-19?
•	Are there seasonal patterns in property sales?

## Normalizing the Data
To make the data clear and easy to compare, I cleaned and organized it. I made sure numbers were in the right format, dates were consistent, and missing or incorrect data was fixed. I also standardized property types and town names to avoid confusion. To better understand trends, I calculated the sales ratio (sale price ÷ assessed value) and added year and month information. I also adjusted prices for inflation so we can compare sales from different years more accurately.

## Limitations
Cleaning and organizing the real estate sales data in Python was a challenge, especially with missing values and inconsistent formatting in property types and town names. Handling outliers in sale prices required careful analysis to avoid skewed results. Another hurdle was working with assessed values, as different towns had varying assessment methods, making direct comparisons difficult. Adjusting prices for inflation also required additional calculations to ensure fair comparisons across different years.
## Technologies Used
1) Data Analysis and VIsualization: Jupyter Notebook, Python (Pandas, Matplotlib, Seaborn)
2) Interactive Dashboard: PowerBI
3) PowerPoint - for introduction of the Project
4) Git - for version control

## Data Sources
To gather data for my analysis and answer these questions, I used the following source.
https://data.ct.gov/Housing-and-Development/Real-Estate-Sales-2001-2022-GL/5mzw-sjtu/about_data

## Conclusion
The data analysis reveals key trends in Connecticut’s real estate market, including variations in property sales, pricing patterns, and regional differences. Towns with the highest property values tend to have strong economic conditions, while more affordable areas may attract first-time buyers or investors. The analysis also highlights how assessed values compare to sale prices, showing where properties are selling above or below their estimated worth. While external factors like economic shifts and the COVID-19 pandemic influence the market, the findings provide useful insights for buyers, investors, and policymakers to make informed decisions about property investments and housing trends.
