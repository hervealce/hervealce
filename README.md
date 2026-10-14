# Hervé Alcé

Data analyst with an **M.S. in Data Analytics** and a **B.A. in Chemistry**. Before analytics I worked in chemistry, manufacturing, production management and quality assurance. That's where I learned how organizations actually use data: root-cause investigations, CAPA, nonconformances, process monitoring. I build analyses that end in a decision, not just a chart.

📫 info@hervealce.com · 🌐 [hervealce.com/data](https://www.hervealce.com/data)

## Projects

Every project is built on public data and comes in three versions: SQL (DuckDB), Python and R. All results are reproducible.

| Project | What it shows | Result |
|---|---|---|
| [Flight Delay Prediction Pipeline](https://github.com/hervealce/flight-delay-mlops) | Time-split ML, MLflow, FastAPI, pytest, Docker | AUC 0.688 on a holdout week; the riskiest 10% of flights were late 52% of the time (base rate 29%) |
| [Hospital Readmission Risk](https://github.com/hervealce/hospital-readmission) | Leakage-aware classification, patient segmentation | 69,987 patients; honest AUC 0.61; 4+ prior stays → 29% readmission vs 8% |
| [What Drives Home Prices?](https://github.com/hervealce/home-price-drivers) | OLS vs Ridge vs PCA regression, logistic classifier | R² 0.90, test RMSE $21.8k; luxury-tier AUC 0.99 |
| [Retail Market Basket Analysis](https://github.com/hervealce/retail-market-basket) | Association rules on 1M+ transactions | 246 rules; strongest pairing lift 30 |
| [Medical Cost Drivers](https://github.com/hervealce/medical-cost-drivers) | Hypothesis testing, interaction regression | Smokers $32k vs $8.4k; interpretable model explains 84% of variance |
| [Sales Warehouse & Revenue Forecast](https://github.com/hervealce/sales-warehouse-forecast) | Star schema design, time-series forecasting | 1.06M-row fact table; seasonal baseline beat SARIMA (22.6% vs 29.4% MAPE) |

## Skills (demonstrated in these repos)

- **Languages:** R, Python, SQL (DuckDB)
- **Data work:** pandas, dplyr, window functions, star-schema design, data cleaning
- **Statistics:** t-tests, Mann-Whitney, regression diagnostics (VIF), logistic regression, stationarity tests
- **Machine learning:** scikit-learn pipelines, gradient boosting, random forests, PCA, k-means, association rules, SARIMA/ARIMA
- **Deployment:** MLflow, FastAPI, pytest, Dockerfile
- **Visualization:** matplotlib, seaborn
- **Domain:** quality assurance, manufacturing operations, ISO 9001:2015 auditing
