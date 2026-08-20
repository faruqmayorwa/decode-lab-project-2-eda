# decode-lab-project-2-eda
Exploratory Data Analysis (EDA) project using Excel to analyse e-commerce data, identify trends, detect potential outliers, and generate actionable insights.
# Decode Lab Project 2 — Exploratory Data Analysis (EDA)

## Project Overview

This project was completed as part of my internship at Decode Lab.

The objective was to perform Exploratory Data Analysis (EDA) on an e-commerce order dataset using Microsoft Excel to understand patterns, trends, distributions, potential outliers and key findings. 

The analysis was performed using the cleaned dataset prepared in Project 1.

## Project Objectives

- Calculate descriptive statistics.
- Analyse numerical and categorical variables.
- Identify trends over time.
- Identify potential outliers.
- Create meaningful charts and summaries.
- Communicate key findings from the dataset.

## Dataset

The dataset contains **1,200 data records and 14 columns**.

Main variables include `OrderID`, `Date`, `CustomerID`, `Product`, `Quantity`, `UnitPrice`, `ShippingAddress`, `PaymentMethod`, `OrderStatus`, `TrackingNumber`, `ItemsInCart`, `CouponCode`, `ReferralSource`, and `TotalPrice`.

## Descriptive Statistics

The main numerical variables analysed were Quantity, UnitPrice, ItemsInCart, and TotalPrice.

| Variable | Count | Mean | Median | Minimum | Maximum |
|---|---:|---:|---:|---:|---:|
| Quantity | 1,200 | 2.95 | 3 | 1 | 5 |
| UnitPrice | 1,200 | $356.41 | $364.21 | $11.39 | $699.93 |
| ItemsInCart | 1,200 | 5.5 | 5 | 1 | 10 |
| TotalPrice | 1,200 | $1,083.97 | $923.62 | $11.39 | $3,456.40 |

## Outlier Analysis

TotalPrice showed the strongest indication of potential high-value observations because the mean ($1,083.97) was higher than the median ($923.62), while the maximum ($3,456.40) was substantially higher than the median.

Descriptive statistics indicate potential outliers; statistical confirmation can be performed using the IQR method.

## Sales Time Trend

| Year | Total Sales |
|---|---:|
| 2023 | $553K |
| 2024 | $480K |
| 2025 | $232K |

### Key Finding

Sales showed a clear declining trend, falling from approximately **$553K in 2023 to $232K in 2025**. The most significant decline occurred between 2024 and 2025.

This analysis identifies the decline but does not assume its cause without further investigation.

## Categorical Analysis

The EDA also examined Product, OrderStatus, PaymentMethod, and ReferralSource using PivotTables and summary tables.

## Visualisations

The project includes Excel visualisations for relevant findings, including sales trends, categorical distributions, and outlier analysis where applicable.

## Tools Used

- Microsoft Excel
- PivotTables
- Excel formulas
- Descriptive statistics
- Conditional Formatting
- Charts and data visualisation

## Workbook Structure

- `Raw_Data` — Original dataset.
- `Clean_Data` — Cleaned dataset from Project 1.
- `Data_Inspection` — Initial data-quality checks.
- `Cleaning_Log` — Data-cleaning documentation.
- `EDA` — Exploratory analysis, statistics, PivotTables, charts, and key findings.

## Key Learning Outcomes

- Performing exploratory data analysis in Excel.
- Calculating and interpreting descriptive statistics.
- Using PivotTables for analysis.
- Identifying potential outliers.
- Analysing trends over time.
- Creating data visualisations.
- Translating numerical results into business insights.

## Preview
- EDA 1 png: https://github.com/faruqmayorwa/decode-lab-project-2-eda/blob/main/EDA%201.png
- EDA 1 png: https://github.com/faruqmayorwa/decode-lab-project-2-eda/blob/main/EDA%202.png

## Conclusion

The exploratory analysis revealed a clear decline in total sales between 2023 and 2025, with the largest decline occurring between 2024 and 2025. The analysis also highlighted potential high-value observations in TotalPrice that require further statistical investigation.

