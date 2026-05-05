# -Cafe-Sales-Performance-Dashboard

​☕ Cafe Sales Performance Analysis (Google Data Analytics Case Study)

​📝 Introduction
​This case study analyzes the daily operations and sales performance of a local cafe. The goal is to provide data-driven insights to optimize staffing, manage inventory effectively, and increase overall revenue.

​🛠️ Step 1: Ask
​Business Task:
​Identify peak hours to optimize staff scheduling.
​Determine top-performing products by revenue and volume.
​Analyze customer payment preferences.
​Track monthly sales trends to identify growth opportunities.

​📁 Step 2: Prepare
​Data Source: The dataset contains transactional records including Date, Time, Drink Category, Sales Amount, and Payment Method.
​Data Integrity: Verified for completeness and consistency. No missing values were found in key metrics.

​🧹 Step 3: Process
​I used Power Query and DAX for data transformation:
​Cleaning: Removed duplicates and standardized naming conventions for drink categories.
​Time Intelligence: Created a custom column to categorize transaction times into Morning, Afternoon, and Evening shifts.
​Calculated Measures (DAX): * Total Sales = SUM(Sales[Money])
​Order Count = COUNT(Sales[TransactionID])
​Average Order Value = DIVIDE([Total Sales], [Order Count])

​📊 Step 4: Analyze
​Key Insights:
​Peak Performance: The Afternoon shift is the busiest, generating $17K in sales with 521 orders.
​Product Leaders: Latte and Americano With Milk are the primary revenue drivers.
​Payment Behavior: 92% of customers prefer Card payments ($39K) compared to only $3K in Cash.
​Efficiency: The average transaction value stands at $32.47.

​📈 Step 5: Share
​The analysis is presented through an interactive Power BI Dashboard:
​KPI Cards: Real-time tracking of revenue, orders, and averages.
​Sales Breakdown: Visual comparisons of sales by payment type and drink category.
​Gauge Chart: Performance tracking against set sales targets.

​✅ Step 6: Act
​Recommendations:
​Staffing Optimization: Increase staff allocation during the Afternoon period to maintain high service quality during peak hours.
​Product Bundling: Launch promotional bundles (e.g., pairing snacks with Lattes) to increase the average transaction value.
​Digital Focus: Since 92% of payments are by Card, ensure the payment infrastructure is robust and consider launching a digital loyalty app.
​Inventory Management: Prioritize stock levels for high-demand ingredients (Milk and Coffee beans) specifically for Lattes and Americanos.