# FUTURE_DS_02

📊 Facebook Ad Campaign Performance Dashboard – Power BI

This Power BI project was built as part of **Task 2** in the **Data Science & Analytics Internship at Future Interns*. 
It focuses on analyzing real-world **Facebook ad campaign** data to evaluate performance, identify high-engagement content, and generate strategic marketing insights.

🧠 Project Overview
The goal was to create an **interactive Power BI dashboard** that helps marketers:
• Evaluate key campaign metrics (CTR, ROI, Spend, Conversions)
• Identify top-performing posts and audiences
• Uncover patterns by demographics
• Generate actionable recommendations

📄 Dashboard Pages

1. Campaign Performance Overview
• Displays high-level KPIs like *CTR*, *Conversions*, *Spend*, and *ROI*
• Uses card visuals, bar charts, and slicers to summarize performance

2. Post-Level Engagement Analysis
• Deep dive into individual ad performance using `ad_id`
• Visuals show impressions, clicks, CTR, and ROI per post
• Identifies the *highest ROI ad*

3. Audience Insights
• Analyzes how *age group* and *gender* impact conversions and ROI
• Matrix tables and bar charts highlight the most responsive segments


🧮 Key DAX Measures
• CTR = `Clicks / Impressions`
• Revenue = `Approved Conversions * 50` (fixed assumption)
• ROI = `(Revenue - Spend) / Spend`
• Highest ROI ad_id = Dynamic calculation to find top-performing ad

🛠️ Tools Used
• Power BI Desktop – Dashboard design & visual analytics
• Power Query – Data cleaning & type formatting
• DAX – Calculated fields & KPIs
• Excel – Preprocessing, initial exploration

💡 Learnings
• Importance of using **DAX measures** over calculated columns for efficiency
• Designing multi-page dashboards with user-friendly navigation
• Linking business goals to measurable ad metrics like CTR & ROI
• Working with assumptions in absence of complete real-world data

📈 Business Value
This dashboard helps marketers:
• Focus budget on high-ROI age groups
• Optimize ad creatives using CTR patterns
• Time campaigns more effectively with demographic insights

🔗 Preview
Campaign Performance Overview
![Campaign Performance Overview](https://github.com/user-attachments/assets/e757f86e-9aa6-49a1-8397-90f59e1cfc6f)

Post-Level Engagement Overview
![Post-Level Engagement Overview](https://github.com/user-attachments/assets/e976171a-b5f0-4b05-906b-1df3e5ec140c)

Audience Insights
![Audience Insights](https://github.com/user-attachments/assets/a9a02e51-0353-4a6d-9e2b-544755413317)
