# US Largest Companies Web Scraper

## Overview
This Python script scrapes data from Wikipedia's list of the largest companies in the United States by revenue. The script parses the webpage, extracts company information, and saves it into a structured CSV file. It's an excellent tool for researchers, data analysts, and anyone interested in financial and corporate data.

## Features
- Scrapes data from Wikipedia's list of the largest companies in the United States by revenue.
- Extracts key details such as company names, revenue, profit, and other relevant data.
- Outputs the data in a CSV file for easy use in data analysis projects.

## Prerequisites
Before running the script, ensure you have the following installed:
- Python 3.x
- Libraries: `requests`, `bs4` (BeautifulSoup), `pandas`

You can install these libraries using pip:
```bash
pip install requests beautifulsoup4 pandas
```

## Usage
1. **Running the Script**: Execute the script in your Python environment. The script will access the Wikipedia page, parse the HTML content, and extract the table of the largest companies.

2. **Output File**: After the script is executed, it will generate a CSV file named `companies.csv`. This file contains the structured data extracted from the Wikipedia page.

3. **Customization**: You can modify the script to target other tables or pages by changing the `url` variable and adjusting the parsing logic as needed.

## Script Details
- The script uses `requests` to send an HTTP request to Wikipedia.
- `BeautifulSoup` from `bs4` is utilized for parsing and navigating the HTML structure of the webpage.
- `pandas` is used for creating a DataFrame and exporting it to a CSV file.
- The script is focused on extracting a specific table but can be adapted for similar web scraping tasks.

## Note
- Please use this script responsibly and in accordance with Wikipedia's terms of service and data use policies.
- Ensure that any scraped data is used in compliance with relevant laws and regulations.

## Contributing
Contributions to enhance the script, add new features, or improve documentation are warmly welcomed. Feel free to fork this repository and submit pull requests.

## License
This script is released under the [MIT License](LICENSE).



