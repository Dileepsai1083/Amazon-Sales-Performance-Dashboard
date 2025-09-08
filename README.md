# Amazon-Sales-Performance-Dashboard
This project is a Power BI Dashboard designed to analyze Amazon sales performance, track profitability, and uncover key business insights.

🚀 Key Highlights

Total Sales: 725.46K

Total Profit: 108.42K

Profit Margin: 1.00

Average Order Value (AOV): 450.32



📈 Dashboard Features

KPIs at a glance → Sales, Profit, Margin, AOV

Sales by Product → Identify top-performing products

Sales by Category → Visual breakdown by Chairs, Phones, Tables, Storage, etc.

Sales & Profit Trend → Line chart showing daily performance

Time Filters → Drill down by Year, Quarter, Month, Day


🛠️ Tech Stack

Power BI → Data modeling, DAX, visualizations

Excel/CSV → Sample dataset (can be replaced with any sales dataset)

DAX Measures:
Total Sales = SUM('Sales'[SalesAmount])  
Total Profit = SUM('Sales'[Profit])  
Total Orders = DISTINCTCOUNT('Sales'[OrderID])  
Profit Margin = DIVIDE([Total Profit], [Total Sales])  
Average Order Value = DIVIDE([Total Sales], [Total Orders])  

📂 Project Structure
amazon-sales-dashboard/
├── data/               # Sales dataset (not included here for privacy)
├── pbix/               # Power BI file
│   └── Amazon_Sales_Dashboard.pbix
├── images/             # Dashboard screenshots
│   └── dashboard.png
└── README.md



🔍 Business Questions Answered

Which products drive the highest sales and profits?

Which categories contribute most to revenue?

How does sales and profit trend over time?

What is the average order value across years?



🚦 How to Use

Clone the repository:

git clone https://github.com/<your-username>/amazon-sales-dashboard.git


Open Amazon_Sales_Dashboard.pbix in Power BI Desktop.

Connect your own dataset (or use the provided sample).

Refresh the dashboard and start exploring insights.




📌 Future Improvements

Add geographical analysis (Sales by Region).

Include YoY / MoM Growth KPIs.

Drill-through to Customer-Level Insights.

Deploy on Power BI Service with scheduled refresh.



