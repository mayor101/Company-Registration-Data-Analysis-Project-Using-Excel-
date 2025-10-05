# Company-Registration-Data-Analysis-Project-Using-Excel-
This project involved cleaning of dataset, exploratory analysis of dataset and building of dashboard to show insights using excel. The dataset is in a workbook. The workbook has the raw data as the first sheet, then there is a working sheet, pivot table and a dashboard

Company Registration Data Analysis Using Excel 
1. Introduction
This report presents an analysis of anonymised company registration data, which includes turnover and trade type information. This analysis aims to identify sector trends, incorporation patterns, company closures, and other meaningful insights from the dataset.
The dataset was provided as an Excel workbook and analysed using Excel (PivotTables, charts, and formulas.
2. Data Preparation & Cleaning
Before conducting the analysis, several data-cleaning steps were performed to ensure accuracy and consistency:
•	Duplicates Removal: Identified and eliminated duplicate company records. 30 duplicate rows were found and deleted. 
•	Standardization of Columns: Adjusted inconsistent column names, values and formats (e.g., inconsistent dates, inconsistent casing ). Discovered that the incorporation date of some business organizations was later than the company's closed date(liquidation) which is logically impossible. 100 rows were found and deleted, so it does not affect the outcome of my analysis.
•	Handling Null Values: Removed unnecessary blank rows/fields and applied appropriate methods where deletion was not feasible.
•	Calculated Columns: Created new fields such as Sum of Turnover 2021 to 2025 and Flagged turnover to support deeper analysis.
These steps improved the dataset’s reliability and allowed for more meaningful insights.
________________________________________
3. Analysis
3.1 Sector Turnover Trends
•	Method: Turnover data was aggregated by sector and compared year-on-year. Line charts were used to visualise changes over time.
•	Findings:
o	My first chart showed the most consistent year-on-year growth, increasing steadily across the entire period. The company type ‘Others’ had the highest turnover in 2021, while Consultancy was the singular company type that had the highest turnover in the same year. 
o	There was a great decline in 2025. This is because many companies had yet to submit their accounts. 

3.2 Common Month of Incorporation
•	Method: Count of incorporations was grouped by month for all company types. PivotTables were used to segment by business type.
•	Findings:
o	Overall, the most common incorporation month is March. 
o	For Company type ‘Others’ and Construction, this trend holds true.
o	For Consultancy, incorporations peak in September.
•	Conclusion: While March is the most popular overall, incorporation seasonality varies by company type.
________________________________________
3.3 Closed Companies Over Time
•	Method: Companies flagged as "Closed" were counted per year.
•	Findings:
o	The number of closed companies increased from 2013 to 2022 and has been on the decrease since then.
o	Peaks in closures occurred in 2022, possibly linked to the effect of the pandemic on companies, as it was around then that the effect of the pandemic was being felt. 
•	Conclusion: Closures have been declining since 2022, suggesting that businesses are picking up. 

3.4 Additional Insights
•	Other Trends:
o	Private Limited Companies have the highest turnover, while Private Unlimited Companies had the lowest out of the company categories that had values. 
•	Trade Type Differences:
o	Farming companies tend to register in most in September, while Education tends to register most in October. 
________________________________________
4. Visualisations
The following visuals were used to support the analysis:
•	Line charts: Turnover trends by sector.
•	Column charts: Incorporations per month.
•	Stacked bar charts: Closed companies per year.
________________________________________
5. Conclusion
The analysis highlights key trends in company registration, turnover, and closures. Consultancy and construction stand out for their consistent growth, while incorporation patterns vary by company type. Closure rates have increased from 2013 to 2022, with notable differences across company types and categories
By first cleaning and preparing the data—through the removal of duplicates, column standardization, handling of null values, and the creation of calculated columns—the dataset became more accurate and reliable for analysis.
________________________________________
6. Recommendations
•	Monitor high-growth sectors like Construction and Consultancy.
•	Investigate causes of closures in 2022 so that they do not happen again, or things are put in place to mitigate the effect of the cause of such closures. 
•	Provide tailored support for businesses incorporating in off-peak months.

