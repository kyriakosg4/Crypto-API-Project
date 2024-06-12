# Crypto-API-Project

## Introduction
This project involves monitoring cryptocurrency prices over a specified period using a custom Python function. The data is sourced from CoinMarketCap's API. The project uses Jupyter Notebook for data analysis and visualization. The goal is to track price changes and gain insights into the cryptocurrency market.

## Project Overview

1. Setting Up the Environment
The project begins by importing necessary libraries and setting up the environment in Jupyter Notebook.

2. Creating the Function to Monitor Crypto Prices
A function is created to fetch cryptocurrency prices using the CoinMarketCap API. This function:

+ Connects to the API using the provided endpoint.
+ Normalizes the JSON response data using Pandas.
+ Saves the normalized data to a CSV file for further analysis.

### API Information
API Provider: CoinMarketCap
API Documentation: CoinMarketCap API Documentation
API URL: CoinMarketCap API

3. Saving Data to CSV
Each time the function runs, it fetches the latest cryptocurrency data and appends it to a CSV file. This allows for historical data analysis and tracking changes over time. The csv created in my local disk

4. Reading and Exploring the Data in Jupyter
After collecting the data, it is read into Jupyter for exploration. The following steps are performed:

* Grouping and Analyzing Data
The data is grouped by cryptocurrency name.
Price changes are analyzed over various periods (1 hour to 30 days).

* Transforming Data
The stack function is used to transform the data frame.
The data frame is reset and restructured to facilitate correlation analysis.

* Columns are renamed for clarity and ease of use in plotting.
  
5. Data Visualization
The project leverages Seaborn and Matplotlib to create insightful visualizations. Specifically, a categorical plot (catplot) is generated to visualize the data.

# Conclusion
This project demonstrates how to use Python to monitor cryptocurrency prices using an API, store the data for analysis, and visualize the insights. By leveraging Pandas, Seaborn, and Matplotlib, we can gain valuable insights into cryptocurrency price movements over various time periods.
