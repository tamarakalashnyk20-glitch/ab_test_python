# ab_test_python
# Python A/B Test Analysis
# Project Overview

This project focuses on analyzing A/B testing results using Python statistical analysis and Tableau dashboard visualization.

Data for the analysis was extracted from Google BigQuery using SQL queries that combined session, event, order, and account data across different test groups, devices, countries, continents, and traffic channels.

The analysis was performed in Google Colab using Python to calculate statistical significance for key conversion metrics and evaluate experiment performance across different user segments.

The Tableau dashboard visualizes:

- A/B test group distribution,
- session trends over time,
- conversion rate comparison,
- statistical significance metrics,
- device and traffic channel performance.

Technologies Used
- SQL
- Google BigQuery
- Python
- Pandas
- NumPy
- SciPy
- Statsmodels
- Google Colab
- Tableau Public

The project evaluates statistical significance for:

- add_payment_info / session
- add_shipping_info / session
- begin_checkout / session
- new_accounts / session

The analysis includes:

- hypothesis testing,
- p-value calculation,
- conversion rate comparison,
- significance evaluation.

Skills Demonstrated

- A/B testing analysis
- Statistical analysis in Python
- Hypothesis testing
- Conversion rate analysis
- KPI reporting
- Tableau dashboard development
- Data visualization and storytelling

# Dashboard Preview
![Dashboard Preview](Dashboard_ab_test.pdf)
