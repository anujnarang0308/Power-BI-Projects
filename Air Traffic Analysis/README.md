## 📌 Project Overview


https://github.com/anujnarang0308/Power-BI-Projects/blob/main/Air%20Traffic%20Analysis/Air%20Traffic%20Analysis%20-Screenshot.png

This project addresses client requirements for understanding airline operational reliability and departure traffic distribution:
* **Flight Status Analysis:** Evaluating the proportion of on-time, delayed, and cancelled flights month-by-month and by day of the week.
* **Air Traffic Analysis:** Identifying peak departure hours and traffic density across origin airports (BWI, DCA, IAD) to provide actionable insights for flight scheduling and booking optimizations.

---

## 🔑 Key Business Insights & Findings

### 1. Flight Operational Reliability & Delays
* **Average Delay Duration:** Recorded a cumulative average delay of **15,935.92 minutes** across the dataset across all monitored airlines.
* **Weekly Performance Trends:** On-time flight volumes consistently peak on **Fridays (261 flights)** and **Thursdays (247 flights)**, while **Sundays (185 flights)** experience higher relative delays.
* **Flight Status Breakdown:** Standard flight volume composition highlights that approximately **57.45%** of monitored flights operate on-time, **36.67%** experience delays, and **5.88%** are cancelled during high-volume periods.
* **Year-over-Year Delay Trends:** Delta Air Lines and American Airlines exhibited variation in average delay times across the 2009–2011 period.

### 2. Air Traffic & Peak Hours
* **Peak Departure Windows:** The highest volume of flight departures occurs in early morning slots (**07:00** and **10:00**) and late evening hours (**23:00**).
* **Airport Capacity Utilization:** Regional traffic analysis highlights DCA and BWI as major departure drivers for carriers such as ExpressJet and American Eagle Airlines.

---

## 🛠 Tech Stack & Tools
* **BI & Visualization:** Power BI Desktop, Power BI Service (Dashboarding & Web Publishing)
* **Data Transformation & Modeling:** Power Query, Star Schema Data Modeling
* **Analytics Language:** DAX (Data Analysis Expressions)
* **Source Data:** Relational CSV / Excel Flight Transaction Records

---

## 📊 Data Analysis & Modeling Highlights

### Key Fields & Measures Used
* `Airline Name` — Primary categorical grouping for carrier performance.
* `Day of Week` & `Departure Hour` — Used for temporal traffic segmentation.
* `Flights Cancelled`, `Flights Delayed`, `On-Time` — Calculated status measures.
* `Avg Delay (min)` — KPI card measure computing overall delay duration.
* `Origin Airport` — Spatial filter for airport-level traffic breakdown (BWI, DCA, IAD).

### Data Model Architecture


```text
[Sheet1 / Flight Records]
  ├── Airline Name
  ├── Origin Airport (BWI, DCA, IAD)
  ├── Day of Week / Departure Hour / Month / Year
  └── Operational Metrics (On-Time, Flights Delayed, Flights Cancelled, Avg Delay)

https://github.com/anujnarang0308/Power-BI-Projects/blob/main/Air%20Traffic%20Analysis/Airline%20Traffic%20Analysis.pbit
  
https://github.com/anujnarang0308/Power-BI-Projects/blob/main/Air%20Traffic%20Analysis/Airline%20Traffic%20Analysis.pbit
