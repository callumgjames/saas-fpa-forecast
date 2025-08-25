# SaaS Revenue & Expense Forecasting (Starter Kit)

This repository contains a fully reproducible, bite-size FP&A project:
- Synthetic dataset of a SaaS business (monthly granularity)
- A step-by-step Jupyter notebook to explore, model, and forecast
- A report template to package insights for executives
- Instructions to build a Power BI dashboard

## Files
- `data/saas_financials.csv` — synthetic monthly metrics (2022-01 to 2025-07)
- `notebook/saas_forecast.ipynb` — run this notebook from start to finish
- `report/report_template.md` — 2–3 page executive-ready template
- `output/` — forecasted CSVs and PNG charts will be written here after you run the notebook
- `images/` — placeholder for any images you want to include in the report

## How to run
1. Install Python 3.10+ and VS Code or Jupyter Lab.
2. Install packages:
   ```bash
   pip install pandas numpy matplotlib scikit-learn statsmodels
   ```
3. Launch Jupyter and open `notebook/saas_forecast.ipynb`.
4. Run cells top-to-bottom to generate forecasts and exports in `output/`.

## Power BI (Optional but Recommended)
1. Open Power BI Desktop.
2. Get Data → Text/CSV → select `data/saas_financials.csv` and `output/forecast_results.csv` (after you run the notebook).
3. Use the step-by-step guide in the notebook (last section) to build visuals.
