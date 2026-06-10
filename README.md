📱 PhonePe Pulse Geo-Visualization Dashboard

📌 Project Overview
This project is an interactive Geo-Visualization Dashboard built using Power BI and the PhonePe Pulse dataset. The dashboard provides insights into digital payment trends, transaction growth, user adoption, and regional performance across India.

The objective of the project is to analyze how digital payments have evolved over time, identify high-performing states and districts, and understand user adoption patterns through interactive visualizations and filters.

🎯 Business Objective
To provide stakeholders with a comprehensive view of:
Digital payment growth across India
Transaction trends over time
State-wise and district-wise performance
User adoption and engagement patterns
Mobile brand usage distribution
High-performing regions based on transactions and users
This dashboard helps in identifying areas with strong digital payment adoption and regions that may require further growth initiatives.

📂 Dataset Information
The project utilizes six datasets extracted from the PhonePe Pulse repository:
Dataset	Description
Aggregated Transaction	State-level transaction counts and transaction amounts
Aggregated User	Brand-wise user distribution and market share
Map Transaction	District-level transaction details
Map User	District-level registered user information
Top Transaction	Top-performing districts based on transaction activity
Top User	Top-performing districts based on registered users

🛠️ Data Preparation
The following preprocessing steps were performed:
Imported all datasets into Python (Google Colab)
Removed unnecessary index columns (Unnamed: 0)
Checked for missing values
Checked for duplicate records
Verified data types and dataset structure
Prepared datasets for Power BI visualization

📊 Dashboard Structure
Page 1: Overview
Provides a high-level summary of the digital payment ecosystem.
KPIs
Total Transaction Amount
Total Transactions
Total Users
Average Transaction Value
Visualizations
Transaction Growth Trend (Quarter-wise)
State-wise Transaction Amount
District-wise Transaction Distribution Map
Filters
State
Year
Quarter
Page 2: Transaction Analysis

Focused on transaction behavior and regional performance.
KPIs
Total Transaction Amount
Total Transactions
Average Transaction Value
Visualizations
Transaction Type Analysis
State-wise Transaction Comparison
Top Performing Districts
Transaction Trend Analysis
Filters
State
Year
Quarter
Transaction Type
Page 3: User Analysis

Focused on user adoption and engagement.
KPIs
Total Registered Users
Visualizations
User Distribution Map
Top User Districts
Mobile Brand Distribution
User Growth Trend
Filters
State
Year
Quarter
Brand

📈 Key Insights Generated
Identification of high-performing states and districts
Analysis of transaction growth trends across quarters
Understanding of digital payment adoption patterns
Comparison of transaction categories
Mobile device brand distribution among users
Regional concentration of users and transactions

🧰 Tools & Technologies
Power BI
Python
Google Colab
Pandas
DAX
PhonePe Pulse Dataset
📸 Dashboard Preview

Add screenshots of:
Overview Dashboard
Transaction Analysis Dashboard
User Analysis Dashboard
inside a /screenshots folder and reference them here.

🚀 Project Outcome
Developed an interactive geo-visualization dashboard that transforms raw PhonePe Pulse data into actionable business insights through KPI tracking, trend analysis, geographic visualization, and user adoption analysis.

👨‍💻 Author
Alok Kumar
Aspiring Data Analyst | Power BI | SQL | Python | Excel

⭐ If you found this project useful, consider giving it a star!
