# USA Regional Sales Analysis

## 🗂️ Project Summary
This EDA notebook dives into Acme Co.’s 2014–2018 USA sales dataset through:

*   **Data Profiling & Cleaning:** Verified schema, handled missing budgets, and corrected data types.
*   **Univariate & Bivariate Analysis:** Explored distributions (revenue, margin, unit price), product/channel/region breakdowns, and customer segments.
*   **Trend & Seasonality:** Charted monthly and yearly sales patterns, highlighting recurring surges and dips.
*   **Outlier Detection:** Identified extreme transactions at both ends of the revenue and unit-price spectra.
*   **Correlation & Segmentation:** Assessed relationships between key metrics and clustered customers by revenue vs. profit margin.

## ❓ Problem Statement
Analyze Acme Co.’s 2014–2018 sales data to identify key revenue and profit drivers across products, channels, and regions; uncover seasonal trends and outliers; and align performance against budgets. Use these insights to optimize pricing, promotions, and market expansion for sustainable growth and reduced concentration risk.

## 🎯 Objective
Deliver actionable insights from Acme Co.’s 2014–2018 sales data to:

*   Identify top-performing products, channels, and regions driving revenue and profit
*   Uncover seasonal trends and anomalies for optimized planning
*   Spot pricing and margin risks from outlier transactions
*   Inform pricing, promotion, and market-expansion strategies

These findings will guide the design of a Power BI dashboard to support strategic decision-making and sustainable growth.

## 📥 Setup & Configuration
The analysis is performed using Python with the following libraries:
*   pandas
*   numpy
*   matplotlib
*   seaborn

## 🔄 Data Ingestion
The dataset is provided as an Excel file (`Regional Sales Dataset.xlsx`) with multiple sheets:
*   Sales Orders
*   Customers
*   Products
*   Regions
*   State Regions
*   2017 Budgets

## 🔍 Data Profiling / Initial Inspection
A preliminary inspection of the data is performed to understand the shape and structure of each dataset.

## 🧹 Data Cleaning & Wrangling
The data is cleaned and wrangled by:
*   Merging the different sheets into a single DataFrame.
*   Renaming columns for clarity and consistency.
*   Handling missing values.
*   Converting data types.

## 🛠 Feature Engineering
New features are created to facilitate the analysis, such as:
*   `total_cost`
*   `profit`
*   `profit_margin_pct`
*   `order_month_name`
*   `order_month_num`
## 📊 Dashboard
Here are some screenshots of the Power BI dashboard:

### Page 1
![Page 1](Background/Page%201.png)

### Page 2
![Page 2](Background/Page%202.png)

### Page 3
![Page 3](Background/Page%203.png)

### Additional Image
![Additional Image](Background/1.jpg)

