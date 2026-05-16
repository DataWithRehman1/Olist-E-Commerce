# Ecommerce Churn Analysis

What this project is
- A Jupyter Notebook analysis using the Olist public e-commerce datasets to identify customer churn (defined here as no purchase in 90+ days) and build predictive models.

How to run
1. Create and activate a Python environment (recommended Python 3.10+)

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

2. Open the notebook and run all cells top-to-bottom in Jupyter or VS Code:

```powershell
jupyter lab
# or
code .
# then open ecommerce_churn_analysis.ipynb and Run All
```

Key findings
- High churn: ~90% of customers are inactive under the 90-day rule (many customers have only one recorded purchase).
- Frequency is the strongest predictor: customers who order more often are much less likely to be labeled as churned.
- Business action: prioritize re-engagement campaigns and loyalty incentives for low-frequency, mid-value customers.

Notes
- The notebook was cleaned for portfolio presentation: added section headers, removed test cells, fixed a RandomForest training cell, and added feature-engineering and feature-importance steps.
- If you want me to commit and push these changes, tell me and I'll attempt to run the git commands (may require your credentials).