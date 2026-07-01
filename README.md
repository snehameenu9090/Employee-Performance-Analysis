# Employee-Performance-Analysis

## 📌 Project Overview
This project focuses on building an end-to-end HR Analytics pipeline using core Python libraries. The objective is to evaluate employee performance data, discover core drivers of workforce productivity, identify top talents, and deliver data-driven strategic recommendations to the Human Resources department.



## 🛠️ Tools & Technologies Used
As aligned with the 2026 industry curriculum guidelines, the following core technologies were used:
- **Programming Language:** Python 3.12+
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Environment:** VS Code / Jupyter Server Configuration

## 📋 Curriculum Deliverables Achieved

### 1. Data Loading & Exploration
- Designed a synthetic HR dataset consisting of fields: `Employee_ID`, `Name`, `Department`, `Performance_Score`, `Tenure_Years`, `Salary`, and test missing fields.
- Audited data shapes, verified structural data types, and isolated initial statistical characteristics.

### 2. Data Cleaning & Preprocessing
- Successfully handled missing data by applying median imputation methods.
- Dropped duplicate records to safeguard data integrity.
- Converted structural identifiers (`Employee_ID`) into proper string objects to prevent arithmetic errors.

### 3. Core Data Analysis & Business Logic
- Grouped data by `Department` to calculate exact average performance benchmarks.
- Extracted the Top 10 High-Performing workforce tier using advanced sorting filters.
- Computed mathematical correlations between:
  - **Tenure vs. Performance**
  - **Salary vs. Performance**

### 4. Advanced Visualization Pipeline (10+ Charts Workflow)
Generated comprehensive analytical plots to evaluate the workplace architecture:
1. **Performance Distribution:** Histogram with Kernel Density Estimate (KDE).
2. **Department Performance:** Comparative Bar Charts.
3. **Compensation Mapping:** Multi-variable Scatter Plots.
4. **Experience Matrix:** Linear Trend Line Charts.
5. **Outlier Detection:** Box Plots for Salary spreads.
6. **Salary Structure:** Distribution Violin Plots by department.
7. **Expenditure Share:** Departmental Salary Pie Charts.
8. **Workforce Headcount:** Categorical Count Plots.
9. **Metric Relationships:** Correlation Matrix Heatmap.
10. **Tenure Density:** Experience KDE plots.

---

## 📈 Strategic HR Recommendations & Insights
Based on the programmatic data output, the following actions have been recommended for corporate management:
1. **Departmental Upliftment:** The **IT Department** significantly outperforms others with an average score of **85.25**, whereas the **Sales Department** sits at a low benchmark of **67.75**. HR must deploy a targeted upskilling program for the Sales group.
2. **Retention Strategy:** A strong positive linear correlation exists between an employee's tenure and their performance score. Retaining senior professionals through loyalty bonuses will directly improve overall organizational output.
