# Productivity & Behavioural Analysis Project
A data analysis project focused on identifying real drivers of productivity using behavioural and lifestyle data.

## Overview

This project analyses how behavioural, lifestyle, and demographic factors impact **productivity, stress, burnout, and job satisfaction**.

The goal was to go beyond basic analysis and identify **real drivers of productivity**, while also validating how data preprocessing choices affect insights.

---

## Dataset

* Source: Kaggle (Social Media vs Productivity dataset)
* Records: 30,000 rows
* Features include:

  * Social media usage
  * Work hours
  * Sleep patterns
  * Stress levels
  * Job satisfaction
  * Productivity scores

---

## Tools & Technologies

* **Python** (Pandas, NumPy, Matplotlib)
* **Power BI** (Dashboard & visualization)
* **Jupyter Notebook**
* **GitHub**

---

## Data Cleaning & Processing

* Handled missing values using:

  * Mean imputation
  * Median imputation
  * Dropping null records (for comparison)
* Created new feature columns:

  * `burnout_risk`
  * `high_stress`
  * `low_sleep`
  * `age_group`
* Compared how different cleaning techniques impact correlation results

---

## Analysis Performed

* Descriptive analysis
* Correlation analysis
* Behavioural pattern analysis
* Group-based analysis:
  * Gender
  * Age group
  * Job type
* Burnout and productivity factor analysis

---

## Key Insights

* Job satisfaction shows the **strongest correlation with productivity**
* Burnout is primarily driven by:

  * High stress
  * Long working hours
  * Low sleep
* Social media usage has **less direct impact** than expected
* Demographic factors (age, gender) show **minimal variation**
* Data cleaning method significantly impacts analytical results

---

## Power BI Dashboard

The interactive dashboard includes:

* KPI cards (Productivity, Stress, Job Satisfaction, Work Hours)
* Job-wise comparison charts
* Burnout factor analysis
* Focus apps vs productivity comparison
* Slicers for:

  * Gender
  * Job Type
  * Age Group

---

## Key Learning

A critical insight from this project:

> The choice of missing value handling method (mean vs dropping data) can significantly alter correlations and conclusions.

---

## Project Structure

```
data/
  ├── cleaned_productivity_data.csv
  ├── social_media_vs_productivity.csv

notebook/
  ├── Productivity_Analysis.ipynb

dashboard/
  ├── Productivity_Dashboard.pbix
```

---

## Conclusion

Productivity is influenced more by **job satisfaction and workplace conditions** than by direct behavioural factors like screen time.

This project highlights the importance of:

* Thoughtful data preprocessing
* Validating assumptions
* Combining analysis with visualisation for better decision-making

---

## 👤 Author

Deepika Chauthani
