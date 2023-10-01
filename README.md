# InternshipProjectSem_3
## Smart Phone sales Analysis using Data Visualization in Python

This repository contains Python code for web scraping mobile phone data from Flipkart and performing various data analysis and visualization tasks. Below is an overview of the code and its functionalities.

## Code Overview
The code is divided into several sections, each performing a specific task. Here's an overview of what each section does:

### Web Scraping
* The code uses libraries such as requests, bs4 (Beautiful Soup), and selenium to scrape mobile phone data from the Flipkart website.
* It collects information such as phone names, prices, specifications, discounts, ratings, and more.
* The data is collected across multiple pages by iterating through the search results

### Data Processing
* After scraping, the data is processed to extract relevant information.
* Specifications are extracted, and additional information like RAM, ROM, battery life, camera details, and screen size is parsed from the specifications.
* The data is structured into lists and cleaned, handling missing values.
  
### Data Storage
* The cleaned data is stored in a CSV file named asses.csv.
* The CSV file contains columns like Name, Brand, Price, Discount, Rating, ram, rom, batterylife, front camera, Rear, and size(inch).

### Data Analysis
* The code performs data analysis to categorize mobile phones based on price ranges (e.g., below 5k, below 15k, etc.).
* It creates separate CSV files for different price range categories.
* Missing values in these categories are filled with appropriate values.

### Visualization
* The code uses the Plotly library for data visualization.
* It creates various visualizations, including pie charts, bar charts, scatter plots, and sunburst charts.
* Visualizations include brand-wise market share, average ratings, price vs. discount distribution, and more.

## Data Files
* asses.csv: Contains the cleaned mobile phone data.
* Separate CSV files for different price ranges (e.g., below5k.csv, below15k.csv, etc.) created during data analysis.
  
## Visualizations
* Pie chart showing the market share of mobile phone brands.
* Bar chart comparing brand frequencies.
* Line chart showing brands and their average ratings.
* Bar chart comparing brands vs. price.
* Scatter plots for individual brands (e.g., SAMSUNG, APPLE, NOKIA, etc.).
* Scatter plot showing price vs. discount distribution.
* Sunburst chart displaying mobiles of various brands.
  
