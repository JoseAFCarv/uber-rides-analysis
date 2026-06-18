# 🚗 Uber Rides Performance Analysis

## 📊 Project Overview

[cite_start]This Business Intelligence project focuses on extracting, modeling, and analyzing ride-hailing performance data across four European markets — Poland, Austria, Czechia, and Germany — throughout the year 2024[cite: 4, 19]. [cite_start]Using a robust star schema relational model built in Power BI based on approximately 10,000 trips, the analysis provides strategic operation evaluations across rides, drivers, customers, and temporal trends[cite: 4].

## 🎯 Strategic Key Insights

* [cite_start]**Rides & Revenue Optimization:** Poland recorded the highest overall volume of rides, whereas Germany led in total revenue generation due to a significantly higher average ride value[cite: 5]. [cite_start]Management should prioritize geographic penetration strategies in Czechia, which demonstrated the weakest performance metrics in both volume and market penetration[cite: 6].
* [cite_start]**Payment Behavior & Data Quality:** Bank Transfer and Cash heavily dominate the system, representing nearly 70% of total rides with known methods[cite: 7, 33]. [cite_start]However, approximately one-third of all transactions lack payment information—marking a major data quality red flag that must be resolved to modernize users toward digital wallets[cite: 7].
* [cite_start]**Driver Base Composition & Performance:** The average driver rating sits at 3.96, failing to meet the internal benchmark target of 4.5[cite: 8]. [cite_start]More critically, only 1/3 of the driver base is actively working, with the remaining 2/3 marked as Inactive or Suspended, indicating serious driver retention challenges[cite: 9, 53, 54].
* [cite_start]**High Cancellation Rates:** The ecosystem faces a steep overall cancellation rate of roughly 38.5%[cite: 11]. [cite_start]Cancellations triggered by drivers (1,816) drastically outnumber customer cancellations (724), primarily driven by unavoidable circumstances such as "Personal Reasons" and "Vehicle Breakdowns"[cite: 12].

## 🛠️ Technical Implementation

* [cite_start]**Data Modeling:** Built a robust star schema relational model connecting qualitative quantitative metrics in a main fact table with structured dimension tables (Vehicles, Drivers, Customers, Reservations, Locations, and Dates)[cite: 21, 173].
* [cite_start]**DAX & Metrics:** Developed custom calculated columns and DAX measures to analyze statistical earnings distributions, month-over-month trends, and specific driver status segments[cite: 58, 59, 60].
* [cite_start]**Reporting:** Documented key findings into an executive performance report highlighting operational improvements needed to reactivate drivers, reduce peak cancellations, and enhance data logging workflows[cite: 16, 17].

## 📁 Repository Contents

* `Uber_Rides_Dashboards.pbix` — The interactive Power BI dashboard and relational data model.
* `UberRides_analysis_report.pdf` — The full executive analysis report containing conclusions and operational recommendations.


