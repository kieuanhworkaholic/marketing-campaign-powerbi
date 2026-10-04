# Marketing Campaign Performance Analysis

Power BI dashboard for analyzing marketing campaign performance,
channel effectiveness, customer conversion, and advertising efficiency.

---

## Project Overview

This project provides an interactive analysis of marketing campaign
performance across campaigns, campaign types, and marketing channels.

The dashboard is designed to support performance monitoring, campaign
comparison, budget evaluation, and data-driven marketing decisions.

---

## Business Objectives

- Evaluate overall marketing campaign performance
- Measure advertising efficiency and return on investment
- Compare campaign and channel performance
- Analyze the conversion funnel from impressions to conversions
- Identify high-performing and underperforming campaigns
- Identify opportunities for campaign and budget optimization

---

## Dataset

The dataset contains marketing campaign performance data, including:

- Campaign
- Campaign Type
- Marketing Channel
- Impressions
- Clicks
- Conversions
- Spend
- Revenue
- Date

### Marketing Channels

- Email
- Search Ads
- Social Media
- Display Ads

---

## Key Performance Indicators

| KPI | Description |
|---|---|
| Total Spend | Total advertising expenditure |
| Total Revenue | Revenue generated from campaigns |
| ROAS | Return on advertising spend |
| CTR | Click-through rate |
| CVR | Conversion rate |
| CPA | Cost per acquisition |
| Total Conversions | Number of recorded conversions |

---

## Dashboard

The dashboard is structured into four analytical views:

### 01. Overview

Provides a high-level summary of marketing performance, including:

- Total Spend
- Total Revenue
- ROAS
- Total Conversions
- CTR
- CVR
- CPA
- Monthly Spend & Revenue
- ROAS by Channel
- Spend by Campaign Type
- ROAS by Campaign

### 02. Campaign & Channel Analysis

Provides a detailed comparison of campaign and channel efficiency:

- Campaign Ranking
- Spend vs. ROAS
- Campaign × Channel ROAS
- CPA by Campaign Type

### 03. Funnel & Trends

Evaluates the marketing conversion funnel and performance trends:

- Impressions
- Clicks
- Conversions
- CTR by Channel
- CVR by Channel
- CTR & CVR by Month
- CPA by Month

### 04. Insights & Recommendations

Highlights key performance drivers, inefficient campaigns,
performance anomalies, and opportunities for marketing optimization.

---

## Key Insights

### Campaign Performance

- Retention campaigns delivered the strongest ROAS performance,
  reaching up to **6.97**.
- Sales Activation generated strong returns while accounting for
  **40.9% of total campaign spend**.
- **11.11 Mega Sale** generated the highest campaign revenue at
  **$12.63K** with a CPA of **$6.44**.

### Channel Performance

- **Email** recorded the highest ROAS at **5.09**.
- **Search Ads** achieved the highest CVR at **11.8%**.
- Social Media showed relatively lower conversion efficiency.
- Display Ads showed a potential conversion-tracking or
  data-quality issue, with **0.0% CVR** despite positive ROAS.

### Campaign Type Performance

- Sales Activation demonstrated strong efficiency with the lowest
  campaign-type CPA at **$7.79**.
- Brand Awareness showed comparatively weak efficiency, with
  **25.07% of total spend** and a CPA of **$83.58**.
- Lead Generation produced moderate CPA performance but ROAS remained
  below the overall campaign average.

### Time-Based Performance

- Overall campaign performance improved toward the end of the year.
- August showed a significant increase in CPA and a decline in CVR.
- October and November showed stronger conversion efficiency and lower CPA.

---

## Recommendations

- Reallocate budget away from consistently underperforming
  Brand Awareness campaigns.
- Scale high-performing Sales Activation and Retention campaigns
  while monitoring incremental CPA.
- Prioritize Email and Search Ads based on their strong efficiency
  and conversion performance.
- Investigate Display Ads conversion tracking before making major
  budget allocation decisions.
- Optimize Social Media campaigns to improve conversion efficiency.
- Review the performance drivers behind the August anomaly and
  replicate successful patterns observed later in the year.

---

## Tools & Technologies

- **Power BI** — Dashboard & Data Visualization
- **Power Query** — Data Transformation
- **DAX** — KPI & Measure Development
- **Microsoft Excel** — Data Source

---

## Project Structure

```text
marketing-campaign-powerbi/
│
├── Marketing_Campaign_Data.xlsx
├── Marketing_Campaign_Performance_Analysis.pbix
├── Marketing_Campaign_Dashboard.pdf
└── README.md
