# Human Resource Analysis 📊

## Overview
This workbook provides a detailed analysis of employee data to explore **attrition patterns**, **income trends**, **career span statistics**, and **department-wise satisfaction levels**.  
It combines raw HR analytics data with aggregated reports and visual summaries to help identify factors influencing employee retention and performance.

---

## 📂 File Structure

- The dataset folder contains dataset used for analysis.

- The workbook contains **5 sheets**:

### 1. **HR_Analytics**
- **Purpose:** Raw dataset of employee attributes.
- **Key Columns:**
  - `EmpID`, `Age`, `Attrition`, `BusinessTravel`, `Department`
  - `MonthlyIncome`, `MonthlyRate`, `PercentSalaryHike`
  - `PerformanceRating`, `StockOptionLevel`, `TotalWorkingYears`, `YearsAtCompany`
- **Use Case:** Base data for all other analyses in the workbook.

---

### 2. **Analysis_Steps**
- **Purpose:** Reserved for documenting the step-by-step process used in the analysis (currently empty).
- **Use Case:** Can be used to track the methodology for reproducibility.

---

### 3. **Department_CareerSpan_Analysis**
- **Purpose:** Aggregates **average years spent in the company** by department and job role.
- **Insights Example:**
  - Human Resources employees have an average tenure of ~7.2 years.
  - Managers tend to have significantly longer tenures (~16.3 years).

---

### 4. **Income_Hike_Analysis**
- **Purpose:** Shows **average monthly income**, **monthly rate**, and **average salary hike** by department and education field.
- **Insights Example:**
  - Sales roles have the highest average monthly income (~₹7063).
  - Education field influences salary hike percentages.

---

### 5. **Final_Visual**
- **Purpose:** Consolidated KPI table showing:
  - Average Monthly Income
  - Average Monthly Rate
  - Average Job Satisfaction
  - Average Years Spent in Company
- **Insights Example:**
  - Life Sciences employees have higher-than-average job satisfaction (~2.88/4).
  - Medical field employees stay longer (~8.77 years) compared to other fields.

---

## 📊 Key Visualizations

### Steps Performed
![Steps Perfoemd](steps.png)

### Average Monthly Income and Rate by Department
![Average Monthly Income and Rate](income_hike.png)

### Average Career Span by Department
![Average Years Spend in Company](career_span.png)

### Final Visualization
![Final Visual Analysis](final_visual.png)

---

## 🔍 Key Insights & Use Cases
- Identify **departments with high attrition** and potential retention strategies.
- Compare **income trends** across departments and roles.
- Examine **job satisfaction patterns** for workforce engagement improvement.
- Plan **career development programs** based on tenure data.

---

## 📊 How to Use
1. **Data Exploration:**
   - Use `HR_Analytics` for employee-level deep dives.
2. **Trend Analysis:**
   - Check `Income_Hike_Analysis` for salary patterns.
3. **Retention Planning:**
   - Use `Department_CareerSpan_Analysis` to understand tenure distribution.
4. **Quick KPI Review:**
   - Refer to `Final_Visual` for at-a-glance HR metrics.

---

## 🛠 Recommended Next Steps
- Populate `Analysis_Steps` with the exact processing and pivot creation methodology.
- Add **more visual charts** for attrition vs. age, income vs. experience, and satisfaction vs. department.
- Perform **predictive modeling** to forecast attrition risk.
