# Wine Data Analysis

This project analyzes a dataset of wines, focusing on their price, rating (points), and generating visualizations to help understand the relationships between these factors.
Features

    Load wine data from a CSV file.
    Filter and clean data to focus on relevant columns.
    Calculate a star rating based on points.
    Generate visualizations for insights on wine pricing and star ratings.

Prerequisites

Before running the application, ensure you have the following installed:

    Python 3.x
    pandas library
    matplotlib or any other library for plotting (if you want to visualize data)

Installation

You can install the necessary Python libraries using pip:

bash

pip install pandas matplotlib

Files
1. wine_analysis.py

This file contains the main functionality for analyzing the wine dataset.
Key Functions:

    Load the dataset from wines.csv.
    Select relevant columns: country, name, points, and price.
    Handle missing or zero values in the price column.
    Calculate a star rating based on the points column.
    Find the wine with the highest price.
    Generate a histogram for wine prices under 100.
    Create a scatter plot to visualize the relationship between price and star rating.

2. wines.csv

This CSV file contains data about various wines, including the following columns:

    country: The country of origin.
    name: The name of the wine.
    points: Rating points for the wine.
    price: Price of the wine.
    Additional columns exist but are not used in the analysis.

Usage

    Ensure the wines.csv file is in the same directory as your script.
    Run the analysis script:

    bash

    python wine_analysis.py

    The output will include printed results, a histogram, and a scatter plot.

Example Outputs

    The total number of wines with a star rating of 5.
    The wine with the highest price and its details.
    A histogram showing the distribution of wine prices under $100.
    A scatter plot showing the relationship between price and star rating.
