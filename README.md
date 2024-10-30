# Books to Scrape - Web Scraper

## Description

This Python script is designed to scrape book information from the [Books to Scrape](https://books.toscrape.com) website. It extracts details such as title, link, price, and stock availability for all books across multiple pages. The collected data is then saved to both Excel (.xlsx) and CSV files.

## Features

- Scrapes multiple pages until no more books are found
- Extracts book title, link, price, and stock information
- Saves data to Excel and CSV formats
- Handles pagination automatically
- Option to use proxies for web scraping (currently commented out)

## Requirements

- Python 3.x
- Required libraries:
  - requests
  - BeautifulSoup4
  - pandas
  - openpyxl

## Installation

1. Clone this repository or download the script.
2. Install the required libraries:

