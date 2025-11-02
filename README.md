# Data Analysis Portfolio — Main Features

This repo contains three self-contained notebooks (each in its own folder). Below are the **main features** covered in each analysis.

## 1) Titanic — Exploratory Data Analysis [🔗](/exploratory-data-analysis-on-the-titanic-dataset)

* Cleaned dataset and handled missing values for key columns.
* Explored **survival relationships** by:

  * Passenger Class (Pclass)
  * Gender (Sex)
  * Age (binned/continuous)
  * Family size
* Built clear visuals (bar charts, histograms) to compare survival rates across groups.
* Summarized takeaways as simple, decision-oriented insights.

## 2) House Prices — Cleaning & Analysis [🔗](/house-prices-cleaning-and-analysis)

* Performed **systematic missing-value treatment** (numeric & categorical).
* Checked distributions and noted near-normal variables where relevant.
* **Feature engineering:** replaced `YearBuilt` with an easier-to-read **Age** feature.
* Computed correlations with **SalePrice** and visualized them (heatmap + interactive view).
* Highlighted the strongest numeric drivers of price with concise commentary.

## 3) Uber Trip Data — Exploratory Data Analysis[🔗](/exploratory-data-analysis-on-uber-trip-data)

* Cleaned raw trip records and standardized datatypes (timestamps, numerics).
* Extracted time features (hour/day/month) to analyze **demand patterns**.
* Identified **peak hours & weekdays** and contrasted with off-peak periods.
* Visualized trends (time-series & heatmaps) and summarized location/activity hotspots.
* Provided a compact, data-driven overview of usage behavior.


## 4) Employee Attrition Analysis — Data Cleaning, EDA & Excel Dashboard [🔗](/exploratory-data-analysis-HR-dataset)

* Performed **comprehensive data cleaning**, removing redundant and calculated fields to simplify HR data.
* Converted key categorical fields (e.g., `Attrition`, `Age`, `JobRole`) into consistent formats for analysis.
* Explored **attrition patterns** across:

  * Gender, Age Group, Department, and Education Field
  * Business Travel Frequency, Job Satisfaction, Job Level, and Total Working Years
* Built **correlation analysis** to identify strongest retention and attrition drivers.
* Created an **interactive Excel dashboard** summarizing:

  * Key KPIs (total employees, attrition rate, average age/income)
  * Demographic insights (gender, age distribution)
  * Attrition by role, department, and work conditions
  * Correlation between numerical features and attrition
* Concluded that **younger, early-career, and frequently traveling employees** are most likely to leave, while **experience, tenure, and fair pay** improve retention.

---

### Tools & Techniques (across projects)

* **Python (Pandas, NumPy)**
* **Visualization:** Matplotlib / Plotly
* **Data cleaning & preprocessing**
* **Feature engineering & correlation analysis**
* **Insight-focused summaries**
* **Excel (PivotTables, Dashboard Design)**
