# Crypto Currency Data Analytics Projects

## Overview

This repository contains multiple Crypto Currency Data Analytics projects developed using:

* Python
* Web Scraping
* Power Query
* Excel
* Pivot Tables
* Charts
* Dashboards
* VBA Automation

The projects are focused on collecting, cleaning, analyzing, and visualizing Crypto Currency market data for investment analysis and business insights.

# Technologies Used

* Python
* Pandas
* BeautifulSoup
* Requests
* Microsoft Excel
* Power Query
* Pivot Tables
* VBA Macros
* Data Visualization

# Data Source

Crypto market data has been collected from:

* CoinMarketCap

# Features Implemented

## Data Collection

* Scraped live crypto currency data from multiple pages
* Extracted:

  * Coin Name
  * Symbol
  * Price
  * Market Capital
  * Volume (24h)
  * Circulating Supply

## Data Cleaning

Removed non-crypto related entries such as:

* stock
* tokenized
* ETF
* Index
* Portfolio
* CoinMarketCap
* CMC

Handled:

* Missing values
* Duplicate records
* Currency formatting
* Large numeric conversions

# Project Tasks

# Project 1 — Crypto Price Comparison Dashboard

## Objective

Compare two crypto coins dynamically using dropdown selection.

## Features

* Dynamic coin comparison
* Data Validation
* XLOOKUP formulas
* KPI Cards
* Price comparison
* Volume comparison
* Market Capital comparison
* Circulating Supply comparison

## KPI Metrics

* Volume Difference
* Market Capital Difference
* Circulating Supply Difference

# Project 2 — Crypto Liquidity Dashboard

## Objective

Analyze liquidity distribution of crypto coins using Volume (24h).

## Features

* Pivot Table
* Pie Chart
* Slicer Integration
* Dynamic filtering
* Top 5 liquidity analysis
* Others category generation

## Slicer Categories

* 0 to 50
* Greater than 50

## Visualization

* Dynamic Pie Chart
* Top 5 Coins based on Volume (24h)
* Others Category

# Project 3 — Working Hours Security Dashboard

## Objective

Display dashboard only during working hours.

## Features

* VBA Automation
* Workbook auto refresh
* Time-based chart visibility
* Security message display

## Working Hours

* 9 AM to 5 PM

## VBA Functionality

* Auto refresh workbook
* Dynamic chart visibility
* Display message outside working hours

# Data Cleaning Process

## Power Query Operations

* Removed currency symbols
* Converted columns to numeric types
* Handled Billion/Million formats
* Created Price Categories
* Created cleaned datasets

# Dashboard Features

* Interactive Dashboards
* Dynamic Charts
* KPI Cards
* Slicers
* Automated updates
* Professional formatting

# Folder Structure

```text id="’wo1r6g"
├── raw_data/
├── cleaned_data/
├── dashboards/
├── screenshots/
├── python_scripts/
├── excel_files/
└── README.md
```

# Python Libraries Used

```python id="q4rv0d"
requests
beautifulsoup4
pandas
time
openpyxl
```

# How to Run

## Install Dependencies

```bash id="wpx1c3"
pip install pandas requests beautifulsoup4 openpyxl
```

## Run Python Script

```bash id="r8j4kv"
python crypto_scraper.py
```

# Outputs Generated

* Excel datasets
* Cleaned datasets
* Pivot tables
* Dynamic dashboards
* Pie charts
* KPI dashboards

# Learning Outcomes

* Web Scraping
* Data Cleaning
* Data Transformation
* Dashboard Development
* Excel Automation
* VBA Programming
* Business Intelligence

# Author

Divyanshu Mandloi

# License

This project is developed for educational and academic purposes.
