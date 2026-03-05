# EazyDiner Restaurant Data Analysis (Web Scraping + EDA)

## Project Overview

This project focuses on collecting restaurant data from the EazyDiner platform using web scraping and performing data cleaning and exploratory data analysis (EDA) to extract meaningful business insights.

The project demonstrates the complete data science workflow including data collection, preprocessing, analysis, and visualization using Python.

## Problem Statement

The objective of this project is to analyze restaurant data to understand patterns in restaurant ratings, pricing, locations, and services. The analysis helps identify factors that influence restaurant popularity and customer ratings.

## Data Collection

Data was collected using web scraping techniques in Python.
Relevant restaurant information such as name, rating, cuisine, location, and price range was extracted from the website.

The scraped data was converted into a structured dataset and exported into CSV format for further analysis.

## Data Cleaning

The dataset was cleaned to improve data quality. The following steps were performed:

* Removing special characters
* Handling missing values
* Converting data types
* Fixing column names
* Removing duplicate records
* Formatting numerical and categorical features

## Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand the dataset and identify trends.

The analysis included:

* Univariate analysis of numerical and categorical variables
* Bivariate analysis to study relationships between variables
* Distribution analysis of restaurant ratings and prices
* Category-wise restaurant counts
* Location-based restaurant distribution

## Data Visualization

Various visualization techniques were used to better understand the data:

* Bar charts
* Count plots
* Histograms
* Box plots
* Scatter plots
* Correlation heatmaps

These visualizations help reveal patterns and trends in the restaurant dataset.

## Key Insights

* Some locations have a significantly higher number of restaurants compared to others.
* Restaurant ratings tend to cluster around mid to high rating ranges.
* Certain cuisines are more common and popular in the dataset.
* Price range varies across different locations and restaurant categories.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* BeautifulSoup
* Requests
* Jupyter Notebook

## Project Structure

```
EazyDiner-Data-Analysis
│
├── data
│   └── eazydiner_restaurants.csv
│
├── notebooks
│   ├── EazyDinner_Webscraping.ipynb
│   └── EazyDiner_Analysis.ipynb
│
└── README.md
```

## How to Run the Project

1. Clone the repository
2. Install required libraries
3. Run the web scraping notebook to collect data
4. Run the analysis notebook to perform EDA and visualizations

## Conclusion

This project demonstrates how web scraping and exploratory data analysis can be used to extract insights from restaurant data. The workflow highlights practical applications of Python for real-world data science problems.
