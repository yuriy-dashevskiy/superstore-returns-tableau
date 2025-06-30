# SuperStore Returns Analytics

## Overview
* This analytical project provides a dynamically interactive tableau dashboard, saved publically on tableau, for analyzing return patterns for the Superclient client.
* Goal was to determine any trends surrounding the alarming rate of return of products and come up with an executive decision based on the data-driven analysis.
---
📊📉[Public Tableau Dashboard](https://public.tableau.com/app/profile/yuriy.dashevskiy/viz/Yuriy_Dashevskiy_Superstore_Project_Tripleten_Sprint_5/Superstore_Dashboard)
---
## 🎯 Objectives <br/>
* Determine the categories/regions experiencing high return rate
* Analyze the trends based time of the year
* Present visuals on return rate vs revenue earned
* Come up with insights based on analysis to present to stakeholders
---
## 📊 Dataset <br/>
Superstore provided Orders and Returns information for helping create this analysis
* Left joined two tables <b>Orders</b> and <b>Returns</b> to create a complete list of all orders regardless if they had a return or not
---
## 📈 Key Metrics <br/>
* Avg Returns = ROUND(AVG([Returns]) * 100,2)
* Returns = IF ISNULL([Returned]) THEN 0 ELSE 1 END
* Total Returns = SUM(Returns)
* Total Sales = SUM(Sales)
---
## 🛠️ Tools Used <br/>
* Tableau - Creating the visuals utilizing the Superstore excel file
* Excel/Google Sheets - Data cleaning
---
## 📌 Visual Features <br/>
* Dual-Axis Chart - Return Rate by Category/Region
* Map Visualization - Return Rates by USA States
* Customer Breakdown - Return Rate by Customer
* Time Series Trends - Return Rate Over Time (Periodically)
---
## Sample Dashboard Screenshot <br/> <br/>
![image](https://github.com/user-attachments/assets/24f0c3a1-e225-43c9-a98a-272e1fbc6d99)

## Future Improvements
* Create different visualizations for analyzing the given data in another perspective
* Connect to a locally installed SQL DB to have the visuals be dynamically reflect what is stored in the database
