# Task
Overview

This repository contains two data analysis projects completed using Microsoft Excel. The projects focus on data cleaning, preparation, transformation, and exploratory data analysis (EDA) to generate meaningful insights from raw datasets.
Project 1: Data Cleaning and Preparation

Project Description

The purpose of this project was to clean and prepare raw business data for analysis using Microsoft Excel and Power Query. Several data quality issues such as duplicates, missing values, inconsistent formatting, and incorrect data types were identified and corrected.
Objectives

• Improve overall data quality • Remove duplicate records • Handle missing values • Standardize data formats • Prepare the dataset for analysis and reporting
Tools Used

• Microsoft Excel • Power Query
Dataset Information

The dataset contains business and operational records used for analytical reporting and data-driven decision-making.
Data Cleaning Process

The following cleaning operations were performed using Power Query:
1. Removed duplicate rows
2. Handled missing values
3. Standardized text formatting
4. Changed incorrect data types
5. Renamed columns for consistency
6. Structured the dataset for analysis

Messy Dataset

Initial raw dataset before cleaning and transformation.


Power Query Techniques Used

• Remove Duplicates • Replace Values • Change Data Types • Additional Columns • Filtering and Sorting • Data Transformation

Power Query Transformation Steps

Power Query was used to clean, transform, and standardize the dataset.


Cleaned Dataset

Dataset after cleaning and preparation using Power Query.


Challenges Faced

• Missing values • Duplicate records • Inconsistent formatting • Incorrect data types
Outcome

The raw dataset was successfully transformed into a clean, organized, and analysis-ready dataset suitable for reporting and further analysis.

Project 2: Exploratory Data Analysis (EDA)

Project Description

This project focuses on exploring and analyzing data using Microsoft Excel to identify trends, patterns, relationships, and business insights.
Objectives

• Analyze trends and patterns in the dataset • Summarize data using descriptive statistics • Identify key performance observations
Tools Used

• Microsoft Excel • Pivot Tables • Descriptive Statistics • Quartile Calculations
Analysis Performed

The following analyses were conducted: • Descriptive statistical analysis • Pivot table analysis • Quartile calculations • Trend analysis • Category comparisons • Performance analysis
Analytical Techniques Used

• Mean, Median, and Mode • Minimum and Maximum Values • Standard Deviation • Quartile Analysis • Frequency Distribution • Pivot Table Summarization • Data Filtering and Sorting

Basic Descriptive Statistics

Summary statistics used to understand the dataset distribution.


Advanced Descriptive Statistics

Advanced statistical analysis for deeper data insights.


Pivot Table Analysis

Pivot tables used to summarize and analyze trends.


Quartile Analysis

Quartile calculations used to identify data distribution and outliers.


Key Insights

• Certain categories consistently performed better than others • Some values showed high variability across records • Quartile analysis helped identify outliers and distribution patterns • Pivot tables simplified category analysis
Challenges Faced

• Inconsistent formatting • Large data organization • Data preparation before analysis
Outcome

The exploratory data analysis provided meaningful insights and improved understanding of the dataset through statistical summaries and trend analysis.

Project 3: SQL Retail Data Analysis

Project Overview

This project focused on analyzing the Online Retail Dataset using Microsoft SQL Server and SQL Server Management Studio (SSMS). The objective of the project was to apply SQL querying, data cleaning, filtering, aggregation, and reporting techniques to extract meaningful business insights from retail transaction data.
Tools Used

• Microsoft SQL Server • SQL Server Management Studio • SQL
Database Setup and Data Cleaning

The dataset was successfully imported into SQL Server from a CSV file. Data cleaning and transformation processes were carried out to improve data quality and prepare the dataset for analysis.
The following cleaning tasks were performed: Replaced blank values in the Coupon Code column with “No Coupon” Created additional columns for: • Order_Year • Order_Month Extracted date values using SQL date functions Verified and adjusted data types where necessary
Creating Database

Database creation after file has been imported into the SQL server in CSV format.


Table Created

Full Table Displayed


Data Cleaning SQL

Data Cleaning queries in preparation for analysis


Removing Blank Rows

NULL values replace with NO COUPON


Year and Month Extraction

Table altered to accomodate the Year and Month column


SQL Skills and Techniques Applied

The project demonstrated practical use of SQL concepts and analytical functions, including:
SQL Clauses and Operations

• SELECT • WHERE • ORDER BY • GROUP BY • HAVING • UPDATE

Filtering Records

WHERE clause used to filter records


Sorting Records

ORDER BY used to sort records


GROUP BY Clause

Payment Method grouped by the Total Revenue


HAVING Clause

Analyzed queries with HAVING


Aggregate Functions

• SUM() • AVG() • COUNT()
Additional SQL Techniques

• Date extraction functions • Conditional filtering • Data aggregation • Business reporting queries

Top 3 Products Query

Additional Queries

Key Findings and Business Insights

Overall Metrics Performance

