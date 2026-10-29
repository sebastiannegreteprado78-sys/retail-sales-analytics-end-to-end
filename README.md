# retail-sales-analytics-end-to-end
Análisis end-to-end de ventas retail y devoluciones usando Python, SQL, Excel y Looker Studio
# 🛍️ E-Commerce Retail: Sales & Returns Analysis

An end-to-end data analysis project exploring 20,000+ fashion retail transactions to understand real net revenue by acquisition channel and identify root causes behind product returns.

🔗 **Interactive BI Dashboard:** [View on Looker Studio]([PEGA_AQUI_TU_ENLACE_DE_LOOKER_STUDIO](https://datastudio.google.com/reporting/0814cd06-ff0b-469c-896b-e0f768b67148))



# Business Problem & Context
The store generated **€701.78K** in gross sales, but lost **€208.39K** due to product returns (~29.7% return rate), leaving **€493.39K** in actual net revenue. 

The goal of this analysis was to answer two key business questions:
1. Which marketing channels are actually driving profitable sales after accounting for refunds?
2. Which product categories have the highest return rates and why?

---

Key Findings
* **Gross sales were misleading:** Almost 30% of total revenue went back to customers via returns, meaning high-volume channels were not necessarily the most profitable.
* **Instagram was the top performer:** Delivered **€173.45K** in net revenue with a 26.8% return rate, outperforming Google and Email in retained earnings.
* **Fit issues in Dresses & Footwear:** Both categories had return rates above 34%. Customer return logs showed that poor sizing guidance (*fit issues*) was the primary reason, pointing to an immediate operational fix on product detail pages.



## 🛠️ Tech Stack & Workflow

* **Python (Pandas):** Cleaned raw data, fixed inconsistent text values (`vestidos`, `CALZADO`, `pantalon`), handled currency formats, calculated discounted order subtotals, and exported clean datasets.
* **SQL:** Queried gross sales vs. returned totals per channel using conditional aggregations (`CASE WHEN`), ensuring data consistency against accounting totals.
* **Microsoft Excel:** Built channel summaries and detailed transactional audit sheets with standard financial formatting.
* **Google Looker Studio:** Designed an executive single-screen dashboard featuring key metric cards, gross vs. net revenue comparisons, and interactive channel filtering.

---

## 📂 Repository Structure
* `*.ipynb` — Complete Python analysis and data cleaning script.
* `*.xlsx` / `*.csv` — Cleaned and aggregated datasets ready for reporting.
* `dashboard_preview.png` — High-resolution screenshot of the executive dashboard.
* `README.md` — Project documentation and business summary.
