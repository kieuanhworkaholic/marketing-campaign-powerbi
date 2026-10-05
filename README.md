# Marketing Campaign Performance Analysis 2024

Interactive Power BI dashboard analyzing campaign performance across campaigns, campaign types and channels, from advertising efficiency (ROAS, CPA) to the conversion funnel.

![Dashboard Overview](images/01_overview.png)

📄 [View full dashboard (PDF)](Marketing_Campaign_Dashboard.pdf)

## Business Question

**Where should the next marketing dollar go?**
$13.67K of ad spend generated $54.42K in revenue (**ROAS 3.98**) and 1,129 conversions, but results vary widely: the best campaigns return 5 to 7× their spend, the weakest less than 2×.

## Dashboard

| Page | What it shows |
| --- | --- |
| **Overview** | 7 KPI cards, monthly spend vs revenue, ROAS by channel and campaign |
| **Campaign & Channel Analysis** | Campaign ranking, Spend vs ROAS, Campaign × Channel heat map, CPA by type |
| **Funnel & Trends** | Impressions → clicks → conversions, CTR / CVR / CPA trends |
| **Insights & Recommendations** | What works, what to improve, next steps |

![Campaign & Channel Analysis](images/02_campaign_channel_analysis.png)
![Funnel & Trends](images/03_funnel_trends.png)

## KPIs

| KPI | Formula | Result |
| --- | --- | --- |
| ROAS | Revenue ÷ Spend | 3.98 |
| CTR | Clicks ÷ Impressions | 5.9% |
| CVR | Conversions ÷ Clicks | 7.4% |
| CPA | Spend ÷ Conversions | $12.11 |

## Key Insights

- **Retention has the best ROAS** (up to 6.97) while using only 11.15% of spend.
- **Sales Activation** takes the largest share (40.9%) and stays efficient: lowest CPA ($7.79), ROAS 5.15 to 5.21.
- **Brand Awareness is the weak spot**: 25.07% of spend, ROAS below 2 on all 3 campaigns, CPA $83.58 (over 10× Sales Activation).
- **Email leads on ROAS (5.09), Search Ads on conversion (CVR 11.8%).**
- **Display Ads data looks inconsistent**: 0.0% CVR but ROAS 3.38, a possible conversion-tracking issue.
- **August is an anomaly**: CPA spiked to about $76 (6× the average); performance recovered strongly in October and November.

## Recommendations

1. Reduce Brand Awareness spend, starting with *Back to School* (CPA $108.47).
2. Scale Sales Activation and Retention gradually while monitoring CPA.
3. Verify Display Ads conversion tracking before reallocating budget.
4. Prioritize Email and Search Ads; optimize Social Media (CVR 1.6%) instead of cutting it.
5. Investigate August and replicate what worked in October to November.

## Data Notes

- No data for July, so monthly trends show a gap.
- ROAS uses attributed revenue and does not account for margin.

## Tools

Power BI · Power Query · DAX · Excel

## Repository

```
├── images/                                       # Dashboard screenshots
├── Marketing_Campaign_Data.xlsx                  # Data source
├── Marketing_Campaign_Performance_Analysis.pbix  # Power BI file
├── Marketing_Campaign_Dashboard.pdf              # Exported dashboard
└── README.md
```

## Author

**Kieu Anh Nguyen** 