Metric	Value
Total Orders	1,200
Total Revenue	1,264,761.96
Average Order Value	1,053.97
Average Quantity Ordered	2 Items
Cancelled Orders	251
Customer and Payment Insights

Most Used Payment Method

• Online Payments (259 transactions)
Highest Revenue Payment Method

• Credit Card — 263,847.63
Top Referral Source

• Instagram (260 referrals)
Highest Revenue Referral Source

• Instagram — 275,285.45
Product Performance

Top 3 Products by Revenue

	
	
	
	
Products with sales greater than 2000 included:

• Chair • Desk • Laptop • Monitor • Phone • Printer • Tablet
Highest Individual Total Price

• Product: Tablet • Coupon Code: SAVE10 • Total Price: 3,456.40
Lowest Recorded Price

• Product: Phone • Referral Source: Email • Total Price: 11.39
Revenue Analysis

Revenue by Payment Method

	
	
	
	
	
	
Revenue by Referral Source

	
	
	
	
	
	
Conclusion

This project demonstrated practical SQL and data analysis skills through the use of a real-world retail dataset. SQL queries were effectively used to clean, organize, analyze, and summarize transactional data into actionable business insights.
The analysis provided visibility into: • Customer behavior • Product performance • Payment trends • Revenue distribution
Overall, the project strengthened foundational SQL skills and showcased the ability to transform raw transactional data into meaningful business intelligence suitable for reporting and decision-making.

Project 4: Power BI Data Visualization

Project Overview

This project analyzes an Online Retail Dataset using Power BI to transform raw transactional data into meaningful business insights. The goal was to perform data cleaning, modeling, visualization, and dashboard development to help stakeholders understand sales performance, customer behavior, product profitability, and operational efficiency.
The final solution consists of multiple interactive dashboards that provide a comprehensive view of the business through KPIs, sales trends, product analysis, and order management metrics.
Project Objectives

• Clean and prepare retail transaction data • Build a data model suitable for analysis • Create DAX measures and KPIs • Develop interactive dashboards for decision-making • Identify trends, opportunities, and operational challenges • Communicate insights through data storytelling
Tools Used

• Power BI • Power Query • DAX • Microsoft Excel (Dataset Source)
Data Cleaning and Preparation

Data preparation was performed in Power Query and included: • Correcting data types • Handling missing values in the Coupon Code column • Replacing blank coupon values with "No Coupon Used" • Removing duplicate records • Validating revenue calculations • Creating date-related fields • Building a Date Table for time intelligence analysis
Data Modeling

A Date Table was created and linked to the main retail table to support: • Yearly analysis • Monthly analysis • Quarterly reporting • Time-based filtering
Relationships were established to improve reporting performance and enable DAX calculations.

Relationship



DAX Measures Created

Revenue Metrics

• Total Revenue • Average Order Value
Customer Metrics

• Total Customers • Total Orders
Sales Metrics

• Total Quantity Sold • Coupon Usage Percentage
Time Intelligence Metrics

• Monthly Revenue • Yearly Revenue • Revenue Trends

Note: The dashboards were designed in a boardroom-style presentation format, as specified in the project instructions, to ensure clarity and executive-level readability.



Dashboard 1: Sales Performance Overview

This dashboard provides a high-level view of business performance.
KPIs

• Total Revenue: $1.26M • Total Orders: 1,200 • Total Customers: 1,189 • Total Quantity Sold: 3,535 • Average Order Value: $1.05K
Dashboard Screenshot


Key Findings

• Revenue exceeded $1.26M • 1,200 orders were processed • 1,189 unique customers were served • Average order value reached $1.05K

Dashboard 2: Top Products by Revenue

This dashboard evaluates product performance based on revenue generation.
Dashboard Screenshot


Key Findings

• Chairs generated the highest revenue ($196K) • Printers generated approximately $196K • Phones generated the lowest revenue ($152K) • Product revenue contribution varied significantly across categories

Dashboard 3: Sales Trend Analysis

This dashboard focuses on revenue patterns over time.
Dashboard Screenshot


Key Findings

• Revenue peaked in June ($171K) • September recorded the lowest revenue ($69K) • Revenue declined significantly in the second half of the year • Strong sales growth occurred between April and June

Dashboard 4: Order and Payment Analysis

This dashboard evaluates transaction methods and order fulfillment performance.
Dashboard Screenshot


Key Findings

• Online payments recorded the highest order volume (258) • Customers showed a preference for digital payment methods • Cancelled orders (250) exceeded Delivered orders (231) • Fulfillment performance presents an opportunity for improvement

Recommendations

Product Strategy

• Increase marketing efforts for underperforming products • Expand promotion of high-performing categories
Sales Strategy

• Align inventory planning with peak sales periods • Prepare for seasonal demand fluctuations
Operational Improvements

• Investigate causes of cancellations and returns • Improve fulfillment and delivery processes
Customer Retention

• Implement customer loyalty programs • Reduce dependence on discount-based purchases
Payment Experience

• Continue optimizing digital payment channels • Improve customer checkout experience
