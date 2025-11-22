# ☕ Retail Shop Case Study: Coffee Sales Dashboard Analysis

## Table of Contents
* [Project Overview](#project-overview)
* [Dashboard](#dashboard)
* [Data Source](#data-source)
* [Tool](#tools)
* [Data Cleaning/Preparation](#data-preparation)
* [Exploratory Data Analysis](#exploratory-data-analysis)
* [Data Analysis](#data-analysis)
* [Results](#results)
* [Recommendations](#recommendations)
* [Acknowledgement](#acknowledgement)

## Project Overview
This project demonstrates proficiency in data cleaning, aggregation, and visualization within Microsoft Excel to transform raw sales data into actionable business intelligence. The resulting dashboard provides leadership with interactive tools to monitor sales performance, identify key customer segments, and track product trends over time.

## Dashboard
<img width="1852" height="976" alt="dashboard" src="https://github.com/user-attachments/assets/7a18139e-12e9-486f-b384-536172fb3e16" />

## Data Source
[coffeeOrdersData.xlsx](https://github.com/user-attachments/files/23690917/coffeeOrdersData.xlsx)

## Tool
Completed entirely in Microsoft Excel

## Data Cleaning/Preparation
This stage focused on establishing a clean, structured, and consistent dataset ready for Pivot Table analysis.

Data Gathering & Transformation:
* Gathered customer data (customer name, customer email, customer country, loyalty card) using XLOOKUP/IF statements.
* Used INDEX/MATCH to retrieve corresponding product details (coffee type, roast type, size, unit price).

Conditional Logic & Standardization:
* Created Coffee Type Name and Roast Type Name columns using nested IF functions to standardize product naming.
* Formatted the Order Date column to ensure consistency across European and American date formats.

Formatting & Quality Control:
* Formatted the Size column to include the (kg) metric for clarity.
* Formatted Unit Price and Sales columns to USD currency.
* Checked for and addressed duplicate entries to ensure data integrity.
<img width="309" height="251" alt="no_duplicates" src="https://github.com/user-attachments/assets/9c228ca3-d979-406a-b7b4-f389299920a9" />

## Data Analysis
* Pivot Table Construction: Created two primary Pivot Tables to generate the underlying data for the dashboard's visuals:
1. Time Series: Pivot Table structured by Month/Year for trend plotting.
2. Customer/Country: Pivot Tables used for ranking and segmenting data.
* Time-Based Calculations: Utilized date functions to calculate Year-over-Year (YoY) growth and compare performance across periods (e.g., Q3 2021 vs. Q3 2020).
* Dynamic Filtering: All Pivot Tables were connected to the Slicers and Timeline filter using the Report Connections feature, enabling full user interactivity.

## Results


## Recommendations


## Acknowledgement
This project was completed as part of a tutorial. I want to give full credit to the original creator.

* **Author:** [[Mo Chen]((https://www.youtube.com/@mo-chen))]
* **Tutorial:** [[Tutorial Link](https://www.youtube.com/watch?v=m13o5aqeCbM)]


