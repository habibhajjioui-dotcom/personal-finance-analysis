# Personal Finance Data Analysis

An end-to-end data analysis project built on a dataset of 32,424 personal finance records. The project covers data profiling, feature engineering, SQL analysis, and visualization using Excel, MySQL Workbench, and Power BI.

---

## Tools

- Microsoft Excel — data profiling, feature engineering, pivot tables
- MySQL Workbench — data import, cleaning, SQL queries
- Power BI Desktop — dashboard and visualizations

---

## Dataset

Source: Kaggle — Synthetic Personal Finance Dataset  
Size: 32,424 rows, 19 columns  
Fields: income, savings, loans, credit scores, age, gender, region, employment status

---

## Workflow

**Step 1 — Data Profiling**  
Reviewed all 19 columns for data types, unique values, and missing values using COUNTBLANK in Excel. Zero missing values were found across all rows.

**Step 2 — Feature Engineering**  
Created three new columns to support analysis:
- age_category: grouped ages into Young Adult, Adult, Senior Adult, Elderly
- income_bracket: classified income into Low, Middle, Upper-Middle, High
- loan_status_label: converted Yes/No loan field into readable labels

**Step 3 — Data Cleaning in SQL**  
After importing the dataset into MySQL, two corrupt values (the letter A) were found in numeric columns using a REGEXP query and corrected using UPDATE statements.

**Step 4 — SQL Analysis**  
Six queries were written to extract insights across income, loans, credit scores, savings, and job titles.

**Step 5 — Power BI Dashboard**  
Five bar charts were built from the raw dataset covering income by education, loan rates by employment status, savings by income bracket, credit score by region, and debt ratio by age group.

---

## SQL Queries and Findings

**Average Income by Education Level**  
All education groups earn between $3,990 and $4,048 per month. The difference is minimal, consistent with synthetic data.

**Loan Interest Rate by Employment Status**  
Unemployed borrowers carry the highest average interest rate at 16.75%. Employed borrowers pay the lowest at 16.41%.

**Credit Score by Region and Gender**  
Credit scores range narrowly between 564 and 594 across all regions and genders.

**Debt to Income Ratio by Age Group**  
Adults aged 26-40 carry the highest debt-to-income ratio at 3.09, reflecting peak borrowing years.

**Savings by Income Bracket**  
High income individuals save an average of $391,597 versus $97,217 for low income — nearly four times more. The savings-to-income ratio stays consistent at around 5.0 across all groups.

**Top 5 Job Titles by Average Income**  
Managers earn the most at $4,082 per month, followed by Doctors at $4,064. Engineers rank fifth at $4,018.

---

## Key Findings

- Education level has minimal effect on income in this dataset
- Employment stability directly affects loan interest rates
- High earners save more in absolute terms but not proportionally
- Credit scores show no significant variation across regions or genders
- Middle-aged adults carry the most debt relative to their income

---

## About me 

Habib Hajjioui  
Economics and Finance Graduate — Cadi Ayyad University, 2025  
Skills: Excel, SQL, Power BI, Python  
Languages: Arabic, French, English, German (B2)
