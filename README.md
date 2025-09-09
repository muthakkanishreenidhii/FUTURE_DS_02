# FUTURE_DS_02
🔍 Project Overview

This project focuses on analyzing social media ad campaign data (Facebook/Instagram-style) to evaluate performance and build an interactive Power BI dashboard.

The dashboard helps marketing teams answer:

Which ads had the highest CTR (Click-Through Rate) and ROI?

Which demographics (age, gender, device, region) engaged the most?

How did ad spend and conversions vary over time?

What improvements can be made for future campaigns?


📊 Dataset Description

The dataset contains simulated social media ads campaign data with the following key fields:

date → Campaign run date

campaign_id → Unique campaign identifier

ad_name → Ad creative name

impressions → Number of times ad was displayed

clicks → Number of clicks received

spend → Advertising cost ($)

conversions → Number of completed goals (sales, signups, etc.)

revenue → Revenue generated from conversions

likes, shares, comments → Engagement metrics

age, gender, device, region, placement → Demographic/targeting info

🛠️ Tools Used

Power BI Desktop → Dashboard creation & visualization

Excel / Power Query → Data cleaning & preprocessing

DAX (Data Analysis Expressions) → Custom KPIs and measures

📐 Key Measures (DAX)

CTR % = (Clicks / Impressions) * 100

CPC = Spend / Clicks

CPM = (Spend / Impressions) * 1000

Conversion Rate % = (Conversions / Clicks) * 100

Cost per Conversion = Spend / Conversions

ROI % = (Revenue – Spend) / Spend * 100

📊 Dashboard Features

KPI Cards → Impressions, Clicks, CTR, Spend, CPC, ROI

Trend Line → CTR % & Spend over time

Bar Chart → Top Ads by ROI & Conversions

Stacked Bar Chart → Engagement (Likes, Shares, Comments) per ad

Demographics → CTR by Age, Conversions by Gender, Spend by Device

Scatter Plot → CPC vs CTR (Efficiency check)

Key Influencers Visual → Drivers of CTR / ROI

Filters (Slicers) → Date, Campaign, Region, Device, Age

📖 Insights & Recommendations

Mobile ads delivered the highest ROI % compared to desktop.

Age group 18–24 had the highest CTR but lower conversions → optimize landing pages.

Campaign CAMP002 was most cost-efficient with the best ROI.

Creative placements in Stories generated stronger engagement (likes & shares).

Recommendations:

Reallocate budget to high-ROI campaigns.

Improve targeting for older demographics.

Focus ad creatives for Mobile & Stories placements.

🎯 Deliverables

✅ Interactive Power BI Dashboard (.pbix)

✅ PDF Report with insights

✅ Screenshots of dashboard

✅ LinkedIn post about completion
