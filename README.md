# Web Scraping Companies - Largest U.S. Revenue Generating Companies (2024)

## Overview
This project demonstrates how to use Python and the BeautifulSoup library to scrape a Wikipedia page and collect data on the largest revenue-generating companies in the United States for the year 2024. The scraped data includes key information like company rank, name, industry, revenue, employee count, and headquarters location.

The final data is stored in a CSV file and can be used for various analytical purposes. The script used for scraping and data processing, as well as the resulting CSV file, are included in this repository.

## Features
- **Web Scraping**: Scrapes data from Wikipedia using BeautifulSoup.
- **Data Processing**: Parses and organizes data into a pandas DataFrame.
- **CSV Export**: Exports the final dataset to a CSV file.
- **AWS S3 Integration**: Uploads the resulting CSV file to AWS S3 storage.

## Files in the Repository
- `scraping_script.py`: The Python script responsible for web scraping and data processing.
- `largest_companies_2024.csv`: The CSV file containing the scraped data on the largest revenue-generating companies in the U.S. for 2024.

## Prerequisites
Before running the project, ensure you have the following installed:
- Python 3.x
- Pandas
- BeautifulSoup4
- Requests

You can install the necessary dependencies using the following command:

pip install pandas beautifulsoup4 requests

## How to Run the Script
Clone the repository:
- `git clone https://github.com/yourusername/Web-Scraping-companies.git
cd Web-Scraping-companies`
Run the script to scrape the data:
-`python scraping_script.py`

## AWS S3 Integration
The script is designed to upload the CSV file to an AWS S3 bucket. You can modify the script to specify your S3 bucket path and ensure that you have the correct permissions and AWS credentials configured.

