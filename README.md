                                     Introduction to the Vehicle Data Analysis
The project focuses on analyzing a dataset of vehicle sales and orders to generate meaningful insights for business performance evaluation. This dataset contains detailed information about orders such as order numbers, product details, pricing, sales data, customer information, and shipping details across different regions.
The goal of this project is to leverage Power BI's data visualization capabilities to understand the trends in vehicle sales, customer behaviors, and product performance by creating an interactive dashboard.

                                      Objective
The main objectives of the project are-
1. Sales Analysis: Analyze sales data based on various factors such as country, product line, deal size, and year.
2. Order Performance: Understand the relationship between sales, and estimated sales (Esales).
3. Product Insights: Identify which product lines contribute most to the overall sales.
4. Geographical Analysis: Examine sales distribution across different countries and territories (EMEA).
5. Business Decision Support: Provide insights that can aid business decisions regarding product focus, pricing strategies, and market expansion.

                                       Tasks
The project tasks include-
                                     Data Loading and Preparation<br>
1. Import the dataset into Power BI and review data integrity.
2. Ensure that all columns are properly formatted (e.g., dates are formatted correctly, numerical fields such as "Sales" and "Unit Price" are usable for analysis)
                                     Data Cleaning<br>
1. Handle missing or incomplete data (e.g., missing values in the "State" field where it says "No information").
2. Filter out irrelevant data and remove duplicates if any.
3. Change data type, rename columns, replace values, reorder columns, sort rows
                                     Data Transformation
1. Create calculated columns such as total sales per year or profit if needed.
2. Format "Order Date" and "Delivery Date" fields to proper date format for date-based analysis.
                                     Data Visualizations
1. Sales by Country: A bar chart to display the Count of sales orders per country.
2. Sales vs Esales: A comparison of actual sales and estimated sales
3. For each order use a clustered bar chart.
4. Deal Size: A pie chart to show the sum of order numbers by deal size.
5. Product Line Analysis: A stacked column chart to show the contribution of each product line to the Count of sales orders.
7. Sales Over Time: A line chart showing sales trends over the years.
8. Order Status Breakdown: A stacked column chart to visualize the different territories performing (sales, territories, etc.)

                                      Dashboard  & Report Creation
![Vechiles Data](https://github.com/user-attachments/assets/6253d7e4-e828-4da8-8d7e-0d9d2aeed739)

We can create a dashboard element where all of this information is summarized on one page. Combine all visualizations into a cohesive dashboard that allows users to interact with the data through filters and slicers (e.g., by year).<br>
In this vehicle's dataset report using Power BI, you aim to create an interactive experience where clicking on any company will reveal detailed information about the company, its location, sales data, product information, and more. Here's how you can approach and explain the features of this report in detail:

                                      Interactive Report Features
01. Company-Level Details:
Click on Any Company: By selecting a company from the dataset (using a slicer or clickable visual element such as a table or chart), Power BI will automatically display complete details about that company.
Location: Country, state, city, territory, and full address (e.g., "C/Moralzarzal/86, Madrid, Spain").
Owner Name: First and last name of the owner (e.g., "Diego Freyre").
Phone Number: Contact information for the company.
Postal Code: ZIP code of the company’s location.

02. Order and Delivery Tracking:
Order Date & Delivery Date: Power BI will show when a vehicle was ordered and when it was delivered for each specific company, allowing you to track the efficiency of orders and shipments.
Order and Delivery Timeline: A visual timeline could be included to show how long the delivery process takes for each company.

03. Sales and Pricing Information:
Total Sales and Estimated Sales (Esales): You can see the exact sales figures alongside estimated sales for that company. This helps in understanding if actual sales match or deviate from forecasts.
Unit Price: The price per unit sold.
Retail Price: The listed retail price of the product, allows you to compare it to the unit price to see if there are any discounts or price markups.

04. Product and Deal Information:
Product Details: You can view the products purchased from the company:
Most Purchased Product: Using a pie chart or bar chart, you can see which product has the highest number of sales or sales value.
Product Line: Whether the company is dealing in "Classic Cars" or any other product category.
Deal Size: Indicate whether the deal was classified as "Medium" or any other category (small, large).

05. Location Visualization:
Map Integration: You can integrate Power BI's map visualization feature to automatically display the location of the selected company. When you click on a company, the location is shown on a map based on its city, state, and country. This helps in quickly visualizing where the company is located in the world.

06. Product Sales by Size:
Deal Size Breakdown: You can create a chart to show sales by deal size, such as medium, small, or large. This will help identify which deal sizes are generating the most revenue.

**7. Filtering by Products or Territories:**
You can filter the report by specific product lines (e.g., "Classic Cars") or territories (e.g., EMEA), which will automatically update all the related visuals like sales, order dates, delivery timelines, and product information.

![Vechile Data - Report](https://github.com/user-attachments/assets/0c10a1e2-4771-4e65-9df5-1f06a23f4782)

**4. Outcomes**
The outcomes of the project include:
Comprehensive Sales Insights: Visualized sales trends across countries, product lines, and years, enabling stakeholders to see which regions and products are performing well.
Performance Comparison: A clear comparison between sales and estimated sales (Esales), helps the company adjust forecasting models and pricing strategies.
 Delivery Efficiency: Insights into the delivery timelines by comparing orders and delivery dates to help the logistics team improve delivery efficiency.
Customer Behavior: An analysis of customer purchasing patterns across different regions and product lines.

**5. Challenges**
Some challenges encountered during the project:
Missing Data: Certain columns like "State" had missing information. The dataset had "No Information" in many state fields, which required thoughtful handling without affecting analysis accuracy.
Date Format Issues: "Order Date" and "Delivery Date" were initially in non-standard formats, requiring transformation into a proper date format for time-series analysis.
Data Consistency: Ensuring consistency in data types, particularly for numerical columns such as "Unit Price", "Sales", and "Esales".

**6. Final Report**
The final report consists of:
A Power BI Dashboard with key visualizations such as:
Sales by Country
Sales vs Esales
Product Line Analysis
Order Status Overview
Sales by year
Countries with the highest vehicle sales
Count of sales orders by product line
How closely Esales match the actual sales
Business Recommendations:
Focus on countries or regions with the highest sales potential for future marketing strategies.
Improve delivery logistics to reduce delays.
Review pricing strategies for underperforming product lines

**Conclusion**
This interactive report allows stakeholders to:
Access detailed company information in one click.
Visualize sales data, product purchases, and delivery performance in a structured format.
Filter data dynamically to compare different companies, products, and territories.
Track order-to-delivery timelines to assess efficiency. This comprehensive view will help make strategic decisions on marketing, product development, and logistics management.



