# :rocket: Meta Ad Performance Analysis – Instagram & Facebook Power BI Dashboard

This Power BI solution delivers a complete analytical system for tracking **Meta ad campaign performance** across **Facebook and Instagram**.  
It helps marketing teams and data analysts understand **reach, engagement, conversions, audience behavior, and budget efficiency** in a single interactive dashboard.
---
[![AD_EVENTS](https://img.shields.io/badge/AD_EVENTS-Download-green?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://github.com/satyashubhamjha/Instagram-and-Facebook-Power-Bi-Dashboard/blob/main/ad_events.csv)

[![ADS](https://img.shields.io/badge/ADS-Download-green?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://github.com/satyashubhamjha/Instagram-and-Facebook-Power-Bi-Dashboard/blob/main/ads.csv)

[![CAMPAIGN](https://img.shields.io/badge/CAMPAIGN-Download-green?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://github.com/satyashubhamjha/Instagram-and-Facebook-Power-Bi-Dashboard/blob/main/campaigns.csv)

[![USERS](https://img.shields.io/badge/USERS-Download-green?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://github.com/satyashubhamjha/Instagram-and-Facebook-Power-Bi-Dashboard/blob/main/users.csv)

---


<img width="1344" height="768" alt="Gemini_Generated_Image_5smrhm5smrhm5smr" src="https://github.com/satyashubhamjha/Instagram-and-Facebook-Power-Bi-Dashboard/blob/main/Facebook%20And%20Instagram%20Analysis.png" />

---



### 🎯 Business Problem & Objective

The business needs a **performance tracking report** for advertising campaigns running on **Facebook and Instagram**.  
The dashboard must provide clear visibility into:

- 📢 **Reach** – How often ads are shown  
- 👆 **Engagement** – How users interact with ads  
- 🛒 **Conversions** – How many users complete purchases  
- 💸 **Budget Utilization** – How efficiently the money is being spent  

This will help the marketing team:

- ✅ Identify the **most effective platform** (Facebook vs Instagram)  
- ✅ Track **campaign ROI** and optimize **budget allocation**   
- ✅ Understand **audience engagement patterns** and improve targeting  

---

### PROBLEM STATEMENTS:-

---

### ⬇️ (KPIs) Requirements For Summary Dashboard:-

:sparkles: **Impressions** –  
Total number of times ads were displayed to users. This represents **overall reach** of all campaigns.

:sparkles: **Clicks** –  
Total number of times users clicked on the ads. Used to measure **engagement intent** and ad attractiveness.

:sparkles: **Shares** –  
Total number of times ads were shared by users. Indicates **viral/organic amplification** beyond paid reach.

:sparkles: **Comments** –  
Total comments left on ads. Helps understand **user sentiment and feedback** on creatives and messaging.

:sparkles: **Purchases (Conversions)** –  
Total number of purchases that occurred after users interacted with ads. Represents **bottom-of-funnel success**.

:sparkles: **Engagements** –  
Combined total of clicks, shares and comments. Shows **overall interaction volume** with ads.

:sparkles: **CTR (Click-Through Rate)** –  
Percentage of impressions that resulted in clicks. Measures **ad effectiveness** in driving traffic.

:sparkles: **Engagement Rate** –  
Percentage of impressions that resulted in any engagement (click, share, comment). Reflects **overall content appeal**.

:sparkles: **Conversion Rate** –  
Percentage of clicks that resulted in purchases. Evaluates **funnel efficiency** from interest to action.

:sparkles: **Purchase Rate** –  
Percentage of impressions that resulted in purchases. Shows how well **reach is converted into revenue**.

:sparkles: **Total Budget** –  
Total spend allocated across all campaigns. Used for **cost and ROI analysis**.

:sparkles: **Average Budget per Campaign** –  
Average budget assigned to each campaign. Helps compare **budget distribution vs performance** across campaigns.

---

## 📊 Performance KPI Overview

| 📌 KPI | 📖 Definition | 🧮 Formula (Conceptual) | 🎯 Purpose |
|-------|---------------|-------------------------|-----------|
| 👁️ **Impressions** | Number of times ads were shown | Count of `event_type = Impression` | Measure reach |
| 👆 **Clicks** | Number of times users clicked ads | Count of `event_type = Click` | Measure engagement intent |
| 🔁 **Shares** | Number of times ads were shared | Count of `event_type = Share` | Viral engagement |
| 💬 **Comments** | Number of comments on ads | Count of `event_type = Comment` | User sentiment & feedback |
| 🛒 **Purchases** | Number of purchases driven by ads | Count of `event_type = Purchase` | Conversions |
| 🎯 **Engagements** | Total interactions | Clicks + Shares + Comments | Engagement volume |
| 📈 **CTR** | % of impressions that became clicks | (Clicks ÷ Impressions) × 100 | Ad effectiveness |
| 💥 **Engagement Rate** | % of impressions that became engagements | (Engagements ÷ Impressions) × 100 | Overall ad appeal |
| 🔄 **Conversion Rate** | % of clicks that became purchases | (Purchases ÷ Clicks) × 100 | Funnel efficiency |
| 🧾 **Purchase Rate** | % of impressions that became purchases | (Purchases ÷ Impressions) × 100 | Conversion from reach |
| 💰 **Total Budget** | Total spend across campaigns | Σ `campaigns.total_budget` | Cost & budget analysis |
| 📊 **Avg. Budget / Campaign** | Average budget per campaign | Total Budget ÷ Campaign Count | Budget distribution |

---

## 📊 Instagram Dashboard

[![Dashboard Button](https://img.shields.io/badge/VISUALIZE%20NOW-Meta%20Ads%20Dashboard-blueviolet?style=for-the-badge&logo=powerbi)](https://github.com/satyashubhamjha/Instagram-and-Facebook-Power-Bi-Dashboard/blob/main/Instagram%20Dashboard.png)

---

## 📊 Facebook Dashboard

[![Dashboard Button](https://img.shields.io/badge/VISUALIZE%20NOW-Meta%20Ads%20Dashboard-blueviolet?style=for-the-badge&logo=powerbi)](https://github.com/satyashubhamjha/Instagram-and-Facebook-Power-Bi-Dashboard/blob/main/Facebook%20Dashboard.png)

### ⬇️ (KPIs) Requirements For Overview Dashboard (Charts):-

:sparkles: **Target Gender – Donut Chart**  
Visualize performance split by **target gender** (e.g., Male, Female, Other) using a donut chart.  
This chart should support dynamic metrics (Impressions, Clicks, Purchases, etc.) to identify **which gender segment contributes most** to the selected KPI.

:sparkles: **Target Age Group – Bar Chart**  
Display engagement and conversions across **age groups** (e.g., 18–24, 25–34, 35–44, etc.).  
Helps highlight **which age segment responds best** to campaigns and where to focus ad spend.

:sparkles: **Country Analysis – Map Chart**  
Use a **filled / bubble map** to show performance by **country**.  
Bubble size or color intensity represents the selected metric, giving a **geographical view of reach and engagement**.

:sparkles: **Calendar Month – Calendar Heat Map**  
Plot impressions/engagements by **date** using a calendar-style heat map.  
Darker shades show higher activity, helping detect **seasonality, peak campaign days, and low-activity periods**.

:sparkles: **Weekly Trend – Stacked Column by Ad Type**  
Weekly stacked column chart with:  
- X-axis → Week number  
- Stacks → **Ad types** (Image, Video, Carousel, Story)  
- Y-axis → Selected metric  
Used to compare **how different ad formats contribute across weeks**.

:sparkles: **Hourly Trend – Area Chart**  
Area chart showing activity by **hour of day (0–23)**.  
Reveals **when users are most active** (e.g., afternoon/evening peaks) so campaigns can be scheduled for **maximum impact**.

:sparkles: **Ad Type vs Platform – Matrix**  
Matrix visual with:  
- Rows → Ad Types  
- Columns → Platforms (Facebook vs Instagram)  
- Values → Selected metric  
This gives a side-by-side comparison of **which ad format works best on each platform**.

---

## 🧱 Data Model – Tables Overview

The dataset follows a **star schema**, with one fact table and three dimension tables:

| 🧩 Table | 📂 Role | 📝 Key Details |
|---------|--------|----------------|
| 📊 **ad_events** | Fact Table | Stores every event (Impression, Click, Share, Comment, Purchase) with timestamps, user, and ad references. Basis for all KPIs. |
| 🎨 **ads** | Dimension | Ad-level metadata – ad type, platform (Facebook/Instagram), targeting (gender, age group, interests), campaign link. |
| 🎯 **campaigns** | Dimension | Campaign-level details – name, start/end date, duration, total budget; used for cost and ROI analysis. |
| 👥 **users** | Dimension | User demographics – gender, age, country, location, interests; used for **audience segmentation and targeting accuracy** analysis. |

---

## 🧠 Meta Ads Overall Analysis – Mind Map

<p align="center">
  <img src="https://github.com/satyashubhamjha/Instagram-and-Facebook-Power-Bi-Dashboard/blob/main/Mind%20Map%20Of%20Fcebook%20And%20Instagram%20Analysis.png" width="650" />
</p>

> **Figure:** Mind map covering the overall Meta Ads analysis – KPIs, audience segments, platforms, ad types, geography, time trends, and budget optimization.

---

## 🛠️ Tools Used

[![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
[![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://github.com/satyashubhamjha/Instagram-and-Facebook-Power-Bi-Dashboard/blob/main/Meta_Ads_Dashboard.pbix)
[![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)](https://github.com/satyashubhamjha)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://github.com/satyashubhamjha)

---

> 💡 **How to Use This Project**  
> 1️⃣ Download the dataset files and Power BI report.  
> 2️⃣ Open the `.pbix` file in Power BI Desktop.  
> 3️⃣ Refresh the data and explore KPIs, filters, and interactive visuals.  
> 4️⃣ Use the dashboard insights to optimize **targeting, timing, ad formats, and budget allocation**.

