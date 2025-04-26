# 📊 OLA Customer Segmentation Analysis

Welcome to the **OLA Customer Segmentation** project!  
This project focuses on analyzing customer ride data for Ola Cabs using **SQL** for data exploration and **Power BI** for building an interactive dashboard that provides deep insights into customer behavior and ride patterns.



## 🚀 Project Objective

The primary goal of this project is to **segment Ola customers** based on their ride history and demographic patterns to uncover valuable business insights.  
The segmentation helps in:

- Understanding different customer profiles
- Analyzing usage trends
- Identifying opportunities for targeted marketing and service improvements
- Enhancing customer experience through data-driven strategies



## 🛠️ Tools and Technologies

| Technology   | Purpose                            |
|--------------|------------------------------------|
| **SQL**      | Data cleaning, transformation, and querying |
| **Power BI** | Interactive dashboard creation and data visualization |
| **CSV**      | Data storage format (Ola sample dataset) |



## 📂 Project Files

| File Name                   | Description |
|------------------------------|-------------|
| `Ola_Sample_Data.csv`         | Sample dataset containing customer ride information |
| `Ola Data Analysis.sql`       | SQL queries used for data preparation and exploration |
| `ola.pbix`                    | Power BI dashboard file for visual insights |



## 🧩 Project Workflow

### 1. Data Understanding

The dataset (`Ola_Sample_Data.csv`) includes:

- Customer ID
- Gender
- Age
- City
- Number of rides
- Average ride distance
- Average ride rating
- Payment method
- Subscription status
- And other key attributes



###  Data Exploration (SQL)

SQL scripts were used to:

- Clean and filter the dataset
- Perform aggregation and group-by operations
- Identify customer clusters based on ride frequency, spending, and demographics
- Derive important KPIs such as:
  - Top cities by ride volume
  - Gender-based ride trends
  - Subscription impact on ride frequency
  - Preferred payment methods

**Sample SQL Query:**

```sql
-- Example: Finding top 5 cities by number of rides
SELECT City, COUNT(*) AS Total_Rides
FROM Ola_Sample_Data
GROUP BY City
ORDER BY Total_Rides DESC
LIMIT 5;
```

###  Data Visualization (Power BI)

Key visualizations included in the Power BI dashboard:

- **Customer Segmentation Pie Charts** (based on subscription and payment methods)
- **Age and Gender Distribution**
- **City-wise Ride Analysis**
- **Average Rating vs Number of Rides Scatter Plots**
- **Subscription Status Impact on Ride Frequency**
- **Revenue Insights**

Interactive filters and slicers were added to allow dynamic exploration based on:

- City
- Gender
- Subscription Status
- Payment Method



🚀 **Dashboard Highlights**:

- Clear KPIs displayed on the top
- Clean, professional theme
- Responsive visualizations for storytelling
- Drill-through reports for customer deep-dive analysis



## 📈 Insights Gained

- **Subscribed users** show significantly higher ride frequencies.
- **Credit Card** remains the most preferred payment method.
- **Top 5 cities** contribute to over 60% of total rides.
- **Female customers** have a slightly higher average ride rating.
- **Age groups 25-34** are the most active segment.

These insights can help Ola in designing better loyalty programs, optimizing marketing strategies, and personalizing service offerings.





## 📜 Future Enhancements

- Apply **Machine Learning clustering algorithms** (like K-Means) for advanced customer segmentation.
- Deploy the dashboard online using **Power BI Service**.
- Include predictive analysis for customer churn and revenue forecasting.





# 🏁 Thank You for Visiting!
