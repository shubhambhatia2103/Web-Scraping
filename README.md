# Web Scraping in Python

## Overview

This project demonstrates how to scrape data from a real website using Python. Specifically, it focuses on extracting data from the Wikipedia page listing the largest companies in India. The scraped data is then stored in a CSV file.

## Contents

- `scraping_script.py`: The main Python script that performs the web scraping.
- `companies.csv`: The CSV file containing the scraped data.
- `README.md`: This file, providing an overview and instructions.

## Requirements

- Python 3.x
- BeautifulSoup4
- Requests
- pandas

## Setup

1. Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/web-scraping-python.git
cd web-scraping-python
```
2. Install the required Python packages:

```bash
pip install beautifulsoup4 requests pandas
```

## Usage

1. Run the Python script to scrape the data and save it to a CSV file:

```bash
python scraping_script.py
```

2. The script will fetch the list of the largest companies in India from the specified Wikipedia page and store the data in 'companies.csv'.

## Script Explanation
The 'scraping_script.py' script performs the following steps:

1. Fetch the Webpage Content: Uses the 'requests' library to fetch the content of the Wikipedia page.
2. Parse the HTML: Uses BeautifulSoup to parse the HTML content of the page.
3. Extract Table Data: Finds the specific table containing the list of companies and extracts the data.
4. Store Data in CSV: Uses 'pandas' to store the extracted data in a CSV file.


## Learning Outcome
This project is an exercise in web scraping, demonstrating how to:

1. Fetch webpage content using 'requests'.
2. Parse HTML content using BeautifulSoup.
3. Extract specific data from an HTML table.
4. Store extracted data in a structured format using 'pandas'.


## Authors

- [@shubhambhatia2103](https://www.linkedin.com/in/shubhambhatia2103/)


## Feedback

If you have any feedback, please reach out to me at Shubhambhatia2103@gmail.com

## Contact

[<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/linkedin.png" title="LinkedIn">](https://www.linkedin.com/in/shubhambhatia2103/) [<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/github.png" title="Github">](https://github.com/shubhambhatia2103) [<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/instagram-new.png" title="Instagram">](https://instagram.com/6eingshubham) [<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/twitter-squared.png" title="Twitter">](https://twitter.com/whoodattboyy)
