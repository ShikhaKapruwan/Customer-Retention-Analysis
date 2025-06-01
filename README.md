# Customer-Retention-Analysis
RFM-Based Customer Retention Analysis using Excel and Power Bi

## Overview
This Customer Retention Analysis project leverages RFM segmentation to categorize customers based on their transaction history. The dataset was cleaned and prepared using Excel, and key insights were visualized through interactive dashboard in Power BI. The project includes a Business Requirements Document (BRD) and is hosted on Github as part of a portfolio to demonstrate analytical and visualization skills.

## Project Objective
The goal of this project is to identify and analyse customer retention patterns using RFM (Recency, Frequency, Monetary) segmentation. By leveraging Excel and Power BI, this analysis helps businesses understand customer behaviour, identify at-risk customers, and develop strategies to improve retention.

## Dataset Used
- <a href="https://github.com/ShikhaKapruwan/Customer-Retention-Analysis/blob/main/OnlineRetail_dataset_original.xlsx">Dataset</a>

##Tools Used
Excel- Data cleaning, pivot tables, RFM score calculation using Excel’s quartile.INC function
Power BI- Data Visualization, dashboard creation
Github- Project documentation & Presentation
MS Word- Business Requirements Document (BRD)

## 🚀 Workflow Overview
### 🧹 Excel- Data Cleaning & Preparation
•	Removed rows with missing or zero values in *UnitPrice* or *Quantity* to ensure data accuracy.
•	Created a new column to calculate *Revenue per customer* using the formula: UnitPrice × Quantity.

### 📊 2. Initial Data Analysis (Excel - Pivot Table)
- Built a pivot table to summarize key information:
•	*CustomerID*
•	*Order Frequency*
•	*Last Purchased Date*
•	*Total Revenue* per customer
•	This helped in building the RFM (Recency, Frequency, Monetary) model.

### 📈 3. RFM Segmentation 
•	Calculated *Recency* using the most recent purchase date as a reference.
•	Applied the *QUARTILE.INC* function to assign scores (1 to 4) for Recency, Frequency, and Monetary value.
•	Created a composite RFM score for each customer (e.g., 444, 131, etc.).
- Categorized customers into meaningful segments like:
•	Best Customers
•	Loyal Customers
•	At Risk
•	Lost Customers
•	Recent Customers
•	Need Attention

### 📊 4. Power Bi- Data Visualization 
•	Imported the cleaned RFM scores sheet into Power BI.
•	Changed data types where required (e.g., dates, numeric fields) to ensure correct visuals.
•	Designed an interactive dashboard to visualize:
•	Customer segments distribution
•	Revenue contribution by segment
•	KPIs for high-value customer retention
•	Ensured proper formatting, filters, and slicers to enhance usability and insight discovery

- <a href="https://github.com/ShikhaKapruwan/Customer-Retention-Analysis/commit/21090cdfb139cada2a4f43f474b53f2539735d88">View Dashboard</a>


