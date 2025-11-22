# ☕ Retail Shop Case Study: Coffee Sales Dashboard Analysis

## Table of Contents
* [Project Overview](#project-overview)
* [Dashboard](#dashboard)
* [Data Source](#data-source)
* [Tools](#tools)
* [Data Cleaning/Preparation](#data-preparation)
* [Exploratory Data Analysis](#exploratory-data-analysis)
* [Data Analysis](#data-analysis)
* [Results](#results)
* [Recommendations](#recommendations)
* [Acknowledgement](#acknowledgement)

## Project Overview
This project demonstrates proficiency in data cleaning, aggregation, and visualization within Microsoft Excel to transform raw sales data into actionable business intelligence. The resulting dashboard provides leadership with interactive tools to monitor sales performance, identify key customer segments, and track product trends over time. 

## Dashboard
The final dashboard is a clean, visually thematic report designed for quick consumption. The design features a coffee-themed color palette and multiple slicers to improve comprehension and accessibility of the data.
* Trend Analysis: An interactive Line Chart visualizing Total Sales Over Time broken down by coffee type.
* Segmentation: Bar Charts detailing Sales by Country and Top 5 Customers.
* Interactivity: All visuals are dynamically controlled using Slicers (Roast Type, Size, Loyalty Card) and an Order Date Timeline.

<img width="1597" height="849" alt="dashboard" src="https://github.com/user-attachments/assets/2c511f1f-a328-43d8-a041-899be3190e6b" />

## Data Source
* **Workbook:** [coffeeOrdersData.xlsx](https://github.com/user-attachments/files/23690917/coffeeOrdersData.xlsx)
* Primary Data: Fictional sales dataset containing detailed transactional records, including order date, customer ID, product details, and sales amount.
* Secondary Data: Separate tables containing Customer and Product reference details (used for VLOOKUP/INDEX MATCH).

## Tools
* Primary Tool: Microsoft Excel (2016+)
* Version Control: Git & GitHub

## Data Cleaning/Preparation
This stage focused on establishing a clean, structured, and consistent dataset ready for Pivot Table analysis.

Data Gathering & Transformation:
* Gathered customer data (customer name, customer email, customer country, loyalty card) using **XLOOKUP/IF** statements.
* Used **INDEX/MATCH** to retrieve corresponding product details (coffee type, roast type, size, unit price).

Conditional Logic & Standardization:
* Created Coffee Type Name and Roast Type Name columns using **nested IF functions** to standardize product naming.
* Formatted the Order Date column to ensure consistency across European and American date formats.

Formatting & Quality Control:
* Formatted the Size column to include the (kg) metric for clarity.
* Formatted Unit Price and Sales columns to USD currency.
* Checked for and addressed duplicate entries to ensure data integrity.
<img width="309" height="251" alt="no_duplicates" src="https://github.com/user-attachments/assets/9c228ca3-d979-406a-b7b4-f389299920a9" />

## Exploratory Data Analysis
Initial data review was conducted to understand distribution and potential anomalies prior to visualization:
* Sales Concentration: Identified that the United States accounts for 79% of total sales, necessitating the use of relative trend comparisons rather than focusing solely on absolute figures.
* Loyalty Gap: Confirmed a significant gap in customer loyalty, with less than half of customers utilizing the loyalty program. This finding was prioritized for the final recommendations.
* Trend Confirmation: Validated that the time series data did not contain significant outliers, confirming the suitability of the line chart for trend analysis.

## Data Analysis
* Pivot Table Construction: Created two primary Pivot Tables to generate the underlying data for the dashboard's visuals:
1. Time Series: Pivot Table structured by Month/Year for trend plotting.
2. Customer/Country: Pivot Tables used for ranking and segmenting data.
* **Time-Based Calculations:** Utilized date functions to calculate Year-over-Year (YoY) growth and compare performance across periods (e.g., Q3 2021 vs. Q3 2020).
* **Dynamic Filtering:** All Pivot Tables were connected to the Slicers and Timeline filter using the **Report Connections** feature, enabling full user interactivity.

## Results
* **Overall Performance:** Total sales achieved $45,134 over the 3.5 year period. While 2019 saw a slight drop at -0.57% YoY, 2021 came back swinging with a 13.60% YoY growth, indicating successful strategy implementation in the later half of the period. 
* **Top Performer:** The United States generated the highest revenue, contributing 79% of total sales, indicating a strong share in the market.

<img width="645" height="241" alt="image" src="https://github.com/user-attachments/assets/6abf46af-40d4-4126-89e4-361a7aac082f" />

* **Loyalty Impact:** Customers holding a loyalty card accounted for only 46% percent of sales, signaling a needed adjustment in strategy to improve customer retention. 
* **Emerging Trend:** Liberica sales, while lower in volume, showed the most explosive growth in the most recent two quarters.

## Recommendations
The following actionable strategies are recommended based on data findings:
1. **Improve Customer Retention:** Currently, 53% of customers are not signed up with the loyalty program. I recommend increasing the marketing budget for personalized campaigns incentiving loyalty program signups, increasing the customer retention rate.
2. **Investigate Growth Drivers:** Deep dive into the sales strategies in Ireland to identify successful tactics that can be replicated in this underperforming market.

## Acknowledgement
This project was completed as part of a tutorial, the initial dashboard design and data was provided by the original creator. I want to give full credit to the original creator.

* **Author:** [[Mo Chen](https://www.youtube.com/@mo-chen)]
* **Tutorial:** [[Tutorial Link](https://www.youtube.com/watch?v=m13o5aqeCbM)]


