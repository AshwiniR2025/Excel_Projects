# 🏭 Excel Production Analysis Dashboard

This Excel project presents a comprehensive production dataset analysis using built-in formulas, data cleaning techniques, and advanced visualizations. The dashboard provides clear insights into production costs, workforce performance, and manufacturing trends.

## 📁 File Overview
- **Excel File Name:** `Production_Analysis_Dashboard.xlsx`
- **Sheets Included:** 
  - `Data`
  - `Dashboard`
  - `Lookups`
  - `Charts`

---

## 🧹 Data Preparation Steps

1. **Null Value Handling:**
   - Replaced missing values in the `Gender` column with `"Unknown"`.

2. **Age Correction:**
   - Used `VLOOKUP` to resolve data quality issues by assigning a consistent age for each manager.

3. **Age Group Creation:**
   - Created a new `Age Group` column using the formula:
     ```
     =IF(I2<=35,"A1",IF(I2>35&I2<=45,"A2","A3"))
     ```

4. **Production Cost Per Unit:**
   - Added a column to calculate cost per unit:
     ```
     = Total Cost / Unit Price
     ```

---

## 📊 Business Questions Answered

1. **🧾 Total Cost by Product Type**
   - **Chart Type:** 3D Column Chart  
   - **Insight:** Visualizes which product categories contribute the most to total production cost.

2. **👷‍♂️ Production Task Count per Manager**
   - **Chart Type:** Column Chart  
   - **Insight:** Helps identify workload distribution and team efficiency.

3. **📆 Units Produced by Year/Month**
   - **Chart Type:** Line Chart or Pivot Chart with slicers  
   - **Insight:** Tracks production trends over time to understand seasonal or monthly fluctuations.

4. **📈 Average Production Cost per Production Type**
   - **Chart Type:** Bar Chart  
   - **Insight:** Compares cost efficiency across different types of production.

---

## 🔧 Tools & Techniques Used

- **Excel Functions:** `VLOOKUP`, `IF`, `ISBLANK`, `AVERAGEIF`, `SUMIFS`
- **Data Cleaning:** Handling nulls, correcting inconsistent values
- **Calculated Columns:** Age Group, Cost Per Unit
- **Charts & Visuals:** 3D Column, Bar, Line, Pivot Charts
- **Formatting:** Conditional formatting for clarity, filters for interactivity

---

## 💼 Use Cases

- Production performance monitoring
- Cost optimization analysis
- Workforce distribution insights
- Decision support for manufacturing managers

---

## 🖼 Preview

*(Include a screenshot of the dashboard here if uploading to GitHub)*

---

## ✅ Future Improvements

- Add dynamic slicers for interactivity
- Incorporate benchmarking for cost efficiency
- Connect with real-time data via Power Query or Power BI

---

> Created by: **AshwiniR2025**  
> Project Type: **Excel Production Dashboard**  
> Tags: `#Excel`, `#DataCleaning`, `#Dashboard`, `#Manufacturing`, `#ProductionAnalytics`
