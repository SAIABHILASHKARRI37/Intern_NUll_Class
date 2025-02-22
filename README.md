# 📊 Twitter Analytics Dashboard

## 📌 Objective
This Power BI project analyzes Twitter engagement trends by developing interactive visualizations to track tweet performance, user interactions, and key engagement metrics. The dashboard applies advanced filtering techniques to extract meaningful insights from Twitter data.

## 📈 Key Features & Insights
- **Total Engagements**
- **Total Impressions**
- **Total Media Views**
- **Average Engagement Rate (%)**
- **Top 10 Tweets by Engagement Rate**
- **Comparison: Weekday vs. Engagement Rate**
- **Likes Rate, URL Click Rate, Retweet Rate, Profile Click Rate (Gauge Chart Visualization)**
- **Monthly Slicer for Trend Analysis**

## 📊 Implemented Visualizations

# **1️⃣ Engagement Rate & Impressions Analysis**

- Visualization: Line/Bar Chart
- Filters Applied:
  - Tweets posted between **01-01-2020** and **30-06-2020**
  - Impressions **≥ 100**
  - Likes **= 0**
  - Visible only between **3 PM - 5 PM IST**
#URL, Profile & Hashtag Clicks Analysis
- Visualization: Clustered Bar Chart
- Filters Applied:
  - Tweets categorized as:
    - **Tweets with Media**
    - **Tweets with Links**
    - **Tweets with Hashtags**
  - Tweets must have **at least one** interaction (URL Clicks, Profile Clicks, Hashtag Clicks)
  - Tweets must be posted on an **even-numbered date**
  - Tweet word count **> 40**
  - Visible only between **3 PM - 5 PM IST**
#Replies, Retweets, and Likes Comparison
- Visualization: Column Chart
- Filters Applied:
  - Tweets with **media engagements > median value**
  - Posted between **June - August 2020**
  - Visible **only between 3 PM - 5 PM IST and 7 AM - 11 AM IST**
  - Tweet date must be **odd-numbered**
  - Media views must be **even-numbered**
  - Tweet character count **> 20**
  - Tweets **containing the letter 'S' are removed**

