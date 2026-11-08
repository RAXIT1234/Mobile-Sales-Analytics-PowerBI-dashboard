📱 Mobile Sales Interactive Dashboard (Power BI)

An end-to-end business intelligence dashboard built in Power BI to track, analyze, and visualize mobile sales performance, customer trends, and key business metrics.

🚀 Project Overview

This project transforms raw transactional sales data into an interactive executive dashboard. It tracks revenue streams across major mobile brands (Apple, Samsung, OnePlus, Vivo, Xiaomi), analyzes customer rating distributions, and evaluates payment mode preferences.

💡 Key Learnings & Technical Highlights

Multi-Page Executive Layout: Designed a seamless reporting interface featuring an Overview Dashboard, Month-to-Date (MTD) tracking, and Same Period Last Year (SPLY) analysis.

Advanced DAX & Metrics: Developed explicit DAX measures to aggregate core business KPIs:

Total_Sales = SUMX('Sales_Data', 'Sales_Data'[Units Sold] * 'Sales_Data'[Price Per Unit])
Total_Quantity = SUM('Sales_Data'[Units Sold])
Transactions = DISTINCTCOUNT('Sales_Data'[Transaction ID])
Average_Price = AVERAGE('Sales_Data'[Price Per Unit])


Geographical & Category Filtering: Integrated interactive map visualizations to track regional sales across major Indian cities (Delhi, Mumbai, Bangalore, Hyderabad, Kolkata) along with dynamic brand slicers.

Diverse Visualizations: Engineered a wide range of custom visualizations, including:

Area & Line Charts for monthly volume trends and day-of-week sales

Donut Charts for payment method splits (UPI, Credit Card, Debit Card, Cash)

Horizontal Bar Charts for model-level revenue performance

Funnel Charts for customer rating status breakdowns

🛠️ Tools & Technologies Used

Power BI Desktop: Data modeling, DAX measure creation, interactive visual design, and report layout.

Power Query (ETL): Data cleaning, field transformation, date hierarchy setup, and schema formatting.

Microsoft Excel: Data storage for raw transactional records (Mobile Sales Data.xlsx).

Git & GitHub: Version control and portfolio hosting.

📂 Repository Structure

├── Mobile Sales Data.xlsx    # Primary transactional dataset (3,835 rows)
├── Dashboard Preview.jpg     # Executive dashboard overview screenshot
├── MTD Report.jpg            # Month-to-date trajectory analysis screenshot
├── MS_Dashboard -.pbix       # Main Power BI project file
└── README.md                 # Project documentation


⚙️ How to View This Project

Clone or download this repository to your computer.

Open the MS_Dashboard -.pbix file using Power BI Desktop.