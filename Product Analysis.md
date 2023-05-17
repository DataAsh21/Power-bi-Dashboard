### Introduction
The purpose of this project is to create a product analysis dashboard using Power BI. The dashboard will provide insights into sales and profit data, allowing users to analyze performance, identify trends, and make informed business decisions. The dashboard consists of three main pages: Dashboard, Details Analysis, and Performance Report. Custom icon buttons will be used for easy navigation between the pages. Additionally, an ETL (Extract, Transform, Load) process will be implemented to prepare and transform the data. Calculated columns in DAX (Data Analysis Expressions) will be used to derive measures such as sales and profit.
- ETL Process

The ETL process involves the following steps:
Extract: Retrieve the sales and profit data from the data source, such as a database or Excel file.
Transform: Perform data transformations and cleaning operations. This may include removing duplicates, handling missing values, and ensuring data consistency.
Load: Load the transformed data into Power BI for analysis and visualization.
- Calculated Columns and DAX Measures

In the data model, calculated columns and DAX measures are created to derive additional insights. Examples of calculated columns and DAX measures include:
Sales: Calculated as the product of unit sold and unit price.
Profit for Total Unit Sold: Calculated as profit multiplied by the unit sold.
These calculated columns and DAX measures enhance the analysis capabilities of the dashboard.
- Dashboard Page

The Dashboard page is the landing page of the dashboard and provides an overview of sales and profit data. It includes the following visualizations:
Stacked Bar Chart: Displays sales and profit data segmented by product categories. Users can analyze the contribution of each segment to overall sales and profit.
Line Chart: Shows the monthly trend of sales and profit. This visualization allows users to identify patterns and seasonality in sales and profit data.
Map: Presents a geographical representation of sales and profit by country. It enables users to identify regions with the highest sales and profit.
Scatter Plot: Provides a detailed analysis of sales, profit, and units sold by product name. Users can identify relationships and outliers in the data.
- Details Analysis Page

The Details Analysis page focuses on specific product and supplier analysis. It includes the following visualizations:
Top 5 Products by Sales: Presents a bar chart displaying the top 5 products based on sales. Users can quickly identify the best-selling products.
Top 5 Products by Supplier Name: Displays a bar chart showcasing the top 5 products based on supplier name. This visualization helps identify the most successful suppliers.
Matrix: Provides a tabular view of supplier name, product name, sales, and profit. Conditional formatting is applied to highlight high and low values, enabling users to spot trends and outliers easily.
- Performance Report Page

The Performance Report page focuses on identifying underperforming segments, products, and suppliers. It includes the following elements:
Bottom 5 Sales by Product Name: Presents a table with the bottom 5 products based on sales. Users can identify products that need improvement.
Bottom 5 Sales by Supplier Name: Displays a table showcasing the bottom 5 suppliers based on sales. This helps identify suppliers with low performance.
Bottom 5 Sales by Segment: Provides a table highlighting the bottom 5 segments based on sales. Users can analyze the reasons for poor performance.
Text Analysis: Contains descriptive text explaining the reasons for low performance and suggestions for improving profitability. Users can take proactive measures based on these insights.
- Bookmarks Functionality
 
 By implementing bookmarks, users can easily navigate between the different pages of the product analysis dashboard by clicking on the custom icon button associated with the dashboard. Each bookmark captures the specific state of the page, including applied filters, slicer selections, and customizations, allowing users to return to a particular view with just a single click. This enhances the usability and interactivity of the dashboard, enabling users to explore and analyze the data effectively.
- Conclusion

The product analysis dashboard in Power BI provides users with a comprehensive view of sales and profit data. The dashboard enables users to analyze performance, identify trends, and make data-driven decisions. The three main pages (Dashboard, Details Analysis, and Performance Report) offer different perspectives on the data, allowing users to dive deep into specific analysis areas. Custom icon buttons facilitate easy navigation between the pages. With this dashboard, businesses can gain valuable insights to improve performance and overall profitability.



