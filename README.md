# Luxury-Car-Dealership-Analysis-PowerBI
## Luxury-Car-Dealership-Report
_This Power BI dashboard was developed to analyze the performance of a luxury car dealership using a provided dataset. It offers key insights into revenue, popular car brands, regional performance, and buying patterns over time_

## Project Overview
>This project showcases an interactive dashboard built using Power BI to analyze the sales and performance data of a high-end luxury car dealership. The primary objective was to clean, transform, and visualize the data in a way that uncovers key business insights, identifies sales trends, and helps stakeholders make informed decisions.
The dataset included information on car models, manufacturers, revenue, transmission types, color, ownership, and geographic distribution. The data was first cleaned and prepared using Power Query, then modeled with relationships and calculated columns using DAX, and finally visualized using intuitive charts and maps in Power BI.

## Tools Used
 + Microsoft Excel (for initial formatting and table creation)
 + Power BI (for data cleaning, modeling, DAX, and dashboard creation)
 + Power Query (for splitting, merging, and transforming data
 
## Business Questions Answered
1. What is the total revenue, average revenue, and number of cars sold?
2. Which car manufacturers are most popular?
3. How does revenue trend over the years?
4. What transmission type generates the most revenue?
5. What are the least popular car colors?
6. Which countries (based on manufacturing company) generate the highest revenue?
7. How does average revenue vary by car ownership history?

## Data Overview
The dataset used for this project was provided by Ifunanya Gabriel as part of a data analysis challenge organized by The Analytics School. It contains 10,000+ rows of data covering various aspects of high-end luxury car sales. The key columns include:
 + Car – Full name of the vehicle (e.g., BMW X5 2021)

 + Manufacturer – The brand of the car (e.g., BMW, AUDI, LEXUS)

 + Model – Extracted from the “Car” column using Power Query

 + Year – The year the car was sold

 + Color – Car color category

 + Transmission – Whether the car is Manual or Automatic

 + Revenue – Amount earned from the sale

 + Owner – Ownership category (e.g., 1st owner, 2nd owner, etc.)

 + Manufacturing Company Table – Provided as a second dataset and merged to get the Country of Manufacture

## Analysis Breakdown
+ Data Cleaning & Preparation:
  + Used Power Query in Power BI to remove duplicates, trim columns, split car names to extract manufacturers, and merge with a reference table for country mapping.

+ DAX Calculations:
  + Created measures including:
  + Total Revenue
  + Average Revenue
  + Car Sold

+ Visual Insights:
  + Bar Chart: Ranked most popular car manufacturers by sales.
  + Pie & Donut Charts: Showed revenue distribution by transmission type and least popular car colors.
  + Line Chart: Analyzed yearly revenue trends.
  + Column Chart: Compared average revenue by ownership category.
  + Map Visualization: Displayed total revenue by manufacturing country using a filled map.

+ Interactivity:
  + Added slicers for Year and Car Model to enhance dynamic exploration of insights.

## Data Source
This dataset was provided by Ifunanya Gabriel as part of the #datachallengewithIfunanyaGabriel and The Analytics School.

## Data Visualization





