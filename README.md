# 🏥 Healthcare Performance Dashboard - Power BI

## 🎯 Project Overview
A comprehensive Power BI dashboard analyzing healthcare facility performance over two years, revealing a **$1M revenue increase** and providing actionable insights into patient satisfaction, departmental efficiency, and provider performance.

---

## 🛠️ Tools & Technologies
- **Microsoft Power BI** (Power Query, DAX, Data Modeling)
- **Data Transformation:** Power Query for cleaning and preparation
- **Visual Analytics:** Interactive dashboards with drill-through capabilities
- **Business Intelligence:** KPI tracking, trend analysis, performance benchmarking

---

## 📈 Key Business Insights (Extracted from Dashboard)

### **💰 Financial Performance**
- **Revenue Growth:** **$1M increase** year-over-year
- **Top Revenue Department:** **Cardiology** (25.62% of total patients)
- **Billing Distribution:** Dr. Sade Kikiola handles 37.37% of total billing
- **Financial Health:** Consistent patient volume supports revenue stability

### **👥 Patient Demographics & Flow**
- **Total Patients:** 1,235+ patients analyzed
- **Peak Months:** February–April (620–680 patients monthly)
- **Department Distribution:**
  - Cardiology: 25.62%
  - General Surgery: 23.70%
  - Orthopedics: 23.58%
  - Neurology: 13.94%
  - Pediatrics: 13.16%
- **Visit Types:** Balanced between routine and emergency visits

### **⭐ Patient Satisfaction & Quality**
- **Average Satisfaction:** 3.84/5 (Room for improvement)
- **Top Performing Provider:** Dr. Olu Abisola (5.45 satisfaction score)
- **Concern Area:** Dr. Sade Kikiola (2.35 satisfaction despite high billing volume)
- **Quality Correlation:** Higher billing doesn't always equal higher satisfaction

### **🏥 Operational Efficiency**
- **Seasonal Trends:** Clear monthly patterns for staffing planning
- **Department Load:** Cardiology carries highest patient volume
- **Diagnosis Patterns:** Hypertension leads at 18.36% of cases
- **Resource Allocation:** Opportunities to balance provider workloads

---

## 🔧 Technical Implementation

### **Data Preparation (Power Query)**
- **Duplicate Removal:** Cleaned patient records for accuracy
- **Data Standardization:** Unified formats across two years
- **Aggregation Setup:** Prepared data for monthly/yearly comparisons
- **Relationship Building:** Connected patient, provider, and billing tables

### **DAX Measures & Calculations**
```dax
// Key Performance Indicators
Total_Revenue = SUM(Billing[Amount])
Revenue_Growth = [Current_Year_Revenue] - [Previous_Year_Revenue]
Avg_Satisfaction = AVERAGE(Feedback[Satisfaction_Score])
Patient_Count = DISTINCTCOUNT(Patients[Patient_ID])
```
📁 Project Structure
```text
healthcare-analytics-powerbi/
├── 📊 Healthcare_Dashboard.pbix           # Main Power BI file
├── 📁 Dashboard                           # Dashboard preview
        ├── Department OverView
        ├── Patient State OverVier
├── 📄 README.md                           # This file
```
---

## 📬 Connect With Me

<p align="center">
  <!-- LinkedIn -->
  <a href="https://www.linkedin.com/in/mohamed-ayman-data/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <!-- GitHub -->
  <a href="https://github.com/mohamed-ayman-data" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <!-- Email -->
  <a href="mailto:mohmedaymn2025@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

<p align="center">
  <i>Let's collaborate on data-driven solutions!</i>
</p>

<hr>
<p align="center">
  <sub>📊 Data Analyst | 📈 Business Intelligence | 🎯 SQL Expert</sub>
</p>
