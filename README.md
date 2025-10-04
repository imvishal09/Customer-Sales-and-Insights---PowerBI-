🧠 Customer Sales and Loyalty Insights Dashboard

📊 Overview

This Power BI dashboard provides a detailed analysis of customer purchasing behaviour, product category performance, and loyalty patterns using the Customer Personality Analysis dataset.
It highlights how spending, recency, and demographics influence customer value, helping identify high-value customers and guiding strategies for customer retention and targeted marketing.

🎯 Objectives
	•	Understand total and average revenue performance.
	•	Segment customers by spending behaviour (Low, Medium, High, VIP).
	•	Analyse product category sales to identify top-performing items.
	•	Examine channel preferences (Web, Store, Catalogue, Deals) across age groups.
	•	Explore recency versus spend to evaluate customer loyalty and retention risks.

🍷 Product Category Sales Distribution

A tree map visualising the contribution of each product category (Wine, Meat, Gold, Sweets, etc.) to overall sales.

Insight: Identifies which product categories drive the most revenue and where to focus sales and marketing efforts.


👥 Customer Distribution by Value Segment

A donut chart displaying the proportion of customers in each spending segment — Low, Medium, High, and VIP.

Insight: Reveals the concentration of revenue among high-value customers, often following the 80/20 rule (where a small portion of customers generate most of the revenue).


🛒 Purchase Channel Preferences by Age

A stacked bar chart comparing purchasing channels — Catalogue, Deals, Store, and Web — across age groups.

Insight: Demonstrates generational differences in purchasing behaviour, supporting targeted campaign design and channel strategy optimisation.


💎 Total Spend vs Recency by Loyalty Segment

A scatter plot mapping Total Spend (Y-axis) against Recency (X-axis), segmented by Loyalty Category (Loyal, At Risk, Lost).

Insight:
	•	Loyal customers purchase frequently and spend more.
	•	At-risk customers have reduced recent activity but previously high spend.
	•	Lost customers show high recency and low engagement — opportunities for reactivation campaigns.


⚙️ Data Source and Preparation

Dataset: Customer Personality Analysis — Kaggle
Tool Used: Power BI Desktop

Data Preparation Steps:
	•	Cleaned and formatted data in Power Query.
	•	Unpivoted product category columns for flexible analysis.
	•	Created calculated columns for:
	•	TotalSpend — total spend per customer
	•	CustomerSegment — value-based segmentation
	•	LoyaltySegment — recency-based loyalty grouping


🚀 Key Insights
	•	A small group of loyal, high-value customers contributes disproportionately to total revenue.
	•	Wine and Meat are the highest-performing product categories.
	•	Older demographics prefer catalogue and store purchases, while younger groups engage more online.
	•	Recency analysis highlights retention opportunities through targeted loyalty campaigns.


🧩 Tools and Techniques
	•	Power BI Desktop for visualisation and report design
	•	DAX for calculated columns and performance metrics
	•	Power Query for data cleaning and transformation
	•	Data storytelling principles for visual communication
