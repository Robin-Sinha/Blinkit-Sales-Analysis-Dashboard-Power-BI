📊 Blinkit Sales Analysis Dashboard | Power BI
📌 Project Overview

This project presents an interactive Blinkit Sales Analysis Dashboard built in Power BI to analyse sales performance across products, outlet types, outlet locations and customer ratings. The dashboard helps identify key business trends and supports data-driven decision making through interactive visualisations and KPIs.

🎯 Business Requirement

The objective of this project is to analyse Blinkit's sales data and provide insights into:

Overall business performance
Product category performance
Outlet performance
Customer satisfaction
Sales trends over time
Outlet segmentation
📈 Key Performance Indicators (KPIs)

The dashboard tracks four major KPIs:

💰 Total Sales
📊 Average Sales
📦 Number of Items Sold
⭐ Average Rating
📊 Dashboard Visualisations
1. Total Sales by Fat Content

Chart: Donut Chart

Objective:

Analyse the impact of item fat content on total sales.
2. Total Sales by Item Type

Chart: Horizontal Bar Chart

Objective:

Identify the best-performing product categories.
3. Fat Content by Outlet

Chart: Stacked Column Chart

Objective:

Compare sales across different outlet segments based on fat content.
4. Sales by Outlet Establishment Year

Chart: Line Chart

Objective:

Analyse how outlet establishment year influences sales performance.
5. Sales by Outlet Size

Chart: Donut Chart

Objective:

Evaluate sales contribution by outlet size.
6. Sales by Outlet Location

Chart: Funnel Chart

Objective:

Compare sales across Tier 1, Tier 2, and Tier 3 outlet locations.
7. All Metrics by Outlet Type

Chart: Matrix

Objective:
Provide a comprehensive comparison of:

Total Sales
Average Sales
Number of Items
Average Rating

across different outlet types.

📂 Dataset Information

The dataset contains:

Rows: 8,523 records (8,524 including header)
Columns: 12
Dataset Fields
Item Fat Content
Item Identifier
Item Type
Outlet Establishment Year
Outlet Identifier
Outlet Location Type
Outlet Size
Outlet Type
Item Visibility
Item Weight
Sales
Rating
🔄 Data Import

The data was imported into Power BI using:

Get Data
Excel Workbook
Load Data
🧹 Data Cleaning (Power Query)

Data cleaning was performed using Power Query Editor.

Quality Checks
Converted source data into Excel Table format
Checked for spelling inconsistencies
Verified categorical fields
Checked for missing values
Reviewed column quality
Removed inconsistencies
Value Standardisation
Original Value	Updated Value
LF	Low Fat
reg	Regular
low fat	Low Fat

All transformation steps were automatically recorded in Applied Steps, ensuring the cleaning process remains dynamic and repeatable whenever the dataset is refreshed.

📏 Data Quality Validation

Column Quality was used to verify:

✅ Valid values
❌ Errors
⚪ Empty values

Null values and inconsistent records were reviewed before building the dashboard.

📐 Dashboard Design

The dashboard was designed using:

Custom canvas size
Shapes
Titles
Icons
Theme colours
KPI Cards
Interactive layout

The colour palette was inspired by Blinkit's branding (Yellow & Green).

📊 DAX Measures

The following DAX measures were created.

Total Sales
Total Sales =
SUM('Blinkit Grocery Data'[Sales])
Average Sales
Average Sales =
AVERAGE('Blinkit Grocery Data'[Sales])
Number of Items
No of Items =
COUNTROWS('Blinkit Grocery Data')
Average Rating
Average Rating =
AVERAGE('Blinkit Grocery Data'[Rating])
🎛 Interactive Features

The dashboard includes interactive filters for better user experience.

Slicers
Outlet Location Type
Outlet Size
Item Type
Interactive Filtering

Instead of default highlighting, Edit Interactions was used so visuals filter one another, creating a cleaner and more intuitive dashboard experience.

🛠 Tools & Technologies
Power BI Desktop
Power Query
DAX
Microsoft Excel
💡 Key Learnings

This project helped strengthen my understanding of:

Business requirement gathering
Data cleaning using Power Query
Data quality validation
DAX measure creation
Interactive dashboard design
KPI development
Data visualisation best practices
Dashboard formatting
Edit Interactions
Slicers and filtering
Business storytelling using Power BI
📷 Dashboard Preview
<img width="1250" height="701" alt="image" src="https://github.com/user-attachments/assets/4e840d96-f98b-491c-b241-93eb99e2c73e" />
