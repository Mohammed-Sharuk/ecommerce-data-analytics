# E-Commerce Data Analytics Project

## Project Overview
This project involves analyzing e-commerce data using SQL, Excel, and Power BI to derive insights and visualize key metrics. The main objectives are to identify trends, track sales performance, and provide a comprehensive overview of business operations.

## Tools and Technologies
- **SQL**: For querying the database to extract and manipulate data.
- **Excel**: For creating pivot charts and analyzing data from SQL queries.
- **Power BI**: For building interactive dashboards to visualize the data.

## Data Sources
- **E-commerce Database**: Contains tables such as Orders, Customers, Products, and Sales.

## SQL Queries
1. **Credit Limit**: Identifying customers' credit limits.
2. **Customers Affected by Late Shipping**: Listing customers who have experienced late shipments.
3. **Customers Over Credit Limit**: Finding customers who have exceeded their credit limit.
4. **Office Sales by Customer Country**: Summarizing sales by office and customer country.
5. **Products Purchased Together**: Analyzing products that are often bought together.
6. **Sales and Country Overview**: Providing an overview of sales by country.
7. **Sales Value Change from Previous Order**: Calculating the change in sales value from one order to the next.

## Excel Analysis
- **Pivot Charts**: Created for each of the SQL queries to visualize the data. The charts include:
  - Credit Limit Analysis
  - Late Shipping Impact
  - Customers Over Credit Limit
  - Office Sales by Customer Country
  - Products Purchased Together
  - Sales and Country Overview
  - Sales Value Change from Previous Order

## Power BI Dashboards
### Dashboard 1
This dashboard provides a comprehensive analysis of sales and net profit.

- **Clustered Bar Chart**: Analyzes sales and net profit by product line.
- **Scatter Chart**: Analyzes net profit and sales by the cost of sale.
- **Donut Chart**: Analyzes sales and net profit by office country.
- **Stacked Column Chart**: Analyzes sales and net profit by customer country.
- **Cards**: Display total sales, count of unique orders, and average value per order.
- **Trend Lines**: Show trends by office country below each card.
- **Slicers**: 
  - Order Date Slicer: Filters charts and cards by order date.
  - Product Line Slicer: Filters charts and cards by product line.
- **Toggle Buttons**: Switch between sales and net profit views in the charts.

### Dashboard 2
This dashboard focuses on a more detailed analysis of net profit.

- **Decomposition Tree**: Analyzes net profit explained by customer country, product line, and customer name.
- **Table**: Shows a sales overview with columns such as Order Year, Order Month, Sales Value, Sales Value MoM%, and Sales Value YTD.
- **Toggle Buttons**: Switch between the two dashboards.

## How to Run the Project
1. **Database Setup**: Ensure you have access to the e-commerce database and the necessary permissions to run SQL queries.
2. **Run SQL Queries**: Execute the provided SQL queries to extract the data needed for analysis.
3. **Excel Analysis**: Import the SQL query results into Excel and create the pivot charts.
4. **Power BI Dashboards**:
   - Import the data into Power BI.
   - Follow the provided steps to create the visualizations and set up the slicers and toggle buttons.
5. **Interact with the Dashboards**: Use the slicers and toggle buttons to explore the data and gain insights.

This project focuses on analyzing and visualizing e-commerce sales data to derive actionable business insights. It demonstrates practical skills in SQL, Excel, and Power BI—covering the full data analysis workflow from data extraction to interactive dashboards.

---

## 📌 Objective

To analyze e-commerce sales data and uncover trends, patterns, and key metrics that can help improve business decision-making. The project involves:

- Data cleaning and transformation
- Writing complex SQL queries
- Creating visual reports using Excel and Power BI

---

## 🛠️ Tools & Technologies

- **SQL** – for data extraction and transformation
- **Microsoft Excel** – for pivot tables and basic visualization
- **Power BI** – for advanced data visualization and dashboarding

---

## 📂 Project Structure

```plaintext
E-Commerce-Data-Analytics/
├── Dataset/
│   └── [CSV or Excel data files]
├── SQL Queries/
│   └── queries.sql
├── Excel Analysis/
│   └── sales_dashboard.xlsx
├── Power BI/
│   └── ecommerce_dashboard.pbix
└── README.md

📈 Key Insights
Some of the business questions answered in this project:
What is the monthly sales trend?
Which product categories generate the most revenue?
Who are the top-performing customers and regions?
What is the contribution of each sales channel (e.g., website vs mobile)?

🔍 Sample Visuals
Sales trend over time
Top 10 products by revenue
Regional sales distribution
Customer segmentation analysis

## Credits
Original project by [Pradeesh Rajakumar](https://github.com/pradeeshculer/E-Commerce-Analysis).  
This version was modified and restructured by [Mohammed-Sharuk] for learning and portfolio purposes.

## Conclusion
This project showcases the use of SQL, Excel, and Power BI to analyze and visualize e-commerce data effectively. The insights derived can help in making informed business decisions.

