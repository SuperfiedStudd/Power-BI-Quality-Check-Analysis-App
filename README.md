# Power-BI-Quality-Check-Analysis-App  

[View on Microsoft AppSource](https://appsource.microsoft.com/en-us/product/power-bi/dhyeyconsultingservicespvtltd1584430919382.quality-check-analysis?tab=Overview)  

[![Watch the Demo](https://img.youtube.com/vi/Wq9HwiC4jJw/0.jpg)](https://youtu.be/Wq9HwiC4jJw?si=9nqhAgoZF9S2-9MG)  

---

## Overview  

In high-output manufacturing environments, managing quality failures proactively is critical to minimizing rework time and controlling production costs. The Quality Check Analysis Dashboard offers a clear, data-driven view of failure patterns, root causes, and resolution timelines—enabling operations and quality assurance teams to identify trends and prioritize improvements.  

This Power BI app transforms fragmented QC logs into actionable insights, helping reduce recurring issues, optimize repair cycles, and lower the cost of non-conformance.  

---

## Technical Framework  

The dashboard is powered by structured QC failure records, linked to plant locations, failure categories, and corrective action data.  

**Key components:**  
- **Data Source:** Excel or system exports detailing failure IDs, types, reasons, fix duration, and cost implications  
- **Data Preparation:** Performed in Power Query to clean, standardize, and categorize failure reasons and resolution times  
- **Data Model Dimensions:**  
  - Location  
  - QC Failure Type (e.g., Density, Packaging, Temperature Sensitivity)  
  - Failure Reason  
  - Time to Fix (Days)  
  - Extra Cost  

This structure supports scalable integration with MES, ERP, and CAPA systems.  

---

## Interactive Filters  

To support precise failure tracking, the dashboard includes:  
- **Location Filter:** Zoom in on plant-specific performance issues  
- **Failure Type Filter:** Narrow the view to specific QC categories  

These filters help teams isolate critical issues and take location-specific or material-specific actions quickly.  

---

## Dashboard Highlights  

**Pie Chart – QC Failure by Failure Type**  
Visual breakdown of the major types of quality failures across all locations (e.g., Density Failure, Raw Material Failure).  

**Column Chart – QC Failure by Failure Reason**  
Top reasons behind QC failures (e.g., Improper rolling, Overheated bitumen), along with their frequency—enabling pattern recognition and root cause analysis.  

**Column Chart – Average Time to Fix by Failure Type**  
Compares average resolution time across failure types, revealing which issues cause the most downtime.  

**Table – QC Failure Details**  
Detailed records of each failure including:  
- QC Failure ID  
- Location  
- Type and Reason of Failure  
- Days to Fix  
- Associated Extra Cost  

A total extra cost figure at the bottom quantifies the operational impact of unresolved or recurring quality issues.  

---

## Screenshots  

### QC Failure by Type  
![Failure Type](https://github.com/SuperfiedStudd/Power-BI-Quality-Check-Analysis-App/blob/main/docs/failure_type.png?raw=true)  

### QC Failure by Reason  
![Failure Reason](https://github.com/SuperfiedStudd/Power-BI-Quality-Check-Analysis-App/blob/main/docs/failure_reason.png?raw=true)  

### Average Time to Fix  
![Time to Fix](https://github.com/SuperfiedStudd/Power-BI-Quality-Check-Analysis-App/blob/main/docs/time_to_fix.png?raw=true)  

### QC Failure Details Table  
![Failure Details](https://github.com/SuperfiedStudd/Power-BI-Quality-Check-Analysis-App/blob/main/docs/failure_details.png?raw=true)  

---

## How to Use  

This repository is intended as a showcase:  
1. Watch the demo video above for a walkthrough.  
2. Explore the screenshots for dashboard views.  
3. Try the published app directly on [Microsoft AppSource](https://appsource.microsoft.com/en-us/product/power-bi/dhyeyconsultingservicespvtltd1584430919382.quality-check-analysis?tab=Overview).  
   - You can download and play around with the app if you have a school or work account that supports Microsoft apps.  

---

## Why It Matters  

This dashboard enables a proactive quality control culture by making failure data visible, measurable, and actionable—reducing rework cycles, supporting root cause correction, and optimizing cost-efficiency in production.  

---

## Author  

Developed by **Jasjyot Singh**  
Contact: jasjyotsingh.work@gmail.com  
