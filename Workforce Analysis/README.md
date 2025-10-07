# 📊 Workforce Management Dashboard (Excel Project)

## 🔍 Project Overview

This project focuses on **monitoring and optimizing call center performance** using an interactive Excel dashboard. It tracks Service Level, Abandonment, Adherence, and Occupancy across Billing, Sales, and Support queues to help workforce managers make data-driven staffing and performance decisions.

✅ Built entirely in **Microsoft Excel** using Power Pivot, PivotTables, and Timeline slicers.

---

## 🧠 Key Questions Answered

1. **What hours and queues are missing SLA targets?**  
2. **How do Abandonment Rate and ASA impact SLA performance?**  
3. **Are agents adhering to schedules consistently across queues?**  
4. **What is the relationship between Occupancy, AHT, and SLA?**  
5. **How can staffing be improved to reduce missed SLAs?**

---

## 🗂️ Dataset

- Source file: (https://github.com/Yungssu/ExcelAnalysis/blob/main/Workforce%20Analysis/workforce_data.csv)
- Columns include:
  - `Timestamp`, `Queue`, `Calls_Offered`, `Calls_Answered`, `Calls_Abandoned`
  - `SLA_Actual_pct_fixed`, `SLA_Target_pct_fixed`
  - `Adherence_pct`, `Occupancy`, `Avg_Handle_Time_sec`, `Abandonment_Rate_pct`
- Data was cleaned and modeled using **Power Pivot** to create calculated measures for KPIs:
  - **Average SLA**
  - **Abandonment Rate**
  - **Adherence**
  - **Occupancy**
  - **AHT** and **ASA**
  - **Service Level Achievement**
    
📂 [View the Project Folder](https://github.com/Yungssu/ExcelAnalysis/blob/main/Workforce%20Analysis/WorkforceAnalysis.md)

---

## 📊 Summary of Findings

### 1. Service Level Performance
- Average SLA: **89%**
- SLA Target: **90%**
- Only **68% of intervals** met the SLA goal.  
- SLA dips occur during high-volume hours (8 AM to 11 AM).

### 2. Call Handling Metrics
| Metric | Average Value |
| ------- | -------------- |
| ASA (Average Speed of Answer) | 0.63 mins |
| AHT (Average Handle Time) | 7.05 mins |
| Abandonment Rate | 16.08% |

- Longer ASA values align with higher abandonment.  
- Billing queue experiences the longest handle times, affecting SLA.

### 3. Agent Efficiency
- **Average Adherence:** 90%  
- **Average Occupancy:** 56%  
- Underutilization in off-peak hours indicates opportunity to optimize scheduling.

---

## 💡 Recommendations

- Rebalance staffing between **Billing and Support** during 8 AM–11 AM.  
- Aim to lower **ASA** below 0.5 mins to improve SLA.  
- Monitor **Occupancy** to ensure agents are not over or under-scheduled.  
- Continue improving **Adherence** to maintain steady SLA performance.  

---


## 🏁 Final Thoughts

The dashboard provides an executive view of performance efficiency, helping identify bottlenecks and staffing gaps.  
It simulates how analysts support workforce teams in achieving operational targets and improving customer experience.

🚀 More Excel-based analytics projects coming soon!

