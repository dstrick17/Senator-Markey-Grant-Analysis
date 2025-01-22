# Massachusetts Funding Analysis

## Overview
This Jupyter Notebook conducts a detailed analysis of funding distribution across cities and counties in Massachusetts. It leverages a dataset to explore various metrics, including total funding amounts, population demographics, and median household income. The analysis includes visualizations such as heat maps, scatter plots, and clustering to identify trends and relationships within the data. The data can be found on public github repositories so there is no need to download any csvs to run the code on your own machine.

## Table of Contents
1. [Preliminary Analysis](#preliminary-analysis)
2. [City Statistics](#city-statistics)
3. [Maps](#maps)
4. [Clustering Analysis](#clustering-analysis)
5. [Scatter Plots](#scatter-plots)
6. [Bar Charts](#bar-charts)
7. [Conclusion](#conclusion)

## Preliminary Analysis
- **Data Loading**: Import necessary libraries and load the dataset from a public URL.
- **Data Cleaning**: Remove whitespace and clean the data to ensure accurate analysis.

## City Statistics
- **Aggregation**: Calculate total funding, total population, median household income, and percentage of the population identifying as White for each city.
- **DataFrame Creation**: Create a DataFrame with aggregated statistics and sort the results for better visualization.
- **Funding Per Capita**: Calculate funding per capita and normalize funding for visualization.

## Maps
### Heat Map by County per capita funding
- **Visualization**: Create a heat map visualizing funding per capita by county using Folium and GeoJSON data.
- **Tooltips**: Display tooltips with detailed information on funding, population, and funding per capita.

### Heat Map by City per capita funding
- **Visualization**: Create a heat map visualizing funding per capita by city.
- **GeoJSON Integration**: Use GeoJSON data to enhance interactivity and visualization.

### Heat Map by % of population that identifies as white for each city
- **Visualization**: Create a heat map visualizing racial demographics by city.
- **GeoJSON Integration**: Use GeoJSON data to enhance interactivity and visualization.

### Heat Map by median household income for each city
- **Visualization**: Create a heat map visualizing median household income by city.
- **GeoJSON Integration**: Use GeoJSON data to enhance interactivity and visualization.

### Map by cluster analysis of race and income for cities in Massachusetts
- **Visualization**: Create a heat map visualizing K-means clustering for cities in Massachusetts.
- **GeoJSON Integration**: Use GeoJSON data to enhance interactivity and visualization.

## Clustering Analysis
- **K-means Clustering**: Perform K-means clustering based on the percentage of the population identifying as White and median household income.
- **Elbow Method**: Use the elbow method to determine the optimal number of clusters.
- **Visualization**: Visualize the clusters using scatter plots and color-coded maps.

## Scatter Plots
- **Funding vs. Demographics**: Create scatter plots to analyze relationships between funding per capita and demographic factors such as the percentage of the population identifying as White and median household income.
- **Correlation Analysis**: Calculate correlation coefficients to quantify relationships.

## Bar Charts
- **Funding Distribution**: Generate bar charts to visualize funding distribution by county and funding per capita.
- **Insights**: Provide insights into how funding varies across different counties in Massachusetts.

## Conclusion
This analysis provides valuable insights into the distribution of funding across Massachusetts cities and counties. The visualizations and statistical analyses highlight significant trends and relationships that can inform policymakers and stakeholders in their decision-making processes.

## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `matplotlib`, `folium`, `sklearn`, `requests`

## Usage
1. Clone the repository or download the notebook.
2. Install the required libraries if not already installed.
3. Open the notebook in Jupyter and run the cells sequentially to perform the analysis.
