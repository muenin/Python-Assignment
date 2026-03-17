# Extracting and Visualizing Stock Data

## Project Overview
This project focuses on extracting essential stock and revenue data for **Tesla (TSLA)** and **GameStop (GME)**. By combining API data extraction and web scraping, the goal is to visualize the relationship between a company's historical share price and its quarterly revenue.

## Features
* **Financial Data Extraction**: Utilized the `yfinance` library to retrieve historical stock prices.
* **Web Scraping**: Used `BeautifulSoup` and `Pandas` to extract revenue data from HTML tables.
* **Data Cleaning**: Processed raw web data by removing special characters ($, commas) and handling missing values.
* **Visualization**: Developed a custom dashboard using `Matplotlib` to overlay share price and revenue trends.

## Technologies Used
* **Python 3**
* **Pandas**: For data manipulation and tabular analysis.
* **yfinance**: For stock market data.
* **BeautifulSoup4 / requests**: For web scraping.
* **Matplotlib**: For data visualization.

## Key Insights
* The project highlights how stock prices often fluctuate independently of quarterly revenue reports.
* Visualized Tesla's growth and the GameStop "short squeeze" period of early 2021.

## How to Run
1. Clone this repository.
2. Install dependencies: `pip install yfinance pandas requests bs4 matplotlib`.
3. Open the Jupyter Notebook `Stock_Analysis.ipynb` and run all cells.
