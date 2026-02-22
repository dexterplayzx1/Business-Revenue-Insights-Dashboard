# Retail Sales Performance Analytics

## Project Overview

This project presents an end-to-end retail sales performance analysis using international transactional data. The objective is to transform raw sales records into actionable business insights that support strategic and operational decision-making.

The analysis evaluates revenue trends, product performance, geographic contribution, customer behavior, and operational sales patterns through structured analytics and dashboard visualization.

---

## Project Objectives

- Analyze overall sales performance and revenue trends over time  
- Identify top-performing products contributing to total revenue  
- Evaluate country-wise revenue contribution  
- Analyze customer purchasing behavior  
- Identify seasonal and hourly sales patterns  
- Provide data-driven recommendations for business growth  

---

## Dataset Description

The dataset consists of over 500,000 international retail transactions recorded between 2010 and 2011.

### Key Attributes

- Invoice Number  
- Stock Code  
- Product Description  
- Quantity Sold  
- Invoice Date  
- Unit Price  
- Customer ID  
- Country  

The dataset represents international e-commerce activity across multiple countries including the United Kingdom, France, Germany, Netherlands, Australia, and others.

---

## Tools and Technologies Used

- Power BI – Dashboard development and KPI visualization  
- Python (Pandas, Matplotlib) – Data cleaning and exploratory analysis  
- Microsoft Excel – Processed dataset preparation  

---

## Data Cleaning and Preparation

The following preprocessing steps were performed:

- Removed missing values in critical fields (Description, CustomerID)  
- Removed cancelled transactions  
- Removed negative and zero quantities  
- Converted date columns to appropriate datetime format  
- Created derived fields including:
  - Year  
  - Month  
  - Hour  
  - Revenue (Quantity × Unit Price)

These steps ensured that the dataset reflects only valid and completed sales transactions.

---

## Key Performance Indicators (KPIs)

- Total Revenue: 8.30 Million  
- Total Orders: 22,000+  
- Total Customers: 4,000+  
- Average Order Value (AOV): 374  

These KPIs provide a high-level performance snapshot of the business, highlighting overall scale, customer base strength, and revenue efficiency.

---

## Key Insights

### Revenue Trend Analysis

- Clear seasonal growth patterns observed  
- Significant revenue spike during Q4 (September–November)  
- November recorded the highest monthly revenue  
- Slight decline in December following peak season  

Business Interpretation:  
The business experiences strong holiday-driven seasonality. Inventory planning and marketing initiatives should be intensified before peak months to maximize revenue capture.

---

### Product Performance

- A limited number of products generate a significant share of total revenue  
- Revenue distribution follows a Pareto-like pattern  

Business Interpretation:  
High-performing products should be prioritized in marketing campaigns and inventory management strategies.

---

### Country-Level Revenue Analysis

- The United Kingdom contributes the majority of total revenue  
- Other European markets contribute smaller but meaningful shares  

Business Interpretation:  
Revenue concentration in a single country introduces geographic risk. Expansion efforts in high-performing international markets could improve diversification and long-term stability.

---

### Customer Contribution Analysis

- A small group of customers contributes a substantial portion of revenue  

Business Interpretation:  
Customer retention programs, loyalty incentives, and personalized marketing strategies can significantly improve customer lifetime value and recurring revenue.

---

### Sales by Hour Analysis

- Revenue peaks during mid-day hours (approximately 11 AM to 1 PM)

Business Interpretation:  
Time-based promotions during peak hours may further enhance sales performance.

---

## Business Recommendations

### Revenue Growth Strategy
- Increase marketing investment prior to Q4 seasonal peaks  
- Bundle lower-performing products with top-selling items  

### Market Expansion Strategy
- Strengthen presence in high-performing international markets  
- Reduce reliance on a single dominant country  

### Customer Retention Strategy
- Implement loyalty programs for high-value customers  
- Launch personalized promotional campaigns  

### Operational Optimization
- Align inventory planning with seasonal demand patterns  
- Utilize hourly sales data to design targeted promotional windows  

---

## Dashboard Preview

Screenshots/Dashboard.png


---

## Future Enhancements

- Implementation of time-series sales forecasting  
- Customer segmentation using RFM analysis  
- Deployment on cloud-based BI platforms  
- Real-time data integration  

---

## Author

Adithya [Full Name]  
B.Sc (Hons) Data Science & Analytics  
M S Ramaiah University of Applied Sciences  

---

## References

- Microsoft Power BI Documentation  
- pandas Documentation  
- Matplotlib Documentation  
- Kaggle – Online Retail Dataset  
