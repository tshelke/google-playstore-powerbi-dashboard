# google-playstore-powerbi-dashboard
This project analyzes Google Play Store app data to understand app performance, user engagement, and monetization trends using Power BI.

# Objective
To identify patterns between app ratings, installs, and user engagement, and support data-driven decisions for product and web analytics.

# Tools & Technologies
- Power BI
- Power Query (Data Cleaning & Transformation)
- DAX (Data Analysis Expressions)

# Data Preparation
- Cleaned and transformed raw dataset (handled missing values, normalized installs, price, and size columns)
- Converted text fields into numeric formats
- Created calculated columns and measures

# Key Metrics (DAX Measures)
- Total Apps
- Total Installs
- Average Rating
- Average Reviews
- Paid Apps
- Average Price (Paid Apps)
- Category Installs
- Reviews per 1k Installs

# Key Visualizations
1. KPI Cards (Apps, Installs, Ratings)
2. Category-wise installs (Bar chart)
3. Scatter plot (Rating vs Installs, bubble = Reviews)
4. Paid vs Free app comparison
5. Top apps table with drillthrough

# Key Insights
1. Some apps have high installs but low ratings, indicating quality issues
2. High-rated apps with low installs represent growth opportunities
3. Most installs come from free apps, showing freemium dominance

# Business Use Case

This dashboard can be used by:

1. Product teams to improve app quality
2. Marketing teams to identify high-growth categories
3. Analysts for benchmarking app performance
