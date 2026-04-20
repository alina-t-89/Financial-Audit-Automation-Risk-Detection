# Financial Audit Automation & Risk Detection

This project demonstrates an end-to-end data analytics workflow for financial auditing. It combines the power of Python for data processing and risk scoring with Tableau for executive-level visualization.

## Project Overview
The goal is to identify high-risk financial transactions within a large dataset. By automating the risk-scoring logic, we reduce manual audit time and focus on critical anomalies.

## Tech Stack
* **Python (Pandas):** Data cleaning and feature engineering.
* **Plotly:** Initial interactive data exploration.
* **Tableau:** Final business intelligence dashboard for stakeholders.
* **Jupyter Notebook:** Development environment.

## Key Features
1.  **Automated Risk Scoring:** Transactions are evaluated based on volume and departmental benchmarks.
2.  **Interactive Treemap:** Hierarchical view of expenditures across departments.
3.  **Real-time Filtering:** Ability to isolate high-probability risks (0.7-1.0 range) instantly.

## How to Use
1. Run the `Financial_Audit_Risk_Analysis.ipynb` to process raw data and generate the CSV export.
2. Import the resulting `.csv` into Tableau to view the interactive dashboard.
