# Social Media User Behavior Analysis – Power BI Dashboard

# Project Overview

This project focuses on exploring **social media user behavior** through **interactive and insightful dashboards** built using **Power BI**. Without relying on complex algorithms or machine learning, this visualization project transforms raw data into a story of user engagement, content interaction, and activity trends.


# Objective

To visualize patterns of user engagement on social media platforms and uncover actionable insights that can help:
- Platform managers improve user experience
- Marketers target content more effectively
- Creators optimize their engagement strategies

# Dataset Summary

The dataset includes features such as:

- Total Posts  
- Likes Received  
- Comments Received  
- Shares  
- Time Spent Per Day  
- Active Days Per Month  
- Follower Count  
- Age & Gender  


# Data Preparation (Inside Power BI)

The dataset was cleaned and enhanced directly within **Power BI** using the following steps:

- **Data type adjustments** for numerical and text fields  
- **New calculated columns** to derive deeper insights:
  - `Engagement Rate = (Likes + Comments + Shares) / Follower Count`
  - `Activity Score = Time Spent Per Day * Active Days Per Month`
  - `Posting Efficiency = Total Posts / Time Spent Per Day`
  - `Age Groups` created using conditional logic for better demographic segmentation

# Dashboard Sections

### 1. **Overview**
A summary view showing total users, gender ratio, average engagement metrics, and time spent on the platform.

### 2. **User Engagement**
Charts and visuals comparing how much users interact through likes, comments, and shares. Helps identify highly active users vs. passive ones.

### 3. **Demographics**
Insights on age groups, gender distribution, and their impact on engagement and time spent online.

### 4. **Activity Trends**
Visual breakdown of posting frequency, time spent, and platform usage patterns — which users are consistent, and which are one-time browsers.

### 5. **Performance Ratios**
Highlighting how efficiently users turn time and effort into engagement — perfect for targeting power users or optimizing posting strategies.

---

## Key Insights

- Users aged 19–25 are the most active and receive higher engagement.
- More time spent on the platform doesn't always equal more engagement — quality of content matters.
- Posting frequency and follower count are not linearly related — engagement rate is a better metric.

---

## Tools Used

- Microsoft Power BI (Visualization & Calculated Columns)
- CSV File Handling
- DAX for Column Calculations

