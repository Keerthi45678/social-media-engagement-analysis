# 🚀 Social Media Engagement Analysis

**Discover the patterns behind social media engagement with SQL + Python!** 💡  

This project demonstrates an **end-to-end data analysis workflow**: from extracting and cleaning data using **SQL**, to analyzing metrics and creating **actionable visualizations** in Python. It focuses on understanding **what content performs best, which users drive engagement, and how engagement varies across platforms and time**.  

---

### 🎯 Project Goal
The aim is to provide insights that can help content creators, social media managers, or businesses understand **audience behavior and content performance**:  
- 🏆 Identify **top-performing posts**  
- 👥 Highlight **most engaging users**  
- 🌐 Analyze **platform-wise distribution of engagement**  
- 📅 Detect **temporal trends** to optimize posting schedules  

---

### 🗂 Dataset Overview
The project uses CSVs generated from SQL queries on the `social_db`:  

- **users_data.csv** – User attributes: language, activity hours, followers, category, active time bucket  
- **posts.csv** – Post details: content type, platform, likes, comments, shares, engagement score, posting day & month  
- **top_5_posts.csv** – Top posts based on engagement rate  
- **all_posts_engagement.csv** – Engagement metrics for all posts  
- **top_users_engagement.csv** – Average engagement rate per user  

> All datasets are **synthetic but realistic**, simulating typical social media user engagement.

---

### 📊 Key Insights & Visualizations

Here’s the **combined visualization** summarizing the analysis:

![Social Media Engagement](https://github.com/YOUR_USERNAME/social-media-engagement-analysis/blob/main/images/social_media_charts.png)

**What this shows:**  
- 🏅 **Top 5 Posts:** These posts have the **highest engagement rate**, showing content types or topics that resonate with the audience.  
- 🌟 **Top 5 Users:** Identifies influencers or highly active users who consistently generate interaction.  
- 📊 **Platform Distribution:** Highlights which platform dominates engagement, helping businesses **focus marketing efforts**.  
- 🗓 **Avg Engagement by Day:** Reveals peak days for posting to maximize reach and interaction.  

**Why it matters:**  
Understanding these trends helps:  
- Content creators plan **optimized posting schedules**  
- Social media managers target **high-engagement content types**  
- Brands identify **key user segments** to engage with  

---

### 🛠 Technologies Used
- **SQL:** Efficient extraction and aggregation of engagement metrics; CTEs, joins, group by, and safe calculations using `NULLIF`  
- **Python:** Data analysis and visualization with **Pandas**, **Seaborn**, and **Matplotlib**  
- **CSV Files:** Exported from SQL queries for clean, structured analysis  



