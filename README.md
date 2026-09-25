# Exploratory Data Analysis in Healthcare

## Executive Summary

This project analyzes healthcare admission records using SQL, Power Query, and Power BI.

SQL and Power Query were used to clean and prepare the dataset. Python/Pandas was then used for exploratory data analysis, including descriptive statistics, sorting, distribution analysis, and time-based exploration.Power BI was used to build an interactive dashboard summarizing the cleaned dataset.

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

Python and Pandas were used to further explore the cleaned dataset.

The analysis included:

- Summary statistics for age, billing amount, and length of stay
- Patient age distribution
- Comparison of billing amounts across groups
- Distribution of admission types
- Monthly hospital admission trends
- Investigation of numerical patterns and possible unusual values

Seaborn was used for exploratory visualizations such as histograms and box plots, while Matplotlib was used to visualize admission trends over time.

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
