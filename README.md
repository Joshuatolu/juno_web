# Juno Web - Jumia Camera Data Scraping and Snowflake Integration
This repository contains a Python script for scraping camera product data from Jumia Nigeria and loading it into a Snowflake database. The script extracts product details such as names, prices, discounts, old prices, and ratings, processes the data, and stores it in a structured database table.

## Overview
The script performs the following tasks:

1. Web Scraping:

    - Scrapes camera product data from Jumia's catalog pages.
    - Extracts product names, prices, discounts, old prices, and ratings.
    - Handles pagination to scrape multiple pages.

2. Data Processing:

    - Cleans and transforms the scraped data (e.g., removing currency symbols, splitting ratings).
    - Converts data types for numerical fields.

3. Snowflake Integration:

    - Connects to a Snowflake database using credentials from an environment file.
    - Loads the processed data into a Snowflake table (src_Camera).

## Key Features

1. Web Scraping: Extracts product data from Jumia using BeautifulSoup.
2. Data Cleaning: Processes and transforms raw scraped data into a clean format.
3. Snowflake Integration: Automates data loading into a Snowflake database.

Repository Contents
Script: The main Python script for scraping and database integration.

### Prerequisites
1. Python 3.x
2. Libraries: beautifulsoup4, requests, pandas, snowflake-sqlalchemy, snowflake-connector-python, python-dotenv
3. Snowflake account and database.

**For any questions or issues, please open an issue in the repository. Contributions are welcome! Thank You!**
