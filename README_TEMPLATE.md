# Customer Shopping Behavior Analysis (End-to-End Data Analytics Project)
---


## Table of Contents
1. [Project Overview](#1-project-overview)
2. [Business Background](#2-Business-Background)
3. [Business Problem](#3-Business-Problem)
4. [Dataset](#4-Dataset)
5. [Tools & Technologies](#5-Tools--Technologies)
6. [Dashboard](#6-Dashboard)
7. [Key Insights](#7-Key-Insights)
8. [Business Recommendations](#8-Business-Recommendations)
9. [Challenges & Limitations](#9-Challenges--Limitations)
14. [Author](#14-author)

---

## 1. Project Overview

This end-to-end data analytics project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The objective was to transform raw customer data into actionable business insights that help improve customer engagement, optimize marketing strategies, and support data-driven decision-making.

The project demonstrates the complete analytics workflow—from data cleaning and preparation in Python, business analysis using SQL, and interactive dashboard development in Power BI. The final deliverables include a comprehensive report, business recommendations, and a well-structured GitHub repository containing all project files.

---

## 2. Business Background

The retail industry is becoming increasingly customer-driven, requiring businesses to understand purchasing behavior in order to remain competitive. Customer demographics, shopping preferences, promotional campaigns, and seasonal trends all influence purchasing decisions.

By analyzing customer shopping data, retailers can better understand what drives customer engagement, identify high-value customer segments, improve product positioning, and develop more effective marketing strategies.

---

## 3. Business Problem

A leading retail company observed changing purchasing patterns across customer demographics, product categories, and shopping channels. Management wanted to better understand which factors influence purchasing decisions, customer loyalty, and repeat purchases.

The primary business question was:

How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?


## 3. Objectives

<!--
  Write objectives that are specific enough to succeed or fail.
  Use action-oriented verbs: Identify, Determine, Quantify, Build, Evaluate.

  WHAT GOOD LOOKS LIKE:
  ✅ "Determine whether customer churn rate correlates with support ticket volume."
  ✅ "Identify the top three revenue-driving product categories across all regions."
  ✅ "Build a reproducible pipeline that ingests and cleans daily sales exports."

  WHAT TO AVOID:
  ❌ "Explore the data."
  ❌ "Gain insights."
  ❌ "Understand trends."
  (These can't fail - which means they can't succeed either.)
-->

- **Primary Objective:** [The main thing you set out to do]
- **Secondary Objective 1:** [Supporting goal]
- **Secondary Objective 2:** [Supporting goal]
- **Secondary Objective 3:** [Remove if not applicable]

> 💡 *Every analysis decision in this project traces back to one of these objectives.*

---

## 3. Project Scope & Tools


### Tools & Technologies

<!--
  List only what you actually used on this project.
  This is not your skills section - it's the project's technical context.
-->

| Tool | Purpose|
|----------|-------------|
| Python (Pandas) | [Data Cleaning & Preparation] |
| MySQL | [Data Storage & Business Analysis] |
| SQL | [Business Queries & Insight Generation] |
| Power BI| [Dashboard Development & Data Visualization] |

---

## 4. Methodology
### 1. Data Preparation (Python)
The raw dataset was cleaned and transformed to ensure data quality before analysis.

### Data Cleaning
- Imported the dataset using Pandas
- Performed data exploration using .info() and .describe()
- Identified missing values
- Imputed missing Review Rating values using the median rating within each product category
- Standardized column names to snake_case
- Checked for duplicate and redundant information
- Removed the promo_code_used column after confirming it duplicated the discount information
  
### Feature Engineering

Created new variables to improve analysis:

- age_group for customer segmentation
- purchase_frequency_days for analyzing buying frequency
  
### Database Integration

- After cleaning, the dataset was connected to PostgreSQL, where the transformed data was loaded for structured SQL analysis.

### 2. Data Analysis (SQL)

SQL was used to answer important business questions and identify customer behavior patterns.

The analysis included:

- Revenue by gender
- High-spending customers using discounts
- Top-rated products
- Purchase comparison by shipping type
- Subscriber vs. non-subscriber performance
- Discount-dependent products
- Customer segmentation
- Top-performing products within each category
- Relationship between repeat purchases and subscriptions
- Revenue contribution by age group
  
### 3. Dashboard Development (Power BI)

An interactive Power BI dashboard was developed to communicate insights through intuitive visualizations.

The dashboard enables stakeholders to:

- Monitor customer demographics
- Analyze purchasing trends
- Compare subscription performance
- Track revenue across customer segments
- Evaluate discount effectiveness
- Identify top-performing products
- Explore seasonal purchasing patterns

  ## Key Insights

  The analysis revealed several important business insights:

- Customer spending varies across different demographic groups, highlighting opportunities for targeted marketing.
- Subscription customers generate stronger long-term value and contribute significantly to overall revenue.
- Certain products rely heavily on discounts to drive purchases, indicating potential pricing optimization opportunities.
- Top-rated products consistently perform well and should be prioritized in promotional campaigns.
- Repeat customers are more likely to subscribe, emphasizing the importance of customer retention strategies.
- Revenue contribution differs across age groups, enabling more focused customer segmentation.
- Shipping preferences influence purchase behavior, with differences observed between Standard and Express shipping customers.
  
## Business Recommendations

Based on the analysis, the following recommendations were made:

### Increase Subscription Adoption

Promote exclusive subscriber benefits such as discounts, early product access, and loyalty rewards to encourage customer retention.

### Strengthen Customer Loyalty

Implement loyalty programs that reward repeat purchases and encourage customers to progress from New to Returning and ultimately Loyal customer segments.

### Optimize Discount Strategy

Review discount policies to ensure promotional campaigns increase sales while maintaining healthy profit margins.

### Promote High-Performing Products

Feature top-rated and best-selling products more prominently in marketing campaigns and promotional activities.

### Personalize Marketing Campaigns

Use customer demographics, purchasing behavior, and age groups to create targeted marketing strategies that improve customer engagement.

### Improve Shipping Experience

Leverage insights from customer shipping preferences to optimize delivery options and enhance the customer experience.

## Challenges & Limitations

### Challenges
Missing values in the Review Rating column required appropriate imputation.
Some variables contained redundant information that needed validation before removal.
Customer segmentation required additional feature engineering beyond the original dataset.

### Limitations
The dataset represents historical transactions and may not capture evolving customer behavior over time.
Customer lifetime value could not be fully measured due to the absence of long-term transaction history.
External factors such as economic conditions and competitor activities were not included in the analysis.

---

## 14. Author

**[Thene Tlotliso]**
[Your role or title - current or target]

- 🔗 [LinkedIn URL]
- 💼 [Portfolio or GitHub profile URL]
- 📧 [thenetlotliso@gmail.com]

---

*Last updated: [July 2026]*

