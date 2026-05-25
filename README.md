# 📊 Meta Ad Performance Analysis Dashboard

A Power BI dashboard project focused on analyzing Meta (Facebook & Instagram) advertising campaign performance. This project helps marketing teams track engagement, conversions, audience behavior, and campaign effectiveness through interactive visualizations and KPI analysis.

---

## 🚀 Project Overview

This dashboard was developed to analyze advertising campaign performance across Meta platforms and generate actionable business insights for marketing optimization.

The project focuses on:

- Campaign reach and engagement
- Conversion funnel analysis
- Audience segmentation
- Geographic performance
- Ad type effectiveness
- Budget utilization
- Time-based engagement trends

### Marketing Funnel Covered

```text
Impressions → Clicks → Engagements → Purchases
```

---

## 🎯 Business Objective

The goal of this project is to help marketing teams:

- Identify the best-performing ad platforms and ad formats
- Understand audience engagement patterns
- Improve campaign ROI
- Optimize ad timing and targeting
- Analyze conversion funnel performance
- Support data-driven marketing decisions

---

## 🛠️ Tools & Technologies Used

- Power BI
- DAX
- Power Query
- Data Modeling
- CSV Datasets
- Data Visualization Techniques

---

## 📂 Dataset Information

The project uses 4 datasets:

| Table Name | Description |
|------------|-------------|
| `ad_events` | Stores user interactions such as impressions, clicks, shares, comments, and purchases |
| `ads` | Contains ad-level metadata like platform, ad type, and target audience |
| `campaigns` | Stores campaign details such as budget and duration |
| `users` | Contains demographic and geographic user information |

---

## 🧩 Data Model

The dashboard follows a **Star Schema** data model.

### Fact Table
- `ad_events`

### Dimension Tables
- `ads`
- `campaigns`
- `users`

### Relationships Created Using
- `ad_id`
- `campaign_id`
- `user_id`

This model enables efficient KPI calculations and seamless cross-filtering between visuals.

---

## 📈 KPIs Used

The dashboard tracks several important marketing KPIs:

- Impressions
- Clicks
- Shares
- Comments
- Purchases
- Engagements
- CTR (Click Through Rate)
- Engagement Rate
- Conversion Rate
- Purchase Rate
- Total Budget
- Average Budget per Campaign

---

## 🧮 DAX Measures Used

```DAX
CTR = DIVIDE([Clicks], [Impressions]) * 100

Engagement Rate = DIVIDE([Engagements], [Impressions]) * 100

Conversion Rate = DIVIDE([Purchases], [Clicks]) * 100

Purchase Rate = DIVIDE([Purchases], [Impressions]) * 100
```

Additional features implemented:
- Dynamic KPI selection
- Parameter-based metric switching
- Interactive calculations

---

## 📊 Dashboard Features

### 👥 Audience Analysis
- Gender-wise engagement analysis
- Age group performance comparison

### 🌍 Geographic Insights
- Country-wise campaign performance using map visualization

### ⏰ Time-Based Analysis
- Weekly engagement trends
- Hourly engagement patterns
- Calendar heatmap for seasonal activity

### 🎥 Ad Performance Analysis
Comparison of ad formats:
- Video Ads
- Carousel Ads
- Story Ads
- Image Ads

### ⚡ Interactive Features
- Dynamic KPI selection
- Tooltips
- Dynamic titles
- Interactive filtering

---

## 💡 Key Business Insights

- High CTR and Engagement Rate indicate strong ad creatives and targeting
- Purchase Rate is relatively low, showing funnel drop-off after engagement
- Females aged 18–30 were the most engaged audience segment
- India and Brazil generated high engagement volume
- Video and Story ads performed better than Image and Carousel ads
- User engagement peaked during afternoon and evening hours

---

## ✅ Recommendations

- Improve landing pages and conversion strategy
- Increase budget allocation toward Video and Story ads
- Focus targeting on high-performing audience segments
- Schedule campaigns during peak engagement hours
- Use retargeting campaigns to improve purchase conversions

---

## 🎓 Project Learning Outcomes

Through this project, I gained hands-on experience in:

- Power BI dashboard development
- Data modeling using star schema
- DAX calculations
- Marketing analytics
- KPI analysis
- Interactive visualization design
- Business insight generation

---

## 📁 Files Included

- Power BI Dashboard (`.pbix`)
- CSV Datasets

---

## 🖼️ Dashboard Preview


<img width="1420" height="792" alt="meta_ads" src="https://github.com/user-attachments/assets/fd2c773b-3a15-4856-87b2-04f157f89e6b" />


## 🔮 Future Improvements

- Add advanced marketing KPIs like ROAS, CPC, and CPM
- Integrate real-time data sources
- Implement drill-through pages
- Add predictive analytics using Python/ML integration

---

## 👨‍💻 Author

**Vedang Tiwari**  

