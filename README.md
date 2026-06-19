Used Car Market Data Analysis

Project Overview
This project focuses on cleaning, analyzing, and visualizing a used car dataset using Python and Pandas. The raw dataset contained missing values, inconsistent formatting, and non-numeric data that required preprocessing before meaningful analysis could be performed.

The goal was to explore pricing trends, identify high-value brands, and understand how factors such as fuel type and vehicle usage influence car prices.

Tools Used
Python
Pandas
Matplotlib
Jupyter Notebook

Data Cleaning Process

Data Type Conversion
Converted Price and kms_driven columns from text format to numeric values.
Removed commas, units, and invalid text entries.

Handling Missing Values
Filled missing mileage values using the median.
Filled missing fuel type values using the mode.

Data Filtering
Removed records containing invalid price values such as "Ask For Price".
Ensured all numerical columns were suitable for analysis and visualization.

Analysis Performed
1. Average Price by Fuel Type
Analyzed how vehicle prices vary across different fuel types.

2. Top 5 Most Expensive Car Brands
Calculated the average selling price of each brand and identified the top five highest-valued companies.

3. Price Distribution Analysis
Explored the overall distribution of car prices using a histogram to understand market pricing patterns.

4. Kilometers Driven vs Price
Investigated the relationship between vehicle usage and selling price through scatter plot visualization.

Visualizations
Average Price by Fuel Type
Bar chart comparing average vehicle prices across fuel categories.

Top 5 Most Expensive Brands
Bar chart highlighting the highest-priced car brands based on average listing price.

Price Distribution
Histogram showing the frequency distribution of car prices.

Kilometers Driven vs Price
Scatter plot illustrating how mileage relates to vehicle price.

Key Insights
Certain fuel types command higher average prices than others.
Premium brands consistently maintain higher market values.
Vehicle prices are not evenly distributed, with a concentration in specific price ranges.
Higher mileage generally shows a tendency toward lower vehicle prices, although exceptions exist.
Business Impact

This analysis can help:
Buyers understand fair market pricing.
Sellers price vehicles more competitively.
Dealerships identify valuable vehicle segments.
Businesses gain insights into pricing trends within the used car market.
