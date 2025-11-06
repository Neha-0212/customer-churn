🧠 Azure Multi-Cloud Performance & Cost Metrics Dashboard
📊 Overview

This Power BI dashboard delivers an end-to-end analysis of multi-cloud performance and cost metrics across major providers — AWS, Azure, Google Cloud, and IBM Cloud.
It enables cloud architects, DevOps engineers, and decision-makers to assess resource utilization, latency, deployment efficiency, and cost optimization for microservices deployed across environments.

🗂 Dataset Description

Download Dataset

The dataset captures operational metrics for multiple microservices (Service A–E) deployed on various cloud platforms.
Each record represents a monitoring snapshot containing performance, cost, and deployment data.

Key Columns

Column	Description
ID	Unique identifier for each record
Microservice Name	Name of the service (e.g., Service A, B, etc.)
Cloud Provider	AWS, Azure, Google Cloud, IBM Cloud
Region	Deployment location (e.g., US-East)
Resource Utilization (%)	CPU/memory usage percentage
Latency (ms)	Average request latency
Cost ($)	Operational or deployment cost
Deployment Time (hrs)	Time taken for full deployment
Success Rate (%)	Percentage of successful transactions
Data Transfer (GB)	Total data moved
Environment	Development, Testing, or Production

Example Record – Service B (AWS, Development):

Resource Utilization: 64.25%

Latency: 38.66 ms

Cost: $2,037.22

Deployment Time: 11.38 hrs

Success Rate: 98.43%

Data Transfer: 508.43 GB

💡 Dashboard Highlights
🔹 Performance Metrics

Average Latency by Microservice & Cloud Provider: Identify latency bottlenecks across clouds.

Resource Utilization (%): Visualize workload distribution and service intensity.

🔹 Cost Metrics

Total Cost by Cloud Provider: Compare operational expenses across AWS, Azure, GCP, and IBM Cloud.

Cost by Environment: Track spend differences between Development, Testing, and Production.

🔹 Deployment Insights

Data Transfer (GB) by Service: Pinpoint bandwidth-heavy workloads.

Cost vs Deployment Time: Discover relationships between time efficiency and cost.

🔹 Trend Analysis

Latency vs Deployment Time: Analyze performance trends and service frequency over time.

📈 Key Metrics Summary
Metric	Value	Description
Total Success Rate	37.9M	Aggregate success rate across all deployments
Average Latency	50.00 ms	Mean latency across all microservices
Total Cost	$1.20B	Combined multi-cloud expenditure
🧩 Tools & Technologies

Visualization: Power BI Desktop & Power BI Service

Data Source: CSV/Excel (simulated multi-cloud dataset)

Data Cleaning: Power Query

Charts Used: Bar, Donut, Trend, KPI cards

Theme: Dark Mode for better readability and professional aesthetics

🚀 Use Cases

Cloud cost optimization and budget forecasting

Multi-cloud performance benchmarking

Identifying latency-critical services

Monitoring resource utilization and deployment efficiency

🧠 Insights Gained

AWS and Azure show competitive latency, but cost structures differ significantly.

Service B incurs higher costs despite moderate utilization — a clear optimization target.

Success rates remain consistently above 90% across all environments, ensuring reliability.

📌 Future Enhancements

Integration with real-time monitoring APIs (Azure Monitor, AWS CloudWatch)

Predictive analytics for cost and performance forecasting

Drill-through reports for region-wise and service-level insights

Automated refresh pipeline via Power BI Gateway

🧾 Author

Created by: Neha Kanaki
Purpose: Demonstrate analytical and visualization capabilities for multi-cloud cost and performance optimization using Power BI.
Dataset: Simulated data representing real-world multi-cloud environments.
