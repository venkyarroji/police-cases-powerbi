# 🚓 2016 Criminal Cases Against Police Personnel – Power BI Dashboard

This Power BI project analyzes criminal cases registered against police personnel in India for the year 2016. The dashboard provides insightful visualizations on case statistics across different states and union territories, with a focus on arrests, chargesheets, convictions, and trial outcomes.

---

## 📁 Files Included

- `criminal case.pbix` – Power BI dashboard file
- `Cleaned_Police_Cases_2016.csv` – Cleaned dataset used in Power BI

---

## 📊 Dashboard Highlights

### Visuals Included:
| Visualization                            | Description |
|------------------------------------------|-------------|
| 🔹 Column Chart – Total Cases by State    | Highlights states with the highest number of criminal cases. |
| 🔹 Clustered Bar Chart – Arrests vs Convictions | Compares the number of police arrested and convicted across states. |
| 🔹 Scatter Plot – Chargesheeted vs Convicted | Reveals case progression efficiency. |
| 🔹 Pie Chart – Case Outcomes              | Proportion of police convicted vs acquitted. |
| 🔹 Bar Chart – Trials Completed by State  | Highlights judicial follow-through in each state. |
| 🔹 Bubble Chart – Withdrawn vs Pursued Cases | Visualizes states where more cases were dropped. |
| 🔹 KPI Cards – Key Metrics                | Displays total cases, conviction rate, charge conviction rate. |

---

## 📈 Insights Derived

- Significant disparity between arrests and convictions in some states.
- Some states have high withdrawal rates, suggesting potential procedural gaps.
- Trials completed are low relative to cases registered.
- Conviction rates vary widely, indicating uneven enforcement or legal resolution.

---

## 📌 Dataset Info

- **Source:** Government of India (2016 Crime Records)
- **Columns:**
  - `State/UT`, `Total Criminal Cases`, `Police Arrested`, `Chargesheeted`, `Trials Completed`, `Convicted`, `Acquitted`, and others.

---

## 🧠 Technologies Used

- [Power BI](https://powerbi.microsoft.com/)
- Data Transformation via Power Query
- DAX Measures for KPIs:
  - Conviction Rate
  - Charge-to-Conviction Efficiency

---

## 🧾 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/police-cases-powerbi.git
