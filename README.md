# Stock Analysis Dashboard (Power BI)

# Objective:

The goal of this project is to create a detailed, insightful, and visually compelling dashboard using stock market data from 1st January 2020 to 11th November 2024. This dashboard analyzes the performance of selected stocks, focusing on key metrics and trends to aid in decision-making and investment strategies.

# Dataset Overview:

The dataset comprises daily trading data for the following stocks:

HCLTECH.NS

HINDUNILVR.NS

INFY.NS

ITC.NS

NESTLEIND.NS

TECHM.NS

WIPRO.NS

# Columns in the Dataset:

Date: The trading date.

Open: The price at market opening.

High: The highest price during the trading session.

Low: The lowest price during the trading session.

Close: The price at market close.

Adj Close: The closing price adjusted for splits and dividends.

Volume: The number of shares traded.

# Data Cleaning:

To ensure a clean and reliable dataset, the following data cleaning steps were taken:

Removed Duplicates: Ensured no duplicate entries were present in the data.

Handled Missing Values: Any missing data points were either filled using interpolation or removed if deemed unnecessary.

Validated Data Types: Confirmed that date columns were properly formatted as date types and numerical columns retained their correct data types.

Standardized Date Format: Unified the date column to a consistent format for seamless data modeling.

# Data Modeling:

The following steps were implemented during the data modeling phase:

Date Table Creation: Created a separate date table for accurate time-based analysis. Power BI requires a dedicated date table to ensure optimal performance.

Relationships Established: Linked the stock data table to the date table using the date columns.

Measure Table: A measure table was created to store key calculated metrics, including:

Average Volume

Sum of Volume

Min and Max Open, High, Low, Close prices

# Creating Visualizations:

KPIs (Cards):

Displayed the following KPIs using card visuals for an at-a-glance summary:

Average Volume

Total Volume

Min/Max of Open, High, Low, Close prices

# Time Series Analysis (Line Chart):

A line chart was created to show trends in the sum of low, sum of high, and average volume by month and year. Key insights:

Identified periods of high and low trading activity.

Visualized trends over the multi-year period.

Quarterly and Categorical Analysis (Donut and Pie Charts):

Sum of Volume by Quarters: Displayed in a donut chart to visualize trading volume distribution across Q1, Q2, Q3, and Q4.

Average Volume by Stock: A bar chart was used to compare average trading volumes across the selected stocks.

# Min/Max Prices (KPIs):

 Displayed as individual cards to highlight:

Min of Open, High, Low, Close prices

Max of Open, High, Low, Close prices

# Filters (Slicers):

Interactive slicers were created for user flexibility, allowing filtering based on:

Stock selection: Users can choose specific stocks for targeted analysis.

Date range: Users can filter data to analyze specific periods.

Quarters: Filter data based on quarters for seasonal trend analysis.

# Color Coding in Visuals:

Dark green: Indicates highest values (e.g., maximum prices, highest volume).

Light green/Teal: Used for mid-range values.

Grey: Denotes the lowest values (e.g., minimum prices, lowest volume).

# Dashboard Screenshot:
 ![Company-Stock-Analysis-Power-Bi](images/dashboard.jpeg)

# Conclusion:

The Stock Analysis Dashboard provides a comprehensive overview of key performance metrics for the selected stocks, allowing stakeholders to understand market trends, identify high and low trading periods, and make informed investment decisions. The interactive nature of the dashboard, coupled with consistent color coding, enhances user experience by enabling easy navigation and customized analysis.

This project highlights the power of Power BI in transforming complex stock market data into a clear, actionable, and visually engaging format.
