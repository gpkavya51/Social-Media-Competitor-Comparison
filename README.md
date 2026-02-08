📊 Social Media Competitor Comparison Dashboard
🧭 Project Overview

The Social Media Competitor Comparison Dashboard is a Business Intelligence solution built using Power BI to analyze and compare social media performance across multiple companies and platforms.

The dashboard helps marketing teams, analysts, and businesses evaluate competitor strategies using engagement metrics, follower trends, content performance, and reach analysis.

🎯 Business Objectives

Compare social media performance across competitors

Track engagement rate and audience growth

Analyze content strategy effectiveness

Measure reach vs engagement performance

Support data-driven digital marketing decisions

🛠️ Tech Stack

Power BI Desktop – Dashboard Development

Power Query – Data Cleaning & Transformation

DAX (Data Analysis Expressions) – Measure Creation

Excel Dataset – Data Source

📂 Dataset Details

The dataset includes:

Company Name (BEL, Infosys, TCS, UpdAte, Wipro)

Platform (YouTube, Instagram, etc.)

Followers Count

Likes, Comments, Shares

Reach Metrics

Engagement Metrics

Post Level Performance Data

🧩 Data Modeling Approach
✔ Fact Table

Social Media Post Performance Data

✔ Dimension Tables

Company

Platform

Content Type

✔ Relationship Design

One-to-Many relationships

Optimized for slicers and cross filtering

📐 DAX Measures Used
🔹 Total Followers
Total Followers = SUM(Data[Followers])

🔹 Average Engagement Rate
Avg Engagement Rate = AVERAGE(Data[Engagement Rate])

🔹 Average Likes Per Post
Avg Likes per Post = AVERAGE(Data[Likes])

🔹 Total Posts
Total Posts = COUNT(Data[Post ID])

📊 Dashboard Components
🔷 KPI Summary Cards

Total Followers → 38M

Average Engagement Rate → 4.30

Average Likes/Post → 14.59K

Total Posts → 100

Top Company by Engagement Rate → BEL

🔷 Followers by Company (Trend Analysis)

Insight:
Helps identify which competitor has the largest audience base.

🔷 Engagement Rate by Company

Insight:
Shows which company creates the most engaging content.

🔷 Content Type Distribution (Pie Chart)

Insight:
Analyzes content mix strategy across competitors.

🔷 Engagement vs Reach Scatter Plot

Insight:
Identifies high-performing companies with strong reach and engagement.

🔷 Company Performance Comparison (Bar Chart)

Metrics Compared:

Total Engagement

Total Likes

Total Comments

🔷 BEL Instagram Post Performance Table

Metrics Included:

Likes

Reach

Comments

Shares

Avg Engagement per Post

Use Case:
Micro-level performance analysis.

📈 Key Business Insights

BEL shows strong engagement performance

High reach does not always mean high engagement

Content mix distribution is balanced across companies

Instagram shows strong interaction metrics

Engagement efficiency varies by company strategy

⚡ Performance Optimization

Removed unused columns

Optimized data types

Used Measures instead of calculated columns

Optimized visual interactions

🚀 How to Use

Download repository

Open .pbix file in Power BI Desktop

Refresh dataset

Use slicers to filter by company or platform

📂 Project Structure
📦 Social-Media-Competitor-Comparison
 ┣ 📊 Social Media Competitor Comparison.pbix
 ┣ 📁 Dataset
 ┣ 📁 Dashboard Screenshots
 ┗ 📄 README.md

🔮 Future Enhancements

Real-time Social Media API Integration

Sentiment Analysis using NLP

Power BI Service Dashboard Deployment

Automated Data Refresh Pipeline

📜 License

This project is for educational and portfolio demonstration purposes.
