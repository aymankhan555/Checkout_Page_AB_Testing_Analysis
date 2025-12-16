# A/B Testing: Checkout Page Conversion Analysis

## Project Overview
This project analyzes the impact of a redesigned checkout page on user conversion using **A/B testing**.  
The goal is to determine whether the new checkout page improves conversion rates compared to the existing page and to provide **data-driven recommendations** for business decision-making.

## Dataset
- Total records: 294,481 users  
- Source: E-commerce A/B testing dataset  
- Two variants:
  - Control: Original checkout page
  - Treatment: New checkout page
 
## Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- SciPy, Statsmodels

## Key Metrics
- Conversion Rate
- Conversion Count
- Statistical Significance (Z-test)

## Methodology
1. Data cleaning and validation of A/B group assignments  
2. Removal of duplicate user records  
3. Exploratory Data Analysis (EDA)  
4. Conversion rate comparison between variants  
5. Hypothesis testing using a Z-test for proportions  
6. Visualization of conversion counts and rates  

## Hypothesis Testing
- Null Hypothesis (H₀): Conversion rate of control = conversion rate of treatment  
- Alternative Hypothesis (H₁): Conversion rates are different  

A Z-test was used to compare the conversion rates between the two variants.

## Results
- Control conversion rate: 12.04%  
- Treatment conversion rate: 11.88%  
- Z-test statistic: -1.31  
- p-value: 0.1897  

The p-value is greater than 0.05, indicating that the difference in conversion rates is **not statistically significant**.

## Business Insight
- The redesigned checkout page did **not** outperform the existing page.
- The observed difference in conversions is likely due to random variation.
- Recommendation: Do not roll out the new checkout page without further design improvements or additional testing.

## Outcome
This project demonstrates practical experience with:
- Real-world A/B testing
- Hypothesis testing
- Business-oriented data analysis
- Clear data storytelling for stakeholders
