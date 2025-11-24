📊 Fashion Clickstream Funnel Analysis
By Hetvi Patel

A complete end-to-end Clickstream Analytics & E-commerce Funnel Optimization project built using Power BI, based on user behavior data from a fashion e-commerce platform.
This dashboard helps understand customer interactions, drop-off patterns, device behavior, campaign performance, revenue insights, and conversion metrics to improve digital marketing ROI and user journey efficiency.

🚀 Project Objective

To analyze user interactions across the website—from landing on the homepage to completing a purchase—using clickstream data.
The dashboard answers critical questions such as:

-How do users navigate through the purchase funnel?

-What devices or traffic sources drive the most sessions?

-Where do users drop off most frequently?

-How do campaigns perform in terms of CPA and conversion?

-Which product categories or devices contribute higher orders?

-What are the revenue, AOV, and cart abandonment insights?

📁 Dataset Overview

The project uses three main datasets:

1. clickstream_events.csv

Contains event-level data such as:

Event Type

Device Type

Traffic Source

Session ID

Page url

Event Timestamp

Cateogry

Event ID 

User ID

2. orders.csv

Includes order details such as:

Order ID

User ID

Order_value

Campaign ID

Date

3. campaign_cost.csv

Includes:

Campaign ID

Campaign Name

Cost

Impressions

Clicks

Spend (Used to calculate CPA)

🎨 Dashboard Structure (3 Pages)
🟦 Page 1: Traffic & Category Insights

This page focuses on website traffic and high-level category behavior.

✔ Key KPIs:

Total Sessions

Orders by Category

Conversion Rate

Average Order Value (AOV)

✔ Visuals:

Donut Chart: Sessions by Device Type

Clustered Bar Chart: Orders by Category

Funnel Chart: Complete funnel from Homepage → Purchase

Ribbon Chart: Device-wise Category Session Flow

🟩 Page 2: Behavior & Engagement Analytics

This page focuses on event interactions, traffic quality, and time trends.

✔ Top KPIs:

Total Sessions

Conversion Rate

✔ Visuals:

Clustered Bar Chart: Orders by Device

Donut Chart: Sessions by Traffic Source

Matrix (Heatmap): Event Frequency by Device

Line Chart: Event Distribution by Hour & Date

🟧 Page 3: Revenue & Efficiency

This page captures revenue-focused insights and marketing efficiency.

✔ KPIs:

Total Revenue

AOV (Average Order Value)

Cart Abandonment Rate

CPA (Cost Per Acquisition)

✔ Visuals:

Line Chart: Sessions vs Event Hours

Drop-Off Users Gauge

Bar Chart: CPA by Campaign

Table view: Drop off Count from Add to Cart to Purchase

🛠 Tools & Technologies

Power BI Desktop

Data Modeling (Star Schema)

DAX (Measures + Calculated Columns)

Data Cleaning & Transformation in Power Query

Git & GitHub for version control
