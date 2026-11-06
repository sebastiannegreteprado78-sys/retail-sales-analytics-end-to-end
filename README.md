# Retail Sales & Returns Analysis

Retail sales and returns analysis using Python, SQL, Excel, and Looker Studio.

## Project

This project evaluates the actual performance of a retail business by analyzing more than 20,000 transactions to answer two key questions:

1. Which marketing channels generate actual net revenue after returns are deducted?
2. Which categories have the highest return rates, and what explains this behavior?

The project combines financial analysis, data cleaning, and executive reporting to turn operational data into business decisions.

---

## Executive Summary

The business recorded **€701.78K** in gross sales, but had **€208.39K** in returns, equivalent to an approximate return rate of **29.7%**.

After deducting returns, actual net revenue was **€493.39K**, showing that gross volume does not always reflect a channel's actual profitability.

### Key Findings

- **Instagram was the top-performing channel by net revenue**: **€173.45K** in net revenue with a return rate of **26.8%**.
- **Google and Email lagged behind** in net performance, despite their high gross sales.
- **Dresses and footwear were the most problematic categories**, with returns related to fit and sizing.
- **The main issue was not just sales volume, but also the quality of the shopping experience and product information**.

---

## Technology Stack

- **Python + Pandas**: data cleaning, category normalization, currency formatting, and metric calculations.
- **SQL**: validation and aggregation of sales, returns, and financial KPIs.
- **Excel**: creation of operational summaries and auditing of results.
- **Looker Studio**: executive dashboard and visualization of KPIs by channel.

---

## Workflow

1. Load and consolidate transaction tables.
2. Clean categories, amounts, and dates.
3. Combine orders and returns.
4. Calculate gross sales, return amount, return rate, and actual net revenue.
5. Export cleaned data for analysis and the dashboard.

---

## Business Impact

This analysis supports data-driven decisions:

- **Reallocate channel investment** based on actual net performance.
- **Reduce returns** by focusing efforts on higher-risk categories.
- **Improve the shopping experience** with clearer sizing and fit information.
- **Prioritize campaigns** with higher profitability and lower financial risk.

---

## Key Metrics

- Gross sales by channel
- Return amount by channel
- Return rate by channel
- Actual net revenue
- Performance by product category
- Identification of products with the greatest fit issues

---

## Repository

- `limpieza_con_python_y_sql.ipynb` — main notebook for data cleaning, analysis, and KPIs.
- `reporte_ventas_limpio(Resumen Canales) (1).csv` — final channel summary dataset.
- `dashboard_preview.png` — dashboard preview.
- `requirements.txt` — project dependencies.
- `README.md` — project documentation.

---

## How to Reproduce

1. Clone the repository.
2. Install the dependencies:

```bash
pip install -r requirements.txt
```

3. Open the `limpieza_con_python_y_sql.ipynb` notebook in Jupyter or VS Code.
4. Run the cells to load, clean, and analyze the data.

---

## Project Status

The project is complete as a solid foundation for business analysis with a commercial and financial focus. The natural next step would be to automate the pipeline and publish the dashboard in a shareable environment.

---

## Next Steps

- Improve the notebook's narrative with more executive-focused sections.
- Add more charts by product category and channel.
- Prepare a final version for a portfolio and professional presentation.
