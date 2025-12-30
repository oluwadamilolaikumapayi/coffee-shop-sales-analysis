# Coffee-Shop-Sales-Analysis
Analyzed multi-location coffee shop sales data to uncover revenue trends, peak transaction periods, and product performance. Built an interactive Excel dashboard using pivot tables, charts, and slicers to deliver actionable insights for improving staffing, inventory planning, and sales strategy across stores.


## Project Overview 

To analyzes the data set and identify key performance indicators including total
revenue, transaction volume, and product performance across multiple dimensions
such as store location, time (hourly), day of the week, month, and product category.
It also highlights the Top 10 best-selling products, enabling stakeholders to quickly
identify high-performing items and underperforming areas.


<img width="1552" height="1147" alt="coffee _sales_dashboard " src="https://github.com/user-attachments/assets/8baad05c-dba1-4d12-bf88-6c5227ce652f" />


### Business Problem 

The business seeks to understand sales performance across store locations, time periods, and product categories to optimize revenue and operational efficiency.

### Project Objective 
1. Identify revenue and transaction trends

2. Analyze peak and low-performing periods

3. Evaluate product category performance

4. Support data-driven business decisions

### Data Source 

Sales Data: This the Primary Dataset use for this analysis "data/Coffee_Shop_Sales[1].csv"

### Tools 

-Microsoft Excel

-Pivot Tables & Charts

-Slicers

-Interactive Dashboard Design

### Data Cleaning 

1. Data Import & Validation

- Imported the raw CSV file into Excel using Data → Get Data → From Text/CSV

- Verified column headers, data types, and row counts after import

- Ensured numeric fields (sales, quantity, transaction values) were correctly recognized as numbers

2. Handling Missing Values

- Checked for missing or blank values across key fields such as transaction date, store location, product category, and revenue

- Removed records with critical missing data that could impact analysis

- Confirmed no null values remained in KPI-related columns

3. Date & Time Formatting

- Standardized date fields to a consistent date format

- Extracted hour, day of week, and month from transaction timestamps to enable time-based analysis

- Validated that all time values fell within expected business operating hours

4. Data Consistency & Standardization

- Ensured consistent naming for store locations (e.g., removing spelling variations and extra spaces)

- Standardized product category names to prevent duplicate groupings

- Removed leading and trailing spaces using Excel cleaning functions

5. Data Accuracy Checks

- Validated revenue calculations by cross-checking quantity × unit price where applicable

- Reviewed outliers and extreme values to ensure they represented valid transactions

- Confirmed totals aligned with expected business ranges

6. Dataset Preparation

- Converted the cleaned dataset into an Excel table for structured analysis

- Used the cleaned data to build pivot tables, charts, and an interactive dashboard

- Saved the final dataset and dashboard in separate folders for clarity and reproducibility

### Key Insight 

- June recorded the highest revenue (£166,486)

<img width="1281" height="209" alt="q1" src="https://github.com/user-attachments/assets/3bcde7b0-2699-4d98-9965-3878d85afe2f" />

- 10:00 AM accounted for over 80% of total transactions

<img width="554" height="305" alt="q2 " src="https://github.com/user-attachments/assets/ecda47cf-8447-4b22-8265-a8efe5ecbb27" />

- Coffee generated over 90% of total revenue

<img width="544" height="363" alt="q3" src="https://github.com/user-attachments/assets/ae168ccd-a4c7-4662-a33a-1a68657c9d36" />


- Friday was the highest-performing day (£21,701)

<img width="563" height="349" alt="q4" src="https://github.com/user-attachments/assets/cd2b09c8-105b-451d-ab0b-fd06e0938d7f" />


### Business Recommendation 

Based on the analysis ,i recommend the following actions;

- Optimize morning staffing and inventory

- Introduce seasonal promotions

- Reduce evening operational costs

- Expand coffee-focused product strategy

