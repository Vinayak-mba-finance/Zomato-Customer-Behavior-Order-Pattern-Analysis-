Detailed Project Description 

The “Zomato Customer Behavior & Order Pattern Analysis” project is designed as a complete, Excel-based data analytics case study that mimics the challenges a data analyst might face in a real food delivery or e-commerce company. The core objective is to understand how customers interact with the Zomato platform: what they order, when they order, how much they spend, and which factors influence their ordering decisions.
The project starts with a raw dataset containing sample order-level information. Typical columns include Order ID, Customer ID, Restaurant Name, City, Order Date & Time, Cuisine Type, Payment Method, Order Amount, Delivery Time, Ratings, and more. The first step is data cleaning and preprocessing entirely in Excel. This involves handling missing values, standardizing city and restaurant names, correcting inconsistent date and time formats, splitting combined fields (for example, separating date and time), and transforming data types so that Excel formulas and Pivot Tables can be applied correctly.
Once the data is cleaned, the next step is to create structured tables using Excel’s “Format as Table” feature. This allows the analyst to work efficiently with filters, slicers, and dynamic ranges. Additional helper columns are created using formulas to derive new fields such as:
•	Order Day (Monday–Sunday)
•	Order Slot (Breakfast, Lunch, Evening, Late Night) based on time
•	Order Month and Year
•	Order Value Categories (Low, Medium, High) using nested IF or IFS functions
•	Customer Tenure and Frequency metrics (for example, total number of orders per customer)

The analytical phase of the project heavily uses Pivot Tables and Pivot Charts. Several key business questions are answered using these tools, such as:

•	Which days and time slots see the highest number of orders?
•	Which cities contribute the most revenue and volume?
•	Which restaurants and cuisines are most popular by number of orders and by revenue?
•	What is the average order value across different customer segments?
•	How do ratings correlate with order value or delivery time?

Multiple Pivot Tables are created to break down orders by city, cuisine, payment method, and time of day. Slicers and timelines are added on dimensions such as City, Month, and Cuisine to enable interactive exploration of the data.
A key part of the project is developing KPIs (Key Performance Indicators) that a business stakeholder or manager would care about. These KPIs might include:

•	Total Orders
•	Total Revenue
•	Average Order Value
•	Repeat Customer Rate (percentage of customers who placed more than one order)
•	Top 5 Restaurants by Revenue
•	On-time Delivery Rate (if such data is included)

These KPIs are calculated using a mix of Excel formulas such as SUMIFS, COUNTIFS, AVERAGEIFS, VLOOKUP / XLOOKUP, and logical formulas. The results are then summarized on a dedicated Dashboard sheet.
The Dashboard is designed to look and behave like a professional business report. It typically includes:

•	High-level KPI cards at the top (Total Orders, Revenue, AOV, etc.)
•	Trend charts showing orders and revenue over time
•	A bar chart of top-performing cities and restaurants
•	A donut or bar chart of order distribution by cuisine type
•	Filters/slicers to dynamically view metrics by city, time period, cuisine, or payment method
Conditional formatting is used to highlight key patterns, such as very high-value orders, low ratings, or days with unusually low or high volume. Color scales and data bars are deployed in some sheets to quickly show trends without the need for charts.
From a data analyst perspective, this project demonstrates a complete end-to-end workflow: from cleaning and transforming raw data, to building intermediate analytical tables, to presenting insights in a visually appealing and easy-to-understand format. It shows how Excel alone can be used to perform serious business analysis, even before moving to tools like SQL, Power BI, or Python.
The final output is an Excel file that a hiring manager or interviewer can easily open to see your approach to structuring data, building calculations, and telling a story with numbers. The project not only highlights your Excel skills but also your ability to think like a business analyst, focusing on customer behavior, performance metrics, and actionable recommendations.

What’s Inside the Excel (Sheets Overview)

1. Raw_Data
This sheet holds the original, unmodified Zomato order data.
•	Columns might include: Order_ID, Customer_ID, Restaurant_Name, City, Order_DateTime, Cuisine_Type, Payment_Method, Order_Amount, Delivery_Time_Minutes, Rating, etc.
•	Purpose: Keep an untouched copy of the dataset for reference and auditing.

2. Data_Cleaned
This is the transformed version of the raw data.
•	Cleaned and standardized city and restaurant names.
•	Date and time split into separate columns (Order_Date, Order_Time).
•	Additional helper columns like:
•	Order_Day (weekday name)
•	Order_Month, Order_Year
•	Time_Slot (Breakfast, Lunch, Evening, Late Night)
•	Order_Value_Bucket (Low/Medium/High)
•	All data formatted as an Excel Table for easier analysis.

3. Customer_Summary
Customer-level aggregated view.
•	Each row is one customer.
•	Metrics:
•	Total Orders per Customer
•	Total Spend
•	Average Order Value per Customer
•	First Order Date, Last Order Date
•	Days Between First and Last Order (Customer Tenure)
•	Segment (New / Returning / Loyal) based on frequency and tenure.

4. Restaurant_Summary
Restaurant-level performance view.
•	Each row is one restaurant.
•	Metrics:
•	Total Orders
•	Total Revenue
•	Average Rating
•	Average Delivery Time
•	Top Cuisine Type per Restaurant
•	Helps identify top-performing restaurants and underperformers.

5. Pivot_Analysis
Collection of Pivot Tables used for exploration. Example Pivot Tables:
•	Orders by City vs Month
•	Orders and Revenue by Time Slot and Day of Week
•	Revenue by Cuisine Type and Payment Method
•	Average Rating vs Order Value buckets These Pivot Tables feed into charts or can be used standalone for ad-hoc analysis.

6. Charts
Clean area where you place charts built from Pivot Tables or data tables.
•	Line chart of Orders/Revenue trend over time
•	Bar chart of Top 10 Restaurants by Revenue
•	Column chart of Orders by Day of Week
•	Donut/pie chart of Orders by Cuisine Type These can be linked to slicers (from Pivot Tables) for interactivity.

7. Dashboard
The final, presentation-ready sheet.
•	KPI tiles at the top (cards with big numbers).
•	Combined charts laid out cleanly to tell a story.
•	Slicers for City, Month, Cuisine, and Customer Segment.
•	Designed for non-technical stakeholders: minimal clutter, clear labels, and formatted numbers.
You can name sheets slightly differently if you prefer, but this structure is clear and recruiter-friendly.
