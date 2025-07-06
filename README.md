# Credit-card-fraud-analysis

## Table of Contents

- [project overview](#project-overview)
- [Problem Statement](problem-statement)
- [Dataset Overview](Dataset-overview)
- [Data source](Data-source)
- [Tool used](tool-used)
- [Geography Dashboard Analysis](Geography-Dashboard-Analysis)
- [Time Series Dashboard Analysis](Time-Series-Dashboard-Analysis)
- [Methodology](Methodology)
- [Findings and Analysis](Findings-and-Analysis)
- [Recommendations](Recommendations)


### Project Overview

Credit card fraud represents a significant threat to the integrity of financial transactions and consumer trust in digital commerce. As the reliance on credit cards for everyday purchases continues to grow, so does the sophistication of fraudsters exploiting vulnerabilities in the system This project analyses historical credit card transaction data to detect fraud patterns and identify high-risk behaviours. Using Microsoft Excel, the data was cleaned, transformed, and modelled into interactive dashboards that uncover geographic and temporal insights around fraudulent activities

### Problem Statement

Credit card fraud continues to threaten financial security and customer trust. This project aims to analyse patterns of credit card fraud, understand the factors contributing to fraudulent activities, and explore effective methods for detection and prevention

### Dataset Overview

•	Rows: 100,000+ transactions

•	Columns: 7 (Transaction ID, Transaction Date, Amount, Merchant ID, Location, Transaction Type, Is Fraud)

•	Fraud Indicator: Binary (1 = Fraud, 0 = Legitimate)

### Data Source

This project uses a primary credit card dataset stored in a CSV file format. The dataset contains detailed information on credit card transactions.

### Tools Used

•	Microsoft Excel:


o	Power Query (for data cleaning and transformation)

o	Power Pivot (for modeling and DAX measures)

o	PivotTables & Charts (for analysis)



•	Excel Formulas: IF, WEEKDAY, TEXT, HOUR, COUNTIFS, AVERAGEIFS

•	Dashboard design: slicers, KPI cards, insight layout

### Geography Dashboard Analysis

Key Charts:

•	Fraud Rate by City

•	Top 5 Merchants ID defrauded by top 3 cities 

•	 Top 5 Merchants ID defrauded by top 3 cities through Refund transaction type 

•	Fraud volume refund vs purchase

KPI Cards:

•	City with Highest Fraud Rate

•	Most defrauded Merchant 

•	Total Fraudulent Transactions

•	Total legitimate transactions

### Time Series Dashboard Analysis

Key Charts:

•	Monthly Fraud Trend

•	Fraud by Hour of Day

•	Fraud by Day of Week

•	Fraud by week type

KPI Cards:

•	Peak Fraud Hour

•	Peak Fraud Day

•	Week type with highest fraud

•	Month with the highest fraud

### Methodology

•	Imported CSV file into Excel Power Query

•	Cleaned and transformed data: created Hour, DayOfWeek, WeekType, etc

•	Built calculated columns and DAX measures in Power Pivot

•	Developed separate dashboards for geography and time trends

•	Applied data visualizations and slicers for interactivity

### Findings and Analysis

•	Fraud peaked between 1–4 AM, especially on weekdays

•	Refunds made up only 49.27% of transactions, but 40% of fraud cases

•	Certain merchants in San Diego and New York had extremely high fraud volumes

•	Average fraud amount was significantly higher than legit transactions

•	Weekdays showed elevated fraud activity across all cities

### Recommendations

•	Monitor transactions during off-hours (12 AM – 5 AM) more closely

•	Flag refunds exceeding a threshold amount for manual review

•	Investigate top fraud-prone merchants with high refund-to-purchase ratios

•	Implement real-time alerts for location + time + transaction-type patterns

•	Use behavior-based thresholds rather than static rules



