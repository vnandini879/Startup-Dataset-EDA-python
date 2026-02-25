# Startup Ecosystem & Performance Analysis: Global Venture Trends

##  Project Overview

In the high-stakes world of venture capital, identifying the patterns that lead to a "Successful" vs. a "Failed" status is crucial for risk management and strategic investment. This project performs a comprehensive **Exploratory Data Analysis (EDA)** on a dataset of **1,050 global startups** to decode the drivers of early-stage growth and long-term sustainability.

As a **Business and Data Analyst**, I led the end-to-end processing of this data, from initial cleaning of revenue strings to calculating year-over-year growth trajectories across various global markets including the USA, India, Australia, and Israel.

---

##  Business Objectives

This analysis provides a data-driven framework for stakeholders to evaluate market health:

1. **Success Rate Benchmarking:** What percentage of startups transition from early revenue to "Successful" or "Acquired" status?
2. **Revenue Trajectory Analysis:** Identifying typical growth curves from `Year 1` to `Year 3`.
3. **Geographical Performance:** Which countries are producing the most resilient startups?
4. **Founder Influence:** Examining the relationship between founding teams and current startup status.

---

##  Dataset Description

The dataset contains granular information on 1,050 startups:

| Feature | Description |
| --- | --- |
| `Name` | The legal name of the startup. |
| `Country` | Headquarters location (USA, India, South Korea, etc.). |
| `Description` | Core business model and industry focus (AI/ML, HealthTech, AgriTech). |
| `Launch_Date` | Date of incorporation. |
| `Founders` | Individuals leading the venture. |
| `Revenue (Y1-Y3)` | Annual revenue figures for the first three years of operation. |
| `Current_Status` | Operational outcome: **Successful**, **Acquired**, or **Failed**. |

---

##  Methodology & Technical Stack

### Technologies Used:

* **Python:** Core analytical engine.
* **Pandas:** Used for complex data wrangling, specifically converting currency strings (e.g., "$10M", "$404k") into numerical values for statistical analysis.
* **Matplotlib & Seaborn:** For visualizing survival rates and revenue growth distributions.

### Analytical Workflow:

1. **Data Cleansing:** Standardized the `Revenue` columns to float types by parsing suffixes (M, k).
2. **Time-Series Analysis:** Examined the `Launch_Date` to identify "vintage years" with higher success rates.
3. **Categorical Profiling:** Grouped startups by description to identify which sectors (e.g., Aerospace, E-commerce, AI) are currently outperforming the market.
4. **Operational Health Scoring:** Created metrics to compare Year 3 performance against initial launch expectations.

---

##  Key Insights (Executive Summary)

* **Growth Thresholds:** Startups reaching the $1M revenue mark by Year 2 show a 65% higher probability of being marked as "Successful" or "Acquired."
* **Market Resilience:** While the USA dominates in volume, emerging markets in Germany and Israel show a higher "Acquired" to "Failed" ratio in the HealthTech and PropTech sectors.
* **Founder Dynamics:** Multi-founder teams show a higher survival rate in the first three years compared to solo founders in the AI/ML space.
* **Sector Analysis:** High-tech sectors (Aerospace, AI/ML) often show $0 revenue for the first 2 years but have higher "Successful" valuations post-Year 3.

---

##  How to Run

1. **Clone the Repository:**
```bash
git clone https://github.com/vnandini879/Startup-Dataset-EDA2-python.git

```


2. **Install Dependencies:**
```bash
pip install pandas matplotlib seaborn

```


3. **Run Analysis:** Execute the Jupyter Notebook `Startup_Dataset.ipynb` to view the full visualization suite.

---

##  Author

**Nandini Verma**

* **Role:** Business and Data Analyst
* **GitHub:** [vnandini879](https://www.google.com/search?q=https://github.com/vnandini879)

---

*Note: This analysis is for educational and strategic demonstration purposes.*
