# Restaurant Sales Analysis using Spark in Databricks

This project is an end-to-end data analysis pipeline for restaurant sales data using Apache Spark in Databricks. It includes various analyses and visualizations such as customer spending, menu pricing, customer visits, category sales, and time-based sales trends.

## Table of Contents
- [Project Description](#project-description)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Project Description
The purpose of this project is to perform a comprehensive analysis of restaurant sales data. The analysis includes:
1. **Customer Spending:** Analyzing the spending patterns of customers.
2. **Menu and Pricing Extraction:** Extracting the menu items and their prices.
3. **Customer Visits:** Tracking the number of visits by customers to the restaurant.
4. **Category Sales:** Analyzing sales based on different product categories.
5. **Time-based Sales Trends:** Analyzing monthly, quarterly, and yearly sales trends.
6. **Ordered Products:** Analyzing the most frequently ordered products.

This project is implemented using PySpark in Databricks, and the visualizations are generated within the Databricks environment.

## Installation
To run this project, you need to have the following installed:
- Python 3.x
- Apache Spark
- Databricks account

### Steps to Install
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/your-repo-name.git
    ```
2. Change to the project directory:
    ```sh
    cd your-repo-name
    ```
3. Install the required Python packages:
    ```sh
    pip install -r requirements.txt
    ```
4. Upload the Jupyter notebook to your Databricks workspace.

## Usage
To use this project, follow these steps:

1. Log in to your Databricks account.
2. Upload the `End to End Project.ipynb` notebook to your Databricks workspace.
3. Attach the notebook to a cluster.
4. Run the cells sequentially to execute the data processing and analysis pipeline.
5. Visualizations will be generated within the Databricks environment.

## Features
- **Customer Spending:** Analyzes how much customers spend on average and identifies high-spending customers.
- **Menu and Pricing Extraction:** Extracts the menu items and their respective prices from the sales data.
- **Customer Visits:** Tracks the frequency of customer visits to the restaurant.
- **Category Sales:** Provides insights into sales based on different product categories.
- **Time-based Sales Trends:** Analyzes sales data to identify trends over different time periods (monthly, quarterly, yearly).
- **Ordered Products:** Identifies the most popular products ordered by customers.

## Note
To view the visualizations, the notebook should be run on Databricks, as this project is implemented using Spark in Databricks.

