# Subscription-Intelligence-Dashboard-Churn-Risk-Profiling-Retention-Strategy-Analytics

<img width="1438" height="942" alt="image" src="https://github.com/user-attachments/assets/d3596df3-e068-4ed9-8f58-0d882d7ad54a" />

# 📋 Table of Contents

* Project Overview
* Business Problem
* Dataset Information
* Key Features
* Tools & Technologies
* Data Preparation
* Dashboard Components
* Key Insights
* Installation & Usage
* Project Structure
* Future Enhancements
* Contact

# 🎯 Project Overview
An interactive Power BI dashboard analyzing customer churn patterns in a music streaming service. This project leverages data analytics to identify at-risk subscribers, understand churn drivers, and provide actionable insights for customer retention strategies.
* Project Duration: 6th April 2026 10:30:00 A.M to 11:30:00 A.M 
* Role: Data Analyst
* Industry: Digital Media & Streaming Services

# 💼 Business Problem
Music streaming platforms face significant challenges in retaining subscribers in a highly competitive market. Understanding why customers churn and identifying early warning signs is critical for:

* Revenue Protection: Reducing subscription cancellations
* Customer Lifetime Value: Improving long-term subscriber relationships
* Resource Optimization: Targeting retention efforts effectively
* Strategic Planning: Data-driven decision making for product improvements

# 📊 Dataset Information
<img width="829" height="289" alt="image" src="https://github.com/user-attachments/assets/02800bac-d213-42ca-a557-9e9e9028e2e4" />

# Dataset Features:

* Demographics: Gender, Age Group
* Subscription Details: Plan Type, Payment Method, Auto-Renewal Status
* User Behavior: Top Genre, Previous Subscription Plan
* Technical Metrics: Device Type, Network Type, Average Buffering Time
* Outcome: Churn Status

# ✨ Key Features
## 📈 Analytics Capabilities

* ✅ Churn Rate Analysis: Overall and segmented churn metrics
* ✅ Customer Segmentation: Analysis by demographics, subscription plans, and behavior
* ✅ Trend Analysis: Time-based churn patterns and predictions
* ✅ Risk Profiling: Identification of high-risk customer segments
* ✅ Interactive Filtering: Dynamic slicers for multi-dimensional analysis

## 🎨 Visualization Highlights

* KPI cards for critical metrics (Churn Rate, Total Customers, Revenue Impact)
* Comparative bar charts for subscription plan performance
* Demographic distribution analysis
* Technical performance metrics correlation
* Payment method and auto-renewal impact analysis

# Tools and Technologies
<img width="837" height="279" alt="image" src="https://github.com/user-attachments/assets/0470ff3b-dab8-4605-834b-b1c04d984444" />

# 🔧 Data Preparation
## Excel Pre-Processing:

1.Data Cleaning

* Handled missing values and duplicates
* Standardized categorical variables
* Validated data types and formats


2.Data Quality Checks

* Verified data consistency across columns
* Identified and treated outliers in buffering time
* Ensured proper encoding of categorical variables


3.Feature Engineering

* Created age group buckets
* Standardized subscription plan categories
* Validated churn labels

## Power BI Transformations:

* Imported clean CSV data into Power BI
* Established data model relationships
* Created calculated columns for analysis
* Developed custom DAX measures for KPIs

# 📱 Dashboard Components
1. Executive Summary Page

* Total customers and churn rate
* Revenue impact estimation
* High-level trends and comparisons

2. Customer Segmentation Analysis

* Churn by age group
* Gender-based churn patterns
* Music genre preferences vs. churn

3. Subscription Intelligence

* Plan type performance (Free, Premium, Family)
* Payment method correlation with churn
* Auto-renewal impact analysis

4. Technical Performance Metrics

* Device type analysis (iOS, Android, Web)
* Network type impact (WiFi, 4G, 5G)
* Buffering time correlation with churn

5. Actionable Insights

* Risk segments identification
* Retention recommendations
* Strategic focus areas

# 💡 Key Insights


📉 Overall Churn Rate: [30.70%] of subscribers churned
👥 High-Risk Segments: Family = [2.22%], Free = [5.41%], Premium = [-6.33%]
💳 Payment Method Impact: UPI users show [29.46%] lower churn
📱 Device Performance: Android users experience higher retention
🎵 Genre Preferences: Jazz listeners show strongest loyalty
⚡ Technical Factors: Buffering time above 0-1 seconds correlates with [31.71]% higher churn

# 🚀 Installation & Usage
Prerequisites:

Microsoft Power BI Desktop (Latest version)
Microsoft Excel 2016 or later

Steps to Run:

1.Clone the Repository

bash  
git clone https://github.com/MahendraPatibandla/customer-churn-analytics.git
cd customer-churn-analytics

2.Open the Dataset

* Navigate to the /data folder
* Open churn_analysis_dataset.csv in Excel (optional: for verification)


3.Launch Power BI Dashboard

* Open Churn_Analysis_Dashboard.pbix in Power BI Desktop
* Refresh data connections if prompted
* Explore interactive visualizations


4.Interact with Dashboard

* Use slicers to filter by demographics, subscription type, etc.
* Click on visuals for cross-filtering
* Export insights as needed

# Project Structure
customer-churn-analytics/
│
├── data/
│   └── churn_analysis_dataset.csv          # Raw dataset
│
├── reports/
│   └── Churn_Analysis_Dashboard.pbix       # Power BI dashboard file
│
│
└── README.md                                # Project documentation


🔮 Future Enhancements

 * Predictive Modeling: Integrate ML models for churn probability scoring
 * Real-time Data: Connect to live data sources for dynamic updates
 * Advanced Segmentation: Implement RFM analysis and customer personas
 * A/B Testing Framework: Track retention campaign effectiveness
 * Mobile Optimization: Create mobile-friendly dashboard version
 * Automated Alerts: Set up threshold-based notifications for churn spikes

# 🎓 Key Learnings

* Advanced DAX formulas for complex business metrics
* Data storytelling through effective visualization design
* Customer segmentation strategies
* Translating data insights into business recommendations

# 📞 Contact
Patibandla Mahendra
📧 Email: mahendrapatibandla7@gmail.com
💼 LinkedIn: linkedin.com/in/mahendrapatibandla
🐱 GitHub: @MahendraPatibandla

<div align="center">
⭐ If you found this project helpful, please consider giving it a star!
Made with ❤️ and ☕ by Patibandla Mahendra
</div>
