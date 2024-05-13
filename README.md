**Important Note**

- original datasets cannot be shared due to NDA (only workproducts such as viz and insights)
- specific data points are anonymized by our stakeholder for security purposes 

**Project Summary**

Solar Turbines Global Supply Chain Operations Analytics Project (Jan 2024 - Current)

- My role in this project was to conduct analysis for 3 scenarios
  1) General Cost Overview For All Domestic and Foreign Shipments
  2) Cost Per Mile Analysis (Domestic Shipments)
  3) Cost Per Pound Analysis (International Shipments) 

- Our team's overall objective is to collaborate with Solar Turbines' SCM team to analyze global shipping data, identify accessorial charge trends, and optimize shipping mode mixes, resulting in shipping charge reductions.
  
- The objectives pertaining to my specifc role include:
  1) identifying data quality issues, data cleaning, data transforming 
  2) extract and present unique cost trends and patterns with the data given to us
  3) develop robust dashboarding tools that can be handed off to Solar Turbines so that they can conduct futher analysis. 

  ________________________
  **Challenges**
  - anonymized data makes it hard for us to conduct any product analysis
  - only given data for past 3 years
  - data inconsistency and incompleteness; data required heavy cleaning
  - extremely large datasets increased script execution time
 
  **Technology Used**
  - Python
  - Tableau
  - Excel

  **Techniques Used**
  - intial exploratory data analysis using python to identify data quality issues and outliers
  - transformed values and created new variables using python and excel
  - analyzed data trends and visualized data using Tableau
  - created calculated fields on-the-fly in Tableau to observe how new variables react

  **Results**

![Screenshot 2024-05-13 084411](https://github.com/samgeles/Solar-Turbines/assets/143467895/bc4e68fb-e056-4d2b-a4b7-165ca528675b)

Overall average accessorial charges have been increasing year over year. When looking at in-year accessorial charge trends we can actually observe a trend reversal. Years 2020 and 2021 have exhibited downward trends for accessorial charges, but now years 2022 and 2023 have been exhibiting increasing avg accessorial charge trends.

When looking at the relationship between costs and carriers used we’ve identified that carrier Davis-Robinson has highest total amount paid for shipments, carrier Jones-Jones has highest avg amount paid for shipments, and carrier Taylor Ltd has highest count of shipments. 


![Screenshot 2024-05-13 095033](https://github.com/samgeles/Solar-Turbines/assets/143467895/51568f8b-de81-40f1-83c3-ebe5f4a9b060)

Overall average cost per mile has been increasing since the start of 2021 . All quarters exhibit an increasing average cost per mile with the highest averages sitting in the 4th quarter.

Carrier Edwards-Hicks has the highest average cost per mile for shipments. Shipments with carrier Mcneil, Frank and Wise tend to have the highest average mileage


![Screenshot 2024-05-13 094958](https://github.com/samgeles/Solar-Turbines/assets/143467895/07c1e40f-188a-4057-8b9b-dcbfa8a640ac)

There’s a few notable trends here, the first being that the avg cost per pound for international  shipments in 2021 was highest with a steep drop off starting in the second quarter. The second notable trend is an overall increasing avg cost per pound from mid 2021 to the end of 2023. The last trend yearly trend we can observe is a trend reversal for avg cost per pound within each year, where 2020 and 2021 have high to low trends and 2022 and 2023 have generally increasing avg costs throughout each year.

Moving on to the bottom, when we look at international destination countries we can observe that Israel and Hungary are the two countries where shipments have been demanding the highest average cost per pound



  ________________________



