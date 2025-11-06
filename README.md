📊 Customer Insights Dashboard: Spending, Satisfaction & Churn Analysis
🧠 Overview

This Power BI dashboard analyzes customer spending behavior, satisfaction trends, and churn patterns in an online retail environment. It provides data-driven insights to help businesses identify churn drivers, evaluate promotion effectiveness, and measure overall customer engagement.

🗂 Dataset Description

The dataset online_retail_customer_churn captures demographic, behavioral, and transactional details for 1,000 customers.
Each record represents a single customer profile, containing purchase history, satisfaction metrics, and churn outcomes.

Key Columns

Column	Description
Customer_ID	Unique customer identifier
Age	Customer age
Annual_Income	Reported yearly income
Average_Transaction_Amt	Average purchase value per transaction
Num_of_Purchases	Total number of purchases
Num_of_Returns	Total returns made by the customer
Num_of_Support_Contacts	Customer support interactions
Satisfaction_Score	Satisfaction rating (1–10)
Promotion_Response	Promotion feedback – Responded / Ignored / Unsubscribed
Email_Opt_In	Boolean flag for email marketing opt-in
Last_Purchase_Days_Ago	Days since last purchase
Total_Spend	Cumulative amount spent
Years_as_Customer	Customer tenure
Gender	Female / Male / Other
Target_Churn	True if customer churned, False otherwise
💡 Dashboard Highlights
🔹 Churn & Satisfaction

Satisfaction vs Churn: Visualizes churn probability relative to satisfaction levels.

Promotion Response vs Churn: Shows how engaged customers respond to promotions and their likelihood to stay.

🔹 Spending & Income Insights

Income vs Total Spend & Purchases: Correlates income brackets with spending behavior and engagement frequency.

Age (bins) vs Purchases: Identifies generational buying patterns and activity trends.

🔹 Customer Segmentation

Gender Distribution: Highlights customer demographic split.

Email Opt-In Analysis: Shows percentage of customers participating in email campaigns.

🔹 Support & Experience

Satisfaction vs Support Contacts: Examines how support interaction frequency affects satisfaction levels.

🔹 Key KPI Cards

Total Customers: 1,000

Average Transaction Amount: 266.88K (aggregate)

Churned Customers: Percentage tracked through KPI indicators

📈 Key Insights

High churn correlation observed among customers with low satisfaction (≤4).

Customers who responded to promotions showed significantly lower churn rates.

Middle-income groups (60K–120K) displayed the highest total spend and purchase frequency.

Customers with multiple support contacts tend to have reduced satisfaction scores, indicating potential service friction.

Email Opt-In customers show higher engagement and spend, validating targeted marketing value.

🧩 Tools & Technologies

Power BI Desktop / Power BI Service – Dashboard design & visualization

Data Transformation: Power Query for data cleaning and preprocessing

Visual Elements: Bar charts, Donut charts, KPI cards, Scatter plots, Trend lines

Color Theme: Dark Mode for better contrast and readability

🚀 Use Cases

Customer churn prediction and prevention strategy design

Identifying underperforming customer segments

Marketing campaign targeting based on promotion response

Customer satisfaction monitoring and support optimization

📌 Future Enhancements

Integration with real-time CRM data sources (e.g., Salesforce, HubSpot)

Predictive churn modeling using Power BI + Python integration

Drill-through analysis for segment-level insights

Automated data refresh pipeline with Power BI Gateway

🧾 Author

Created by: Neha Kanaki
Purpose: To demonstrate customer analytics, churn modeling, and visualization skills using Power BI.
Dataset: Simulated online retail dataset prepared for analytical demonstration.
