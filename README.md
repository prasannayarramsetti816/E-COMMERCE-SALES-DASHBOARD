## E-COMMERCE SALES DASHBOARD
# 📌 Project Overview 
This project presents an E-Commerce Sales Dashboard built using Microsoft Excel to analyze and visualize key sales, product, and customer metrics. The dashboard consolidates order, revenue, and customer data into a single interactive view for quick decision-making.

# 📚 About the Dataset
The dataset (Data sheet, structured as an Excel Table) contains e-commerce transaction records at the order level. It includes the following fields: TX ID, Product, Quantity, Unit Price, Amount, Order Date, Ship Date, Customer Gender, Order Mode, Rating, State, County, Days to Delivery, Weeknum. The data spans 2,400 transactions across a 13-week period. Products span categories such as T-Shirts, Jeans, Sneakers, Sandals, Sundresses, and Bikinis. Order modes include App, Website, Target.com, Partner App, and Instagram. All records are located in California, broken out by county.

# 🤖 Why Excel?
Excel enables fast, drag-and-drop pivot analysis of transactional datasets without heavy coding. PivotTables and PivotCharts allow quick aggregation by product, channel, county, or week. Formulas support calculated fields like delivery time and week number directly from raw dates. Excel dashboards are easy to share, edit, and refresh, making them ideal for lightweight, recurring sales reporting.

🔍 Steps Followed in This Project Data Loading and Preparation: Imported raw transaction data into Excel and structured it as a Table (orders). Cleaned and derived fields for delivery time (Ship Date − Order Date) and week number (WEEKNUM). Data Modeling: Built PivotTables off the Data table for each business question. Created calculated KPI cells for Total Orders, Total Quantity, Total Amount, Average Rating, and Average Days to Deliver. Dashboard Design: Designed KPI cards for high-level metrics. Added charts for trend, distribution, and comparison analysis. Visualization: Used line, donut, bar, and pie charts to represent different aspects of the sales data. Interactivity: Structured PivotTables so all charts refresh together from the same source data.

📊 Key Insights from Visualization Weekly sales trend shows revenue fluctuation across the 13-week period, with Week 10 peaking at ~$64,900. Sales by order mode shows App as the leading channel at 35.3% of total sales. Top 10 products by quantity highlights T-Shirts, Jeans, and Sneakers as volume leaders. Total sales by county shows Los Angeles County generating the largest share of revenue. Average customer rating by product surfaces which items are best and worst received. Customer distribution by gender shows a 55% female / 42% male / 3% other split.

🧑‍💻 Applications of This Project E-commerce operations teams tracking revenue, channel performance, and delivery speed. Retail analytics and reporting for management decision-making. Academic or portfolio projects demonstrating Excel dashboarding and PivotTable skills. Templates for building similar dashboards for other online retailers.

🚩 Possible Extensions of This Project Add revenue by month, not just by week, for seasonal trend analysis. Break out top products by revenue in addition to quantity. Add delivery time analysis by state/county to spot regional shipping delays. Integrate a live data connection for automatic refresh from an order-management system.

🔑 Challenges in Dashboard Design Balancing detail and simplicity so the dashboard remains easy to read at a glance. Ensuring PivotTables recalculate correctly as new transaction rows are added. Handling missing values (e.g., unrated orders, blank gender) without skewing KPI averages.

🏆 Why This Project is Valuable for Learning Provides hands-on experience with Excel PivotTable and PivotChart design. Builds understanding of e-commerce data analysis and KPI reporting. Teaches good practices in visual layout, filtering, and dashboard interactivity. Strengthens skills relevant to business intelligence and data analytics roles.

📈 Key Metrics Displayed Total Orders: 2,400 Total Quantity: 11,997 units Total Revenue: $649,020 Average Rating: 4.0 / 5 Average Days to Deliver: 2.3 days

📂 Project Structure ├── data/ # Raw transaction dataset (Data sheet) ├── dashboard/ # Excel (.xlsx) dashboard file ├── results/ # Dashboard screenshots ├── README.md # Project documentation

📸 Dashboard Screenshots ![Dashboard Screenshot](Screenshot%20(71)

.png)

🎯 Results Summary Delivered a clear, interactive dashboard summarizing e-commerce sales performance. Enabled analysis by order mode, product, county, and gender for deeper insight. Provided actionable insights into revenue trends, product performance, and customer demographics.

👤 Author Prasanna Yarramsetti Data Analyst | Excel Dashboard Developer | E-Commerce Analytics Enthusiast
