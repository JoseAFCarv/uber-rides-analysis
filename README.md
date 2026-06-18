# 🚗 Uber Rides Performance Analysis

## 📊 Project Overview

This Business Intelligence project focuses on extracting, modeling, and analyzing ride-hailing performance data across four European markets — Poland, Austria, Czechia, and Germany — throughout the year 2024. Using a robust star schema relational model built in Power BI based on approximately 10,000 trips, the analysis provides strategic operation evaluations across rides, drivers, customers, and temporal trends.

## 🎯 Strategic Key Insights

**Rides & Revenue Optimization:** Poland recorded the highest overall volume of rides, whereas Germany led in total revenue generation due to a significantly higher average ride value. Management should prioritize geographic penetration strategies in Czechia, which demonstrated the weakest performance metrics in both volume and market penetration.
**Payment Behavior & Data Quality:** Bank Transfer and Cash heavily dominate the system, representing nearly 70% of total rides with known methods. However, approximately one-third of all transactions lack payment information—marking a major data quality red flag that must be resolved to modernize users toward digital wallets.
**Driver Base Composition & Performance:** The average driver rating sits at 3.96, failing to meet the internal benchmark target of 4.5. More critically, only 1/3 of the driver base is actively working, with the remaining 2/3 marked as Inactive or Suspended, indicating serious driver retention challenges.
**High Cancellation Rates:** The ecosystem faces a steep overall cancellation rate of roughly 38.5%. Cancellations triggered by drivers (1,816) drastically outnumber customer cancellations (724), primarily driven by unavoidable circumstances such as "Personal Reasons" and "Vehicle Breakdowns".

## 🛠️ Technical Implementation

**Data Modeling:** Built a robust star schema relational model connecting qualitative quantitative metrics in a main fact table with structured dimension tables (Vehicles, Drivers, Customers, Reservations, Locations, and Dates).
**DAX & Metrics:** Developed custom calculated columns and DAX measures to analyze statistical earnings distributions, month-over-month trends, and specific driver status segments.
**Reporting:** Documented key findings into an executive performance report highlighting operational improvements needed to reactivate drivers, reduce peak cancellations, and enhance data logging workflows.

## 📁 Repository Contents

* `Uber_Rides_Dashboards.pbix` — The interactive Power BI dashboard and relational data model.
* `UberRides_analysis_report.pdf` — The full executive analysis report containing conclusions and operational recommendations.


