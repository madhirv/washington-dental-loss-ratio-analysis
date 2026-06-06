# Washington State Dental Loss Ratio Insurance Analytics

This repository contains an insurance analytics project focused on analyzing **Washington State Insurers Dental Loss Ratios** using financial, customer, and performance metrics.

The project evaluates dental premiums, dental payments, dental members, member months, and dental loss ratios to understand insurer performance and identify meaningful business insights.


## Project Overview

Dental Loss Ratio is an important insurance metric that measures the percentage of dental claims paid relative to premiums collected. This project analyzes insurer-level dental loss ratio data from Washington State to evaluate financial performance, customer coverage trends, and predictive factors influencing loss ratios.

The analysis also compares data processing performance using different methods and applies regression, profiling, and machine learning techniques to understand feature importance and improve analytical efficiency.

## Objective

- Analyze Washington State insurer dental loss ratio data.
- Evaluate financial metrics such as dental premiums, dental payments, and loss ratios.
- Study customer metrics such as dental members and dental member months.
- Compare data loading and processing performance.
- Identify important predictors influencing dental loss ratio.
- Apply regression and machine learning techniques for insurance analytics.
- Create dashboard-ready outputs for business interpretation.

## Dataset

- **Dataset:** Washington State Dental Loss Ratios
- **Source:** Data.gov
- **File Format:** CSV
- **Coverage:** Washington State insurers
- **Years Covered:** 2015–2023
- **Domain:** Insurance analytics / healthcare finance

## Dataset Attributes

- Company Name
- NAIC Code
- Domicile State
- Business Type
- Year
- Dental Premiums
- Dental Payments
- Dental Members
- Dental Member Months
- Dental Loss Ratio
- Average Amount of Premiums per Member per Month
- Previous Year Average Amount of Premiums per Member per Month
- Percentage Change in Average Premium per Member per Month from Previous Year

## Tools Used

- Python
- Pandas
- Dask
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab
- PowerPoint
- Data.gov dataset

## Data Cleaning & Preprocessing

- Standardized column names for analysis.
- Converted financial and numeric fields into proper numeric data types.
- Handled missing values in previous-year premium and percentage-change columns.
- Prepared insurer-level data for visualization, regression, and machine learning.
- Generated cleaned outputs for dashboard development.

## Exploratory Data Analysis

The project analyzes:

- Dental loss ratio distribution
- Total dental premiums by year
- Total dental payments by year
- Average dental loss ratio by year
- Top insurers by dental premiums
- Relationship between dental premiums and dental payments
- Correlation between financial and member-related metrics

## Performance Benchmarking

The project compares data loading performance using:

- Pandas `read_csv`
- Dask `read_csv`

The goal is to evaluate how different data processing methods perform when handling insurance datasets and preparing them for analytics workflows.

## Modeling Approach

The project includes:

- Linear Regression for predicting Dental Loss Ratio
- Random Forest Regression for feature importance analysis
- Random Forest Classification for business type prediction
- Runtime profiling to identify performance bottlenecks

## Key Features Analyzed

- Dental Premiums
- Dental Payments
- Dental Members
- Dental Member Months
- Average Premium per Member per Month
- Dental Loss Ratio
- Business Type

## Key Insights

- Dental loss ratio provides insight into how much of collected premiums are paid back as dental claims.
- Dental payments and premiums are important financial indicators for insurer performance.
- Member months and member counts help evaluate customer coverage and scale.
- Data loading and profiling comparisons help identify efficient workflows for insurance analytics.
- Machine learning models can support feature importance analysis and business-type prediction.
- Scalable tools such as Dask can support larger insurance datasets and improve preprocessing efficiency.

## Dashboard Pages

1. **Executive Overview**  
   Summarizes key insurer metrics, premium trends, payments, and dental loss ratio patterns.

2. **Financial Performance Analysis**  
   Compares dental premiums, dental payments, and loss ratios across companies and years.

3. **Customer Coverage Metrics**  
   Analyzes dental members and member months to understand insurer coverage scale.

4. **Modeling & Feature Importance**  
   Presents regression and Random Forest model insights for identifying important predictors.

5. **Performance Benchmarking**  
   Compares data loading and modeling performance across processing methods.

## Recommendations

- Monitor dental loss ratio trends to identify insurers with unusually high or low claim payout patterns.
- Use dental payments, premiums, and member months as core indicators for financial performance analysis.
- Apply machine learning feature importance to identify variables that most strongly influence insurer outcomes.
- Use scalable data tools such as Dask when analyzing larger insurance datasets.
- Build recurring dashboards to support regulatory monitoring and insurer performance review.

## Project Outcome

This project demonstrates an end-to-end insurance analytics workflow using Washington State dental loss ratio data. The analysis combines data cleaning, exploratory visualization, performance benchmarking, regression modeling, Random Forest feature importance, and dashboard-ready outputs to support financial and regulatory decision-making.

## Repository Contents

- `Washington State Insurers Dental Loss Ratios.pptx` - Project presentation
- `Washington_Dental_Loss_Ratio_Analysis.ipynb` - Python analysis notebook
- Dashboard link or dashboard screenshots
- README documentation

## Contributors

- Varshini Guthi
- Vaishnavi Madhiraju
- Midhun Manam
- Rithwik Raj Suram

## References

- Washington State Dental Loss Ratios dataset from Data.gov
- Dask Documentation: https://docs.dask.org/
- Scikit-learn Documentation: https://scikit-learn.org/
- Pandas Documentation: https://pandas.pydata.org/docs/
- Matplotlib Documentation: https://matplotlib.org/stable/
