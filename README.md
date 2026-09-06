# Airline Passenger Satisfaction — EDA & Statistical Analysis

Exploratory data analysis and hypothesis testing on airline passenger survey data
to identify which service factors most strongly influence satisfaction.

## Business Question
Which service factors (wifi, seat comfort, delays, class) most significantly affect
whether a passenger reports satisfaction — and are the differences statistically
significant or just noise?

## Dataset
[Airline Passenger Satisfaction (Kaggle)](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction)
— ~130,000 survey responses with satisfaction ratings across 20+ service factors.

## Tools
Python (Pandas, SciPy), Seaborn/Matplotlib, Google Colab

## Workflow
1. **Cleaning** — removed identifier columns, handled missing arrival delay values,
   standardized column names
2. **EDA** — satisfaction distribution by class, correlation heatmap across service factors
3. **Statistical Testing**
   - Independent t-test: departure delay vs. satisfaction
   - Chi-square test: travel class vs. satisfaction
4. **Interpretation** — translated p-values into plain-language business takeaways

## Key Findings
*(fill in with your actual results)*
- e.g. Business class passengers report satisfaction at a significantly higher rate
  (chi-square p < 0.05)
- Departure delay shows a statistically significant but modest effect on satisfaction
- [Service factor] correlates most strongly with overall satisfaction

## Repo Structure
