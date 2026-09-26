# Exploratory Data Analysis in Healthcare

## Executive Summary

This project analyzes healthcare admission records using SQL, Power Query, and Power BI.

SQL and Power Query were used to clean, transform, and prepare the healthcare dataset for analysis, including removing duplicates, correcting data types, standardizing values, and creating calculated fields. Power BI was then used to analyze the cleaned data and build an interactive dashboard highlighting patient demographics, billing, admission types, length of stay, and admission trends over time.

The analysis focused on patient age, billing amounts, medical conditions, admission types, length of stay, and admission trends over time.

## Data Cleaning

The dataset was cleaned by:

- Removing duplicate records
- Removing records with negative billing amounts
- Standardizing formatting issues in the hospital column
- Creating a new **Length of Stay** column using the difference between admission and discharge dates
- Converting admission and discharge dates into appropriate date formats for analysis

The cleaned dataset was then used for exploratory analysis and visualization.

<img width="500" alt="Healthcare EDA Dashboard"
src="https://github.com/user-attachments/assets/acf8d701-52af-40a4-8562-496ed3999f26" />

## Exploratory Data Analysis

SQL and Power Query were used to clean, transform, and prepare the healthcare dataset for analysis. This included removing duplicate records, filtering invalid billing values, standardizing hospital names, formatting date fields, and creating a Length of Stay column.

Power BI was then used to analyze and visualize the cleaned data through an interactive dashboard.

The analysis included:

- Patient age distribution
- Billing amount comparisons
- Admission type distribution
- Length of stay analysis
- Medical condition comparisons
- Monthly hospital admission trends

Power BI visuals were used to identify patterns, compare categories, and summarize the overall performance and structure of the dataset.

## Key Findings

The dataset showed relatively even distributions across several major variables.

- Patient ages were distributed fairly evenly across most of the age range.
- The average and median billing amounts were very similar, suggesting no strong overall skew in billing values.
- Length of stay had an average of approximately 15.5 days and a median of 15 days.
- Admission types were relatively evenly represented.
- Monthly admission counts were generally stable across most of the dataset, although the first and last months contained fewer records because they represented partial periods.

Overall, the project demonstrated that the dataset did not contain strong differences across many of the explored categories. As a result, data preparation and validation became an important part of the analysis.

<img width="700" alt="EDA for the Healthcare_db"
src="https://github.com/user-attachments/assets/24631775-1bfc-4d7c-b4b6-b0da86422c3a" />

## Tools Used

## Tools and Techniques Used

- **SQL:** CTEs, `DELETE`, `UPDATE`, `WHERE`, duplicate removal, data standardization
- **Power BI:** Interactive dashboard and trend visualization
- **Power Query:** Data type changes and additional formatting
