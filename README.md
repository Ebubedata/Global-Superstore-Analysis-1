# Global-Superstore-Analysis-
### Description
The Global Superstore dataset contains detailed information on sales, customers, products, shipping, and regions across global markets.


### Business Objectives 
- Analyze sales trends across regions and products
- Identify top-performing and underperforming products, countries, and operational markets
- Evaluate sales distribution across customer segments
- Assess sales performance by product categories and sub-categories
- Identify top revenue-generating customers
### Tools Used
- Microsoft Excel – data exploration, pivot tables, and dashboard creation
- Power Query – data cleaning, transformation, and preparation
- Power Pivot (Data Model) – relationship modeling and DAX measures
- Pivot Tables & Charts – data aggregation and visualization
### Data Analysis Process 
Step 1. Data Cleaning (Power Query)
- Removed blank values and duplicate records
- Corrected data types for dates, numeric, and categorical fields
- Removed unnecessary columns
- Imported an updated dataset with accurate order and ship dates

Step 2. Data Modeling
- Created dimension tables: Location, Orders, Customers, Products, Calendar
- Loaded all tables into the Excel Data Model
- Established relationships using Power Pivot (fact–dimension model)
  
Step 3. Delivery Date Column
- Created a Delivery Time column by calculating the difference between ship date and order date
- Converted delivery duration into days for KPI analysis
  
Step 4. KPI Development
  Key metrics developed include:
- Total Sales
- Total Profit
- Total Quantity Sold
- Total Orders
- Total Customers
- Average Delivery Time
  
Step 5. Visualization & Dashboarding
  Built an interactive dashboard with slicers for:
- Region
- Year
- Ship Mode
- Category
### Insights
- Technology products drive revenue, with Phones consistently generating the highest sales across all years, followed by Copiers.
- Sales performance varies significantly by market, as APAC and EU lead in revenue, while EMEA and Africa underperform.
- The United States dominates country-level sales, whereas Tajikistan records the lowest sales, indicating uneven geographic demand.
- Consumer customers are the primary revenue contributors, outperforming Corporate and Home Office segments.
- Sales show steady growth over time, with the Central region maintaining the highest sales each year and overall upward trends across regions and products.
- Operational efficiency is strong, with an average delivery time of 4 days, supporting timely order fulfillment and customer satisfaction.
### Recommendation
- Invest more in high-performing products such as Phones and Copiers
- Strengthen sales and marketing strategies in underperforming markets like EMEA and Africa
- Review pricing, discount, and promotion strategies for low-performing products
- Focus on Technology category expansion due to its strong revenue contribution
- Optimize shipping and fulfillment processes to further reduce delivery time
