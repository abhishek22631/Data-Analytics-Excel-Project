# 🍎 Apple Social Media Analytics – Excel Project

## 📌 Project Overview

This project focuses on analyzing Apple’s social media performance across major platforms using Microsoft Excel. The objective was to transform raw social media, campaign, and ad-spend data into actionable business insights that can support data-driven marketing decisions.

The analysis covers engagement trends, platform effectiveness, content and hashtag strategy, campaign performance, and follower growth patterns.

---

## 🎯 Business Objectives

* Identify which social media platforms drive the highest engagement
* Understand how different content types and hashtags perform
* Measure campaign effectiveness and engagement uplift
* Analyze follower growth and retention trends
* Provide actionable recommendations to improve Apple’s social media strategy

---

## 🗂 Dataset Description

The project uses three Excel datasets:

### 1️⃣ Posts Dataset

Used for content-level performance analysis.

**Key fields:**
Post_ID, Platform, Date, Content_Type, Hashtags, Likes, Shares, Comments, Clicks, Impressions

---

### 2️⃣ Engagement Summary Dataset

Used for platform-level trends, follower growth, and ad spend analysis.

**Key fields:**
Week_Start_Date, Platform, New_Followers, Unfollows, Total_Followers, Engagement_Rate, Ad_Spend

---

### 3️⃣ Campaign Metadata Dataset

Used to analyze campaign performance and ROI.

**Key fields:**
Campaign_Name, Start_Date, End_Date, Objective, Total_Spend, Impressions, Engagement_Uplift

---

Dataset link: https://docs.google.com/spreadsheets/d/1FicvoxOk9lrR40og4HC8AmGN5EFGqKCRB_Tq47Ypcvo/edit?usp=sharing

## 🛠 Tools & Techniques Used

* Microsoft Excel
* Pivot Tables & Pivot Charts
* Calculated Fields & Excel Formulas
* Text to Columns (Hashtag splitting)
* Sorting, Filtering, and Ranking
* Data Visualization (Column charts, Line charts, Scatter plots)

---

## 📊 Analysis Breakdown

### 🔹 Task 1: Data Preprocessing & Cleaning

* Checked and validated duplicate records
* Standardized text fields and date formats
* Formatted numeric and currency columns
* Split hashtags into separate values for analysis

---

### 🔹 Task 2: Engagement Analysis

* Calculated Engagement Rate using:

  ```
  (Likes + Shares + Comments) / Impressions
  ```
* Identified Top 10 posts by engagement rate
* Analyzed engagement by content type and platform
* Evaluated average clicks per hashtag

---

### 🔹 Task 3: Platform Performance Analysis

* Compared engagement rates across platforms
* Calculated follower growth rate per platform
* Visualized engagement trends using charts
* Provided strategic recommendations on platform prioritization

---

### 🔹 Task 4: Hashtag & Content Strategy

* Identified most frequently used hashtags
* Compared average engagement by hashtag
* Analyzed content performance across formats:

  * Videos
  * Images
  * Carousels
  * Tweets
* Determined best-performing content types per platform

---

### 🔹 Task 5: Campaign Effectiveness

* Calculated total and average impressions, likes, and clicks per campaign
* Measured engagement uplift during vs. before campaigns
* Used a separate worksheet (**Campaign Effectiveness Task 5.2**) for comparison

**Note on methodology:**
For each campaign, average engagement during the campaign period is calculated using all posts marked as *During*, and repeated for *Before* posts to enable side-by-side comparison. The same logic applies in reverse for *During* posts.

---

### 🔹 Task 6: Follower Retention & Loyalty

* Visualized weekly follower growth per platform
* Identified peak follower gain periods
* Explored moving averages for trend smoothing
* Analyzed the relationship between ad spend and follower growth

---

## 📈 Key Insights

* Twitter recorded the highest engagement rate
* Videos achieved the strongest overall engagement
* Tweets generated the most shares, clicks, and impressions
* #AppleEvent was the most frequently used hashtag
* iPhone 16 Launch campaign showed the highest engagement uplift
* Specific weeks showed significant spikes in follower growth

---

## 💡 Recommendations

* Prioritize Twitter while maintaining a multi-platform presence
* Increase focus on video-based content (especially short-form videos)
* Replicate strategies from high-performing campaigns
* Use campaign timing and hashtag strategy to maximize uplift

---

## 🚧 Limitations

* Moving average analysis was partially explored
* Advanced correlation analysis could be enhanced using BI tools
* Results depend on the available time period and dataset scope

---

## 👤 Author

**Abhishek Chakraborty**
Aspiring Data Analyst | Excel | Data Analytics | Visualization

---

⭐ *If you found this project insightful, feel free to explore or provide feedback!*








