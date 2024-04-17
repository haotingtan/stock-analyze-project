# Stock Analyze Project

## Overview

This project is designed to parse financial data from HTML sources, specifically focusing on Tesla and GameStop's annual and quarterly revenue. It aims to extract, clean, and present Tesla and GameStop's revenue data in a structured format, enabling further financial analysis and visualization.

## Features

- **Data Extraction**: Uses BeautifulSoup to parse HTML content and extract relevant tables containing ticker's revenue data.
- **Data Transformation**: Cleans and transforms the extracted data using pandas, preparing it for analysis. This includes removing unnecessary characters like dollar signs and commas.
- **Data Analysis**: (Optional) Perform basic financial analysis to track ticker's revenue trends over the years.

## Installation

To run this project, you need Python 3.x and the following Python packages:
- BeautifulSoup4
- pandas
- yfinance
- requests
- plotly

You can install the required packages using pip:

```bash
pip install beautifulsoup4 pandas
```
