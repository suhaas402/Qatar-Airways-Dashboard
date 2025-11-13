# Qatar-Airways-Dashboard
Qatar Airways Analytics Dashboard

The Qatar Airways Analytics Dashboard is a data-driven project built using Power BI and Excel, using a single comprehensive dataset containing operational, commercial, and customer-focused airline metrics.
This dashboard helps analyze flight demand, fares, revenue performance, market share, punctuality, cancellations, and customer booking behavior across multiple routes and months.

📊 Project Overview

This repository contains the dataset and documentation used to build an interactive dashboard that visualizes:

Origin–destination (OD) route performance

Cabin-wise fares and demand segments

Revenue, market share, and load factor

On-time performance and cancellations

Booking behavior and distribution channel patterns

Competitor airline analysis

The insights help understand route profitability, customer preferences, and operational efficiency for Qatar Airways.

🧾 Dataset Description (Your Source File)

Your dataset contains 31 columns and includes metrics such as:

🔹 Route & Booking Details

origin, destination

month

cabin (Economy / Business)

booking_class

fare_family

distribution_channel (Direct / OTA / GDS etc.)

demand_segment (Business / VFR / Tourism)

🔹 Revenue & Pricing

base_fare_usd

total_fare_usd

taxes_usd

ancillary_revenue_usd

yield_usd_per_rpk

🔹 Operational Metrics

od_distance_km

load_factor_pct

on_time_performance_pct

cancellations_pct

days_to_departure

🔹 Market Intelligence

competitor_airline

qr_market_share_pct

competitor_market_share_pct

share_gap_pct

cost_per_booking_usd

This dataset is cleaned, structured, and ready for analysis.

🚀 Features of the Dashboard

Using this dataset, the dashboard provides:

1. Route Performance

Top performing OD pairs

Monthly travel demand patterns

Distance vs profitability visualization

2. Revenue & Fare Insights

Fare comparison by cabin, class, and fare family

Revenue per route and per passenger

Ancillary revenue contribution

3. Market Share Analytics

Qatar Airways vs Competitors

Share gap percentage per market

Competitive pricing zones

4. Operational Performance

Load factor trends

On-time performance scorecards

Cancellation rates per route

5. Customer & Booking Behavior

Demand segment breakdown (Business, Tourism, VFR)

Booking class usage

Distribution channel comparison (Direct / OTA / GDS)

📂 Repository Structure
/QatarAirways-Dashboard
│
├── data/
│   └── qatar_airways_dataset.csv
│
├── assets/
│   └── dashboard_screenshots/
│
├── QatarAirways_Dashboard.pbix  (Power BI file)
└── README.md

🛠️ Tech Stack

Power BI — dashboard development

Excel — data cleaning, validation, minor ETL

CSV Dataset — single source of truth

Power Query — transformations & modeling

🧠 Insights You Can Make From This Dashboard

Identify routes with highest revenue or strongest demand

Detect competitive threat routes based on share gap

Evaluate the performance of fare families (Classic, Comfort, Elite…)

Compare OTA vs Direct booking trends

Study punctuality and operational reliability

Understand booking behavior relative to days before departure

🧪 Example Use Cases

Which destination generates the highest revenue in Business class?

Are OTA bookings associated with lower or higher fares?

Which routes have high market share but low load factor?

How does on-time performance impact revenue for long-haul flights?
