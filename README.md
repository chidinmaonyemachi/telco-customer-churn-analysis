# Customer Behaviour & Business Performance Analysis

## Project Overview

This project analyzes customer churn patterns using the Telco Customer Churn dataset. The analysis explores customer characteristics, contract types, tenure, monthly charges, and service adoption to identify patterns associated with customer churn and retention.

## Business Problem

ABC Communications Ltd wants to investigate customer churn and provide business insights that support customer retention strategies.

## Objectives

• Understand a business problem.
• Explore and analyse business datasets.
• Identify trends and patterns.
• Create professional visualisations.
• Develop business recommendations.
• Present findings professionally.

## Dataset

The project uses the Telco Customer Churn dataset.

The unit of observation is one customer per row.

The dataset contains customer demographic information, account information, services, charges, contract information, and churn status.

## Data Preparation

The analysis included:

- Data quality inspection
- Missing-value checks
- Duplicate customer ID checks
- Validation and conversion of charge fields to numeric values
- Review of categorical values
- Creation of ServiceCount
- Creation of helper calculations for interactive analysis

## Analysis

The project uses:

- Excel PivotTables
- PivotCharts
- Slicers
- KPI calculations
- Box plot analysis
- Correlation heat map
- Interactive dashboard

## Key Findings

1. Month-to-month customers have meaningfully higher churn than customers on one- or two-year contracts.

2. Longer-tenured customers tend to have greater service adoption, reflected in the moderate tenure–Service Count correlation.


3. Fiber optic customers have the highest churn rate, despite the service being a higher-value offering.

4. Compared with the relationship between tenure and service adoption, the correlation involving Senior Citizen is relatively weak.

5. Monthly charges should be considered alongside factors such as contract type and tenure rather than treated as an isolated cause of churn.

## Recommendations

1. Create targeted retention campaigns for month-to-month customers and encourage migration to one-year or two-year contracts.

2. Review fiber customers' service quality, pricing, installation experience, complaints, and support interactions.

3. Provide incentives for customers to remain longer, such as loyalty benefits, contract upgrades, bundled services, or preferential offers.

4. Create a structured engagement process for newer customers, including onboarding communication, service education and early satisfaction checks.

5. Analyze churn across monthly-charge bands and customer segments to determine whether particular pricing or service combinations require attention.

## Dashboard

![Telco Customer Churn Dashboard](images/dashboard.png)

## Tools Used

- Microsoft Excel
- PivotTables
- Excel formulas
- Conditional formatting
- Data visualization
- GitHub

## Project Files

- [Business Understanding Report](reports/Business_Understanding_Report.pdf)
- [Dataset Inspection Report](reports/Dataset_Inspection_Report.pdf)
- [Excel Analysis Workbook](excel/Telco_Churn_Analysis.xlsx)
- [Presentation](presentation/Telco_Churn_Analysis.pptx)

 **Note:** The findings describe patterns and associations identified in the available customer data. Correlation and distributional analysis do not establish that a particular factor directly causes customer churn.
