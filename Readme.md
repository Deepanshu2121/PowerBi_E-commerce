**Project Overview**

This  Power BI project aimed at analyzing E-Commerce Order Data from multiple countries.
It simulates a real-world business scenario where an e-commerce company dealing in mobile accessories wants to understand sales performance, customer behavior, and demand patterns to make data-driven decisions.
The project involves data cleaning, modeling, DAX calculations, and report building to generate actionable insights.

**Objectives** 

1. Sales Targets and Completion Rates
2. Top Sales Managers by Country
3. Order Trends Analysis
4. Country-wise Performance
5. Customer Order Analysis
6. Order Source Analysis
7. Customer Category Insights
8. Q&A Interactivity
9. Sales Targets Page & KPI Dashboard
10. Report Design and Visualization
11. Slideshow using Bookmarks
12. Mobile View Design
13. Save Final PBIX File

**Project Structure**

- Folder / File	Description
- Data/	Contains Excel file with three tables — Orders, Customers, and Sales Targets
- PowerBI File/	.pbix file with complete report and DAX measures
- README.md	Documentation and explanation of the project
- Images/	Screenshots of dashboards and visuals
- Reports/	Exported PDF of the Power BI report
- Dataset Details

- **Orders Table**: Contains order details such as Order ID, Date, Source, Sales POC, and Order Value.

- **Customers Table**: Contains customer details like Customer ID, Gender, Category, and Country.

- **Sales Targets Table**: Includes Sales POC, Sales Manager, Team, and assigned targets.

**Data Model**

**Relationships**:
Customers[Customer ID] → Orders[Customer ID]
Sales Targets[Sales POC] → Orders[Sales POC]
Type: One-to-Many, bidirectional where necessary.

- Additional Calculated Columns and Measures created using DAX.


**Reports and Dashboards**

1. **Sales Performance Dashboard**
- Compare Actual Sales vs Target Sales by:
- Sales POC
- Sales Manager
- Sales Team
- Visuals: Clustered Bar Charts, KPI Cards

2. **Country Insights Dashboard**
- Analyze performance by Country:
- Total Sales Value
- Number of Orders
- Top Performing Managers
- Visuals: Filled Map, Table, Bar Chart

3. **Order Trends & Forecast**
- Monthly trend of Number of Orders and Sales Value
- Identify high-performing months
- Visuals: Line & Area Chart

4. **Customer Insights**
- % of customers who did not place an order
- Order behavior by Gender and Category
- Visuals: Donut Chart, Column Chart

5. **Order Source Analysis**
- Performance comparison of order sources (App, Website, WhatsApp, etc.)
- Visuals: Pie Chart, Bar Chart

6. **Drill-through Functionality**
- Drill from Country Map → Sales Manager → Sales POC
- Enables detailed insight per team.

7. **Presentation Mode**
- Slideshow created using Bookmarks for stakeholder presentation.

**Key Findings**

- Certain Sales Teams consistently exceeded their targets, while a few lagged behind.
- Country X and Country Y showed the highest order value and volume.
- App emerged as the most popular order source.
- Some Sales Managers were associated with multiple countries, increasing their coverage.
- Seasonal trends were visible — specific months had significant sales spikes.
- A notable % of customers did not place an order despite being registered.

**Conclusion**
This Power BI project demonstrates how structured data analysis and visualization can transform raw business data into valuable insights.
It helps the e-commerce company to:

- Optimize sales strategies
- Focus on top-performing regions and sources.
- Identify improvement areas for underperforming teams.
- Forecast demand for better inventory and marketing decisions.

**How to Use**

- Download the repository or clone it:
- git clone https://github.com/<your-username>/PowerBI-ECommerce-Orders.git
- Open the .pbix file in Microsoft Power BI Desktop.
- Refresh the data source (if required).
- Navigate through different dashboards using tabs or bookmarks.
- Explore filters, slicers, and drill-through options to interact with visuals.

**Tools & Technologies**
- Microsoft Power BI Desktop
- DAX (Data Analysis Expressions)
- Excel (for dataset)
- Data Modeling & Visualization Best Practices

**Author - Deepnashu Dahiya**
This project is part of my portfolio, showcasing the PowerBI skills essential for data analyst roles. If you have any questions, feedback, or would like to collaborate, feel free to get in touch!

