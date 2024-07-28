**Luxury Watch Scraper**
This repository contains a Python script for scraping detailed information about luxury watches from a specific website. The script uses BeautifulSoup for HTML parsing and requests for handling HTTP requests. It extracts various details such as images, product names, brand names, SKU, movement, functions, box, bracelet, remarks, price, and product URLs. The collected data is then saved into an Excel file.

**Prerequisites**
Before running the script, ensure you have the following installed:

    Python 3.x
    BeautifulSoup
    requests
    pandas

**Script**

This script scrapes detailed information about luxury watches from the specified website.

Functionality:

    Scrapes the links to all available brands.
    Scrapes the links to all products from each brand.
    Extracts detailed information about each product.
    Saves the extracted data into an Excel file.

**Output**

The script outputs an Excel file named output1.xlsx with the following columns:

    Image Urls: URLs of product images.
    SKU: SKU number of the product.
    Brand Name: Name of the brand.
    Product Name: Name of the product.
    Mouvement: Movement type of the watch.
    Functions: Functions of the watch.
    Box: Box details.
    Bracelet: Bracelet details.
    Remarks: Additional remarks.
    Price: Price of the product.
    Product Url: URL of the product page.
