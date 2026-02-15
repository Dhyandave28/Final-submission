# Extracting and Visualizing Stock Data

## Description
This project demonstrates the extraction of essential stock and revenue data for analysis and visualization. By comparing historical share prices and company revenue, users can make informed, data-driven decisions.

## Table of Contents
* **Define Graphing Function**: Implementation of the `make_graph` function.
* **Tesla Stock Data**: Extraction using the `yfinance` library.
* **Tesla Revenue Data**: Extraction via web scraping with `BeautifulSoup`.
* **GameStop Stock Data**: Extraction using the `yfinance` library.
* **GameStop Revenue Data**: Extraction via web scraping.
* **Data Visualization**: Plotting dashboards for both Tesla and GameStop.

## Prerequisites
The following Python libraries are required:
* `yfinance`: For historical stock data.
* `pandas`: For data manipulation and DataFrames.
* `requests`: To fetch web pages for scraping.
* `bs4` (BeautifulSoup): To parse HTML revenue tables.
* `plotly`: For building interactive dashboards.
* `matplotlib`: For general plotting needs.

## Key Features

### Automated Visualization
The project includes a custom function, `make_graph`, which generates an interactive, two-panel dashboard:
* **Upper Graph**: Displays "Historical Share Price".
* **Lower Graph**: Displays "Historical Revenue".
* **Interactivity**: Includes a range slider and shared x-axes to synchronize time-period analysis.


### Data Extraction Methods
* **API Integration**: Uses `yfinance.Ticker` to extract full historical price data (set to `period="max"`).
* **Web Scraping**: Retrieves revenue data by parsing financial websites into clean Pandas DataFrames.

## Usage
1. **Install Dependencies**: Execute the library installation cells at the start of the notebook.
2. **Define Tools**: Run the `make_graph` function definition.
3. **Run Analysis**: Execute the extraction cells for Tesla or GameStop and pass the resulting data to the graphing function to view the dashboard.

---
