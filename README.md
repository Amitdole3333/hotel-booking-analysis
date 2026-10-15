# Hotel Booking Analysis

## Project Overview

This is my first data analytics project, built as a learning exercise to practise analysing hotel booking data using Microsoft Excel.

The objective was to clean and transform hotel booking data, identify patterns in booking cancellations, guest types, and room preferences, and present the findings through Pivot Tables and an interactive Excel Dashboard.

## Dataset

- **Source:** Kaggle
- **Topic:** Hotel Bookings
- **Hotel Types:** City Hotel and Resort Hotel

## Tools Used

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data analysis and dashboard creation |
| Power Query | Data cleaning and transformation |
| Excel Formulas (`IF` / `AND`) | Guest and room preference classification |
| Pivot Tables | Analysing booking and cancellation patterns |
| Excel Dashboard | Visualising key metrics and insights |

## Project Workflow

1. Imported the hotel booking dataset into Excel using Power Query.
2. Removed unnecessary columns and performed data cleaning and transformation.
3. Created a **Room Type** classification column using `IF` and `AND` logic to classify bookings as *Desired* or *Un-Desired*.
4. Created a **Guest Type** classification column to categorise guests as *Couples*, *Family*, or *Singles*.
5. Built Pivot Tables to analyse booking volumes and cancellation patterns.
6. Developed an Excel Dashboard with KPI cards, charts, and a year slicer.
7. Prepared an Insights Report summarising the key findings and business recommendations.

## Key Insights

1. **Overall Cancellation Rate:** 37.04%
2. **City Hotel Cancellation Rate:** 41.73%, compared with 27.76% for Resort Hotel.
3. **Highest Cancelled Bookings by Month:** August recorded 5,239 cancelled bookings.
4. **Couples Cancellation Rate:** 39.75%, the highest among the analysed guest types.
5. **Room Preference:** Desired Room bookings had a cancellation rate of 41.56%, compared with 5.38% for Un-Desired Room bookings.

## Dashboard

The Excel Dashboard provides a visual overview of hotel booking performance, including:

- Booking and cancellation KPIs
- Room preference analysis
- Hotel-wise booking and cancellation patterns
- Monthly booking trends
- Guest type analysis
- Year slicer for interactive filtering

## Project Files

### 1. Excel Workbook

Contains the hotel booking data, Pivot Tables, and the interactive Excel Dashboard.

[**View Excel Workbook**](My%20EXcel%20project.xlsx)

### 2. Insights Report

A report covering the project's key findings, cancellation patterns, business recommendations, and conclusion.

[**View Insights Report (PDF)**](Hotel_Booking_Analysis_Insights_Report.pdf)

## Business Recommendations

Based on the observed patterns, the following areas could be investigated further:

- **Review City Hotel cancellations:** Investigate booking characteristics associated with the higher cancellation rate.
- **Analyse seasonal patterns:** Examine August cancellations to understand seasonal booking behaviour.
- **Improve confirmation processes:** Evaluate confirmation messages and pre-arrival reminders for bookings classified as Couples.
- **Investigate room preferences:** Review the relationship between room preference classifications and cancellation outcomes.
- **Monitor cancellation KPIs:** Track cancellation counts and rates across hotel types, months, and guest categories.

## Learning Outcomes

Through this project, I practised:

- Importing, cleaning, and transforming data using Power Query
- Applying Excel formulas to create classification columns
- Analysing data using Pivot Tables
- Creating KPI cards, charts, and an interactive dashboard
- Identifying business patterns and communicating findings
- Presenting an end-to-end data analysis project

## Conclusion

This project helped me understand the basic end-to-end data analytics workflow, from raw data preparation to analysis, visualisation, and business recommendations. It strengthened my practical Excel skills and provided a foundation for further learning in SQL, Power BI, and Python-based data analysis.
