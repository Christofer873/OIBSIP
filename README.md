# OIBSIP - Oasis Infobyte Data Analytics Internship

This repository contains projects completed as part of the Oasis Infobyte Data Analytics Internship.

## Task 1 - EDA on Retail Sales Data

### Objective
Perform exploratory data analysis on a retail sales dataset to uncover sales patterns, customer behaviour, product performance, and actionable business insights.

### Tools
Python, pandas, NumPy, Matplotlib, Seaborn, and Jupyter Notebook.

### Analysis Performed
- Dataset inspection: shape, data types, and missing values
- Mean, median, mode, and standard deviation
- Monthly and quarterly sales trends
- Customer analysis by age group and gender
- Top 10 best-selling products
- Revenue by product category
- Correlation heatmap
- Average sales by age group
- Business recommendations and conclusion

### Key Insights
- Electronics generated substantially more revenue than the other product categories.
- Smartphones and tablets were among the leading products by quantity sold.
- Unit Price had the strongest positive correlation with Sales (0.79).
- Quantity had a moderate positive correlation with Sales (0.45).
- Age had almost no linear relationship with Sales (-0.03).
- The 18-25 age group had the highest average sales per transaction despite having fewer transaction records than older age groups.

### Business Recommendations
1. Maintain sufficient inventory and prioritize promotions for high-performing electronics.
2. Test targeted campaigns for the 18-25 customer segment to explore its revenue potential.
3. Test upselling higher-value products and product bundles to increase transaction value.

## Task 2 - Customer Segmentation Analysis

### Objective
Segment customers based on purchasing behaviour using Recency, Frequency, and Monetary (RFM) analysis and K-Means clustering.

### Tools
Python, pandas, NumPy, Matplotlib, Seaborn, scikit-learn, and Jupyter Notebook.

### Analysis Performed
- Inspected and cleaned transaction data
- Removed duplicates, missing customer IDs, returns/cancellations, and invalid prices
- Calculated transaction value using Quantity × Unit Price
- Built Recency, Frequency, and Monetary (RFM) features
- Standardized RFM features using StandardScaler
- Used the Elbow Method to select a reasonable number of clusters
- Applied K-Means clustering with 3 clusters
- Profiled and interpreted customer segments
- Visualized customer counts and cluster behaviour
- Developed segment-specific marketing recommendations

### Customer Segments
- **Regular Customers:** 315 customers; moderate recency, frequency, and spending.
- **High-Value Customers:** 49 customers; recent and frequent purchases with the highest average spending.
- **At-Risk Customers:** 36 customers; long purchase inactivity with relatively low frequency and spending.

### Marketing Recommendations
1. Retain High-Value Customers with loyalty rewards, exclusive offers, and personalized recommendations.
2. Encourage Regular Customers with bundles, limited-time offers, and loyalty programs.
3. Re-engage At-Risk Customers with personalized reminders and targeted comeback offers.

### Project Structure
OIBSIP
- README.md
- Task1_EDA_Retail_Sales
  - Task1_EDA_Retail_Sales.ipynb
  - Oasis_Task1_Retail_Sales_Dataset.csv
- Task2_Customer_Segmentation
  - Task2_Customer_Segmentation.ipynb
  - Oasis_Task2_Customer_Segmentation_Dataset.csv
  - Customer_Segmentation_Results.csv

The notebooks contain the complete analyses, visualizations, observations, recommendations, and conclusions.

## Internship
Organization: Oasis Infobyte  
Track: Data Analytics
