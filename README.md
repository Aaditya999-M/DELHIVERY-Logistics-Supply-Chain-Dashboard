# DELHIVERY-Logistics-Supply-Chain-Dashboard
Power BI Logistics &amp; Supply Chain Analytics Dashboard using DAX, Power Query and Data Analysis.


DELHIVERY Logistics & Supply Chain Analytics Dashboard

Project Overview

The DELHIVERY Logistics & Supply Chain Analytics Dashboard is an interactive Power BI solution developed to analyze and monitor logistics operations across shipments, delivery costs, distances, delays, weather conditions, vehicle utilization, regions, and delivery partner performance.

The project transforms raw logistics data into meaningful operational insights using Power Query, DAX, data modeling, KPI development, interactive navigation, and custom performance indices.

---

 Business Objective

The objective of this project is to provide a centralized analytical view of logistics operations and identify:

- Overall shipment performance
- Delivery delays and on-time performance
- Delivery cost and distance patterns
- Vehicle utilization
- Regional shipment distribution
- Weather-related delay patterns
- Delivery partner performance
- Operational shipment stress
- Cost efficiency across delivery partners

---

Tools & Technologies

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Data Cleaning & Transformation
- Data Visualization
- Business Intelligence

---

Dashboard Pages

1. Dashboard

Provides a high-level overview of logistics operations through key performance indicators and operational summaries.

Key areas include:

- Total Shipments
- Total Distance
- Average Distance
- Average Delivery Cost
- On-Time Deliveries
- Weather Delay Rate

---

2. Shipment Analysis

Provides detailed analysis of shipment operations across multiple dimensions.

Key analysis includes:

- Shipment Volume by Region
- Shipment Trends
- Distance and Delivery Cost Relationship
- Delay Rate by Weather Condition
- Vehicle Type Distribution
- Delivery Partner Performance
- Shipment Stress Analysis

---

3. Reports

Provides deeper operational and comparative analysis of logistics performance without duplicating the primary shipment analysis.

The page focuses on:

- Delivery Partner Benchmarking
- Operational Performance
- Cost Efficiency
- Regional and operational comparisons
- Advanced performance indicators

---

# Key Performance Indicators

The dashboard uses DAX measures to calculate core operational KPIs.

•	Total Shipments

Measures the total number of shipment records.

•	Total Distance

Measures the total distance covered across all shipments.

•	Average Distance

Calculates the average distance per shipment.

•	Average Delivery Cost

Calculates the average delivery cost per shipment.

•	Average Rating

Measures the average delivery rating.

•	On-Time Rate

Measures the percentage of shipments that were not delayed.

•	Delay Rate

Measures the percentage of shipments that were delayed.

•	Cost Efficiency

Measures distance covered per unit of delivery cost.

---

•	Advanced Analytics

 
1. Overall Performance Score

A custom performance index was developed to benchmark delivery partners using three operational dimensions:

| Metric | Weight | Direction |
|---|---:|---|
| Delivery Cost | 35% | Lower is better |
| Delivery Rating | 35% | Higher is better |
| Cost Efficiency | 30% | Higher is better |

Each metric is normalized to a common scale and combined into a final score ranging from 0 to 100.

 Formula

Overall Performance Score:

Cost Score × 35  
+ Rating Score × 35  
+ Efficiency Score × 30

The score is used as a comparative measure between delivery partners within the dataset.

---

 2. Shipment Stress Index

A custom Shipment Stress Index was developed to identify shipment segments experiencing relatively higher operational pressure.

The index considers:

| Factor | Weight |
|---|---:|
| Delay Pressure | 40% |
| Cost Pressure | 25% |
| Distance Pressure | 20% |
| Package Weight Pressure | 15% |

A higher index indicates relatively greater operational pressure based on the selected factors.


 Data Analysis Workflow

Raw Logistics Data
        ↓
Data Cleaning & Transformation
        ↓
Power Query
        ↓
Data Modeling
        ↓
DAX Measures
        ↓
KPI Development
        ↓
Advanced Performance Indices
        ↓
Interactive Dashboard
        ↓
Business Insights
