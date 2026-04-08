# 📊 Data Quality Analysis of Healthcare Wearable Devices

## 🧩 Project Overview
This project evaluates the data quality of a healthcare wearable device to identify issues affecting the reliability of recorded health metrics and support improvements in device performance.

---

## 🎯 Objectives
- Assess data completeness and accuracy across key metrics  
- Identify patterns of missing or inconsistent data  
- Provide actionable insights to improve data reliability  

---

## 📦 Dataset
The dataset contains data quality measurements across multiple health metrics, including:
- Category and dimension information  
- Metric names  
- Timestamps for trend analysis  
- Subject-related attributes  

---

## 🛠️ Tools & Technologies
- Python (pandas)  
- Tableau  
- SQL (for data querying logic)

---

## ⚙️ Methodology
1. Data cleaning and preprocessing  
2. Definition of key metric: `issue_rate`  
3. Exploratory data analysis (EDA)  
4. Time-series analysis  
5. Dashboard development in Tableau  

---

## 📊 Dashboard Design

To support both business monitoring and user-level insights, three dashboards were developed:

### 1. Overall Device Monitoring Dashboard
- Tracks overall data quality performance across all metrics  
- Highlights issue rates and trends over time  
- Helps stakeholders quickly identify system-level problems  

### 2. User-Level Monitoring Dashboard
- Provides an overview of data quality for individual users  
- Allows users to understand their overall recording performance  

### 3. Metric-Specific Monitoring Dashboard
- Focuses on specific health metrics (e.g., heart rate, movement, sleep)  
- Enables detailed investigation of data quality issues  
- Helps identify patterns and potential causes of anomalies  

---

## 🔍 Key Insights
- Most metrics show high reliability with near-zero issue rates  
- Movement-related metrics have higher issue rates, likely due to sensor or activity factors  
- Sleep and readiness metrics show higher missing rates  
- Heart rate metrics contain anomalies that may indicate measurement inconsistencies  

---

## 🚀 Business Recommendations
- Improve movement tracking accuracy during active conditions  
- Enhance data collection for sleep-related metrics  
- Investigate heart rate anomalies for better reliability  
- Use dashboards for continuous monitoring and improvement  

---

## 📊 Dashboard Preview
### Overall Device Monitoring
![Dashboard](Dashboard1.jpg)

### User-Level Monitoring
![Dashboard](Dashboard2.jpg)

### User-Level Monitoring
![Dashboard](Dashboard3.jpg)

---

## 💡 Key Takeaway
This project demonstrates how data analysis can identify quality issues in healthcare devices and support data-driven product improvements.
