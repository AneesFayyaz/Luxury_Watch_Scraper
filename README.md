# WatchScraper

WatchScraper is a web scraping project that extracts detailed information about watch products from the "Le Guide des Montres" website and saves the data into an Excel file. This project uses BeautifulSoup and requests to scrape data and pandas to handle data storage.

## Features

- Scrapes watch product details such as images, SKU, brand name, product name, movement, functions, box, bracelet, remarks, and price.
- Stores the extracted data in an Excel file for easy access and analysis.

## Requirements

- Python 3.x
- BeautifulSoup4
- requests
- pandas
- openpyxl

## Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/yourusername/WatchScraper.git
    ```

2. Navigate to the project directory:

    ```bash
    cd WatchScraper
    ```

3. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the main script to start the scraping process:

    ```bash
    python main.py
    ```

2. The script will scrape the data and save it to an Excel file named `output1.xlsx` in the project directory.

## Code Overview

### main.py

This script contains three main functions:

1. `brands_links()`: Scrapes the brand links from the main product page.
2. `products_links(brandsLink)`: Scrapes the product links from each brand page.
3. `Product_details(links)`: Scrapes the detailed product information from each product page and saves it to an Excel file.

## Acknowledgements
- The BeautifulSoup library for parsing HTML and XML documents.
- The requests library for making HTTP requests.
- The pandas library for data manipulation and analysis.
- The openpyxl library for working with Excel files in Python.
