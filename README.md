Power BI Multi-Page Dashboard
This project is a professional multi-page Power BI dashboard designed to analyze and visualize sales, inventory, customer behavior, supplier performance, and regional data. It demonstrates a variety of Power BI features, including advanced visuals, DAX calculations, and interactivity to offer insights into business performance.


This Power BI dashboard covers the following key aspects:

Sales Analysis: Identifying top-performing products, sales trends, and revenue distribution.
Inventory Insights: Understanding stock levels and inventory management.
Customer Loyalty: Evaluating loyalty points and customer ratings.
Supplier Performance: Analyzing supplier contributions and return rates.
Regional Analysis: Mapping sales and customer density by location.

File Structure

PowerBI-MultiPage-Dashboard/
├── Data/
│   ├── Sales.csv                 # Sales dataset
│   ├── Purchases.csv             # Purchase dataset
│   ├── Countries.csv             # Regional dataset
├── Screenshots/
│   ├── Page1_Overview.png        # Screenshot of the Overview page
│   ├── Page2_SalesAnalysis.png   # Screenshot of the Sales Analysis page
│   └── ... (screenshots of other pages)
├── Analysis and Visuals
├── README.md                     # Documentation file

Technologies Used
Power BI Features

Data Transformation:
Imported and transformed datasets using Power Query.
Cleaned and formatted data for accurate visualizations.

DAX (Data Analysis Expressions):
Created measures and calculated columns for insights such as:
Total Revenue = SUM(Sales[Quantity Purchased] * Sales[Gross Product Price])
Loyalty Points per Purchase = SUM(Sales[Loyalty Points]) / COUNT(Sales[Order ID])

Advanced Visualizations:
Line charts, bar charts, and tree maps for trend and category analysis.
Gauge charts for KPIs like total stock levels.
Map visuals for geographical insights.

Interactivity:
Used slicers for filtering by product category, region, and time period.
Added drill-through functionality for deeper insights.
