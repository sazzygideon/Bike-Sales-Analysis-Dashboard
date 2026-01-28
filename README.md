# Bike Sales Analysis Dashboard

## Project Objective
The goal of this project was to analyze customer data to identify key factors that influence bike purchases, such as income, commute distance, and age.

## 🛠️ Data Cleaning & Preparation
Before building the dashboard, I performed several data transformation steps to ensure accuracy and readability:
* **Handling Categorical Shorthand:** Converted "M" and "S" to "Married" and "Single," and "M" and "F" to "Male" and "Female."
* **Data Type Correction:** Formatted Income as currency for accurate averaging.
* **Age Bracketing:** Used nested `IF` statements to group ages into Adolescent, Middle Age, and Old Age.
* **Custom Sorting:** Standardized "Commute Distance" categories so they sort logically on charts.

## 📈 Key Insights
* **Income Matters:** Customers who purchased bikes had a higher average income (approx. $72k) compared to those who didn't.
* **The "Middle Age" Sweet Spot:** The majority of bike buyers fall into the Middle Age bracket.
* **Commute Factor:** People with shorter commutes (0-1 miles) are significantly more likely to purchase a bike than those with long commutes.

## Dashboard Preview
![Bike Sales Dashboard](https://github.com/sazzygideon/Bike-Sales-Analysis-Dashboard/blob/main/dashboard_preview.PNG)

## Tools Used
* **Excel:** Data Cleaning (VLOOKUP, IF statements, Find/Replace).
* **Pivot Tables:** Data aggregation and analysis.
* **Pivot Charts:** Interactive visualizations and slicers.
