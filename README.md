# Python Portfolio

A data analysis project built with pandas, NumPy, Matplotlib, and Seaborn,
covering data cleaning, exploratory analysis, and business insight
generation on a multi-year global sales dataset.

## Project: Global Sales Data Analysis

**[Open the notebook](Global_Sales_Data_Analysis.ipynb)**

**Business context:** The dataset covers multi-year sales from a company
operating in both online and offline retail channels across the global
market, split across three related tables — order-level sales events,
product categories, and country/region reference data.

**What the analysis covers:**
- Data cleaning and validation: missing values, duplicates (including
  Cyrillic/Latin lookalike character normalization), anomaly detection,
  data type consistency
- Merging three source tables into a single analytical dataset
- Core business metrics: revenue, cost, profit, margin, order volume,
  market coverage
- Sales performance breakdown by product category, country, region, and
  sales channel
- Shipping time analysis and its relationship with profitability
- Sales trends over time and day-of-week seasonality
- Order priority vs. profit and shipping speed
- Profit margin (%) by category, beyond absolute profit
- Correlation analysis across key numeric metrics

**Tools & libraries:** Python, pandas, NumPy, Matplotlib, Seaborn

**Key findings:**
- The company is financially healthy: 1,328 orders, $1.70B in revenue, a
  ~30% margin (2010–2017)
- Sales channels are well balanced (Offline 50.1% vs. Online 49.9% of
  revenue) — no critical dependency on either
- Concentration risk: Europe dominates revenue over Asia by an order of
  magnitude, and shows a declining trend in the last three years of the
  period
- Shipping speed (~25 days on average) is fully decoupled from
  profitability and order priority — correlation ≤ 0.07 across all
  financial metrics
- Popularity ≠ profitability: Office Supplies leads in sales volume, but
  Clothes has by far the highest profit margin (67.2%), suggesting an
  under-leveraged, high-efficiency category worth expanding

