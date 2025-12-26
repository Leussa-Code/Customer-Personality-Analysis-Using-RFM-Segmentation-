
# Customer-Personality-Analysis-Using-RFM-Segmentation-
This project provides a 360-degree view of customer demographics, purchasing behavior, channel preferences, and marketing responsiveness. RFM segmentation enables targeted decision-making,
while campaign analyses supports optimization of marketing spend.
# 1. Project Overview
This project focuses on conducting a Customer Personality Analysis using transactional, demographic, and behavioral data to support data‑driven marketing and customer relationship management decisions. 
The analysis was implemented in Power BI, leveraging Power Query for data preparation and DAX for advanced analytics and segmentation.

The primary objective is to segment customers based on their purchasing behavior and engagement levels, identify high‑value customers, and provide actionable insights for targeted marketing strategies.

# 2. Business Problem
The organization collects large volumes of customer data but lacks a structured approach to:

Understand customer demographics and behavior
Identify high‑value and at‑risk customers
Evaluate campaign effectiveness
Optimize marketing spend
Without segmentation, marketing campaigns are generic, less effective, and costly.

# 3. Dataset Description
The dataset contains customer‑level information across four major dimensions:

## 3.1 Demographic Data
Year_Birth
Education
Marital_Status
Income
Kidhome, Teenhome
## 3.2 Customer Engagement
Dt_Customer
Recency
NumWebVisitsMonth
NumDealsPurchase
## 3.3 Purchasing Behavior
MntWines
MntFruits
MntMeatProduct
MntFishProduct
MntSweetProduct
MntGoldProds
NumWebPurchase
NumCataloguePurchase
NumStorePurchase
## 3.4 Campaign Response
AcceptedCmp1–5
Response
Complain
# 4. Methodology
## 4.1 Data Preparation (Power Query)
The following transformations were applied:

Age calculated from Year_Birth
Age Groups created for demographic segmentation
Family Size derived from Kidhome and Teenhome
Marital status grouped into Single and Couple categories
Customer tenure calculated from Dt_Customer
Total Spending derived from product‑level spending
Data cleaning steps included:

Removal of invalid income values
Standardization of categorical fields
Validation of numeric ranges
## 4.2 Feature Engineering
Key analytical metrics were created using DAX:

Total Spending
Total Purchases
Average Spending per Customer
Deal Sensitivity Ratio
Campaign Acceptance Count
These features form the foundation for behavioral and value‑based segmentation.

# 5. RFM Analysis Framework
RFM (Recency, Frequency, Monetary) analysis was applied to evaluate customer value:

Recency (R): How recently a customer made a purchase
Frequency (F): How often a customer purchases
Monetary (M): How much a customer spends
Each metric was scored on a scale of 1–5 using DAX measures, and combined into an overall RFM Score.

Customer Segments Defined:
Champions
Loyal Customers
Potential Loyalists
At Risk
Lost Customers
# 6. Dashboard Design (Power BI)
The report consists of multiple interactive pages:

## 6.1 Customer Overview
KPI Cards: Total Customers, Avg Age, Avg Income, Avg Spending
Customer distribution by Age Group and Marital Category
## 6.2 Spending Behavior
Total Spending by Product Category
Average Spending by Income Band
Spending patterns by Family Size
## 6.3 Purchase & Channel Behavior
Purchases by Channel (Web, Store, Catalogue)
Web Visits vs Web Purchases scatter analysis
Deal sensitivity by segment
6.4 RFM & Segmentation
Segment distribution
Revenue contribution by segment
Recency vs Monetary scatter plot
## 6.5 Campaign Performance
Campaign acceptance rates
Spending comparison between responders and non‑responders
Impact of complaints on customer value
Slicers and tooltips were implemented to enhance interactivity and usability.

# 7. Key Insights
A small proportion of customers (Champions) contribute a significant share of total revenue
Wine and meat products are the primary revenue drivers across high‑value segments
Multi‑channel customers demonstrate higher engagement and spending
Deal‑sensitive customers purchase frequently but generate lower revenue
Customers who respond to campaigns show significantly higher average spending
# 8. Business Recommendations
Focus retention and loyalty programs on Champion and Loyal segments
Use personalized offers to convert Potential Loyalists into high‑value customers
Re‑engage At‑Risk customers using targeted campaigns
Optimize marketing spend by prioritizing high‑response customer segments
Improve customer service to reduce complaints and protect revenue
# 9. Tools & Technologies
Power BI
Power Query
DAX
Excel / CSV data sources
10. Conclusion
This project demonstrates the effective use of Power BI and DAX to transform raw customer data into meaningful business insights. By applying RFM segmentation and behavioral analysis, the organization can make informed decisions that enhance customer engagement, improve marketing ROI, and increase overall profitability.
