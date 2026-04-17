# Wearable Device Data Quality Dashboard

## Overview
This project analyzes data quality issues from wearable devices, focusing on two key dimensions:

- Accuracy
- Completeness

The goal is to identify hidden data risks and provide both system-level and user-level insights.

---

## Data Description

The dataset contains wearable device data from 10 users across 60+ health and activity metrics over time.

Each record is evaluated for data quality across two dimensions:
- **Accuracy**: whether values are within expected ranges  
- **Completeness**: whether required data is missing  

An `issue` flag (1 = issue, 0 = valid) is used to calculate issue rates by user, metric, and time.

---

## Problem

Although overall issue rates appear low (~8%), deeper analysis reveals:

- Significant accuracy issues (~38%)
- Certain metrics consistently failing (up to 100%)
- Data quality problems affecting all users

---

## Dashboard Design

### 1. System-Level Dashboard

<img width="2404" height="1602" alt="1" src="https://github.com/user-attachments/assets/93e9eb9e-2b64-4a31-84ca-b3e58897b44d" />

- Overall issue rate KPI
- Accuracy vs Completeness comparison
- Top failing metrics
- Issue distribution across users
- Time-based trends

Purpose: Identify global data quality risks

---

### 2. User-Level Dashboard

<img width="2402" height="1604" alt="2" src="https://github.com/user-attachments/assets/1bdc3866-40e5-46cd-bd26-ed001183b27c" />

- Personalized issue rate
- Dynamic insight generation
- Top problematic metrics per user
- Daily issue trend

Purpose: Help users understand and improve their own data quality

---

## Tools Used

- Python (data processing)
- Pandas (data transformation)
- Tableau (dashboard design)

---

## 💡 Key Insights

- Overall issue rate (~8%) can be misleading
- Accuracy issues are the dominant problem
- Missing activity-related metrics drive most failures
- Data issues are consistent across users (system-level issue)

---

## Value

This project demonstrates:

- Data quality analysis
- Dashboard storytelling
- UX thinking in data products
- Personalized analytics design

---





