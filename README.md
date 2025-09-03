*🚖 Ride Booking Analysis Dashboard – Power BI*

📌 Project Overview

This project showcases an interactive Power BI dashboard built using ride-booking data sourced from Kaggle.
The goal was to analyze revenue, demand-supply gap, cancellations, and customer/driver experience using advanced data visualization techniques.

During development, I also leveraged Power BI Copilot AI to auto-generate DAX measures and accelerate dashboard building.

---

*📊 Key Insights*

🔹 Revenue Analysis

Total Revenue: ₹52M

Average Revenue per Ride: ₹508.30

Vehicle types like Auto (₹12.9M) and Go Mini (₹10.3M) contribute maximum revenue.

Revenue trend shows monthly fluctuations with clear seasonality.


🔹 Demand & Supply

62% rides completed, while 25% cancellations were observed.

7% No Driver Found, highlighting supply shortages.

AI-driven analysis shows demand often exceeds supply in certain months.


🔹 Operational Performance

Driver Experience Score: 4.23 (Target: 4.50 → -5.92%)

Customer Experience Score: 4.40 (Target: 4.50 → -2.26%)

These KPIs help monitor service quality against business goals.


🔹 Booking Status Breakdown

Completed: 93K rides (62%)

Cancelled by Driver: 10.5K (7%)

Cancelled by Customer: 9K (6%)

No Driver Found: 10.5K (7%)

Incomplete: 27K (18%)

---

🛠 Tools & Techniques Used

Dataset Source: Kaggle (Ride-booking dataset).

Power BI – for dashboard creation & visual storytelling.

Power BI Copilot AI – assisted in generating DAX formulas like:

Completion % = DIVIDE([Completed Rides], [Total Bookings])

Cancellation % = DIVIDE([Cancelled Rides], [Total Bookings])

Avg. Revenue per Ride = DIVIDE([Total Revenue], [Completed Rides])


Data Cleaning & Transformation – Power Query.

Visualizations – Pie Charts, KPI Cards, Line Charts, and Trend Analysis.

---

📈 Business Value

This dashboard helps stakeholders in the ride-hailing industry to:

Track revenue trends and identify high-performing vehicle types.

Detect demand-supply mismatches to improve resource allocation.

Dashboard image- https://github.com/arya-sharma-1/Rapido-Dashboard/blob/main/Rapido%20Dashboard.png

Measure driver and customer satisfaction vs business targets.

Reduce cancellations by understanding key problem areas.
