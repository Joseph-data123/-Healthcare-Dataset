# Exploratory Data Analysis in Healthcare

## Executive Summary

This project analyzes healthcare admission records using **SQL, Power Query, Python/Pandas, and Power BI**.

SQL and Power Query were used to clean, transform, and prepare the dataset by removing duplicates, correcting data types, standardizing values, and creating calculated fields. **Python and Pandas** were then used for exploratory data analysis, including descriptive statistics, distribution analysis, sorting, and time-based exploration.

Power BI was used to build an interactive dashboard highlighting patient demographics, billing amounts, medical conditions, admission types, length of stay, and admission trends over time.

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

Python and Pandas were then used for exploratory data analysis, including descriptive statistics, distribution analysis, sorting, and examining trends over time.

Power BI was used to create an interactive dashboard that visualized:

- Patient age distribution
- Billing amount comparisons
- Admission type distribution
- Length of stay
- Medical condition comparisons
- Monthly hospital admission trends

Together, Python and Power BI were used to explore the dataset, identify patterns, compare categories, and communicate the key findings visually.
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
- **SQL:** Data cleaning and standardization  
- **Python/Pandas:** Exploratory data analysis and descriptive statistics  
- **Matplotlib & Seaborn:** Histograms, box plots, and trend visualizations to explore distributions and identify possible outliers  
- **Power Query:** Data transformation and formatting  
- **Power BI:** Interactive dashboard and data visualization  
