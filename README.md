# Mitron-Bank-analysis-project
## Background
Mitron Bank is a legacy financial institution headquartered in Hyderabad. aims to launch new credit cards, seeking diversification and extended market reach. AtliQ Data Services proposed a pilot project with a sample dataset of 4000 customers.

## Problem statement
Mitron Bank aims to introduce a new line of credit cards to expand its product offerings and market reach. My role involved analyzing the provided sample data and reporting key findings to Mitron Bank's strategy team. This analysis is expected to guide them in tailoring the credit cards to customer needs and market trends.

## Task
Design a dashboard with metrics and analysis. The end users of this dashboard are top-level management and the product strategy team. Therefore, the dashboard should be self-explanatory and easy to understand.

## Tools used
* Power BI
* Power Query
* DAX

## Data Collection
* Sample dataset of 4000 customers across five cities provided by Mitron Bank.
* Dataset includes online spending and other customer details.
* Loaded the CSV data file to Power BI
* Link for the data set : https://codebasics.io/challenge/codebasics-resume-project-challenge

## Data Cleaning & Transformation
* Checked for null and duplicate values.
* Utilized Power Query for data cleaning.
* Created a new table to showcase the incomeutilization data using the calculated column feature.
* Evaluation of income utilization percentages.
* Load and apply the cleaned data into Power BI report view

## Data Analysis
* With DAX Query, effectively manipulated and analyzed the data to provide insights for visualization and identify areas for improvement for Mitron Bank.
* Analyzed the distribution of active customers by gender, income category, and city.
* Explored average income for various categories like age group, city, gender, and occupation.
* Created measure for average income utilization % : avg income utilization % = AVERAGE(dim_customers[Avg_income_utilization%])
* Identification of spending patterns across different customer groups.

## Data Visualization
* Created 4 reports for analyzing demographic insights, income utilization, spending analysis and recommendations report
* Designed the dashboard layout and used charts, cards and filters for visualization
* Link to the dashboard : https://is.gd/x0b9m_MitronBank
