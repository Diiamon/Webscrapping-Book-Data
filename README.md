# Web Scraping Project

## Overview

This project is focused on web scraping, a technique used to extract data from websites. The code provided in this repository is designed to scrape book information from a sample online bookstore.

### Features

- **Data Extraction**: Utilizes BeautifulSoup and requests libraries to parse HTML and extract data.
- **Pagination Handling**: Includes functions to navigate through paginated sections of the bookstore.
- **Data Cleaning**: Implements RegEx and pandas operations to clean and structure the scraped data.
- **Data Storage**: Saves the scraped data into a pandas DataFrame for easy manipulation and analysis.
  
### How It Works

- **Import Libraries**: The necessary libraries for web scraping and data manipulation are imported.
- **Establish Connection**: The requests library is used to establish a connection with the website.
- **Parse HTML**: BeautifulSoup is employed to parse the HTML content and extract relevant data.
- **Handle Sections and Pagination**: Custom functions are created to handle different sections of the bookstore and manage pagination.
- **Extract Book Links**: Functions are designed to extract individual book links from the pages.
- **Scrape Book Information**: Each book’s details are scraped, including UPC, name, category, price, and availability.
- **Clean Data**: The extracted data is cleaned and structured using pandas and RegEx.
- **Store Data**: The final cleaned data is stored in a pandas DataFrame.
  
### Usage
To use this code, simply run the Jupyter Notebook files provided. Ensure that you have the required libraries installed in your Python environment.

### Dependencies

Python 3
BeautifulSoup
requests
pandas
numpy
re (RegEx)

**Feel free to clone this repository and use the code as a starting point for your own web scraping projects! Remember to respect the terms of service and robots.txt of any website you scrape. Happy data hunting!** 📊🔍
