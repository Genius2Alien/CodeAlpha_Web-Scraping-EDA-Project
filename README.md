# CodeAlpha_Web-Scraping-EDA-Project
Python web scraping and exploratory data analysis of 100 books
# Web Scraping and Exploratory Data Analysis

## Project Overview

This project uses Python to scrape book information from Books to Scrape and perform exploratory data analysis on the collected dataset.

## Objectives

- Retrieve book information from a public website.
- Extract titles, prices, ratings, availability, and book URLs.
- Create a structured dataset using Pandas.
- Explore price and rating distributions using visualizations.
- Test whether book-price distributions differ across rating groups.
- Identify potential data-quality issues and outliers.

## Tools and Technologies

- Python
- Requests
- BeautifulSoup
- Pandas
- Matplotlib
- SciPy
- Google Colab

## Dataset

The dataset contains 100 book records with the following columns:

- `Title`
- `Price`
- `Rating`
- `Availability`
- `Book_URL`
- `Price_numeric`

## Key Findings

- Total records analyzed: 100.
- Mean book price: £34.56.
- Median book price: £34.78.
- No missing values or duplicate records were detected in the checks performed.
- The IQR method identified no potential price outliers.
- The Kruskal–Wallis test returned H = 2.6655 and p = 0.6153, providing no statistically significant evidence of price-distribution differences across rating groups at the 5% significance level.

## How to Run

1. Download or clone this repository.
2. Open `Web_Scraping_Project.ipynb` in Google Colab or Jupyter Notebook.
3. Install the required libraries if they are not already available.
4. Run the notebook cells in order.

## Data Source

[Books to Scrape](https://books.toscrape.com/)

The website is commonly used for educational web-scraping practice.

## Disclaimer

This is an educational project developed for learning web scraping, data cleaning, visualization, and exploratory data analysis.
