# Wikipedia Companies Web Scraper 🕸️

## Overview
This project demonstrates a simple and effective web scraping workflow where company data is extracted from Wikipedia, processed, and saved into a structured CSV file.  

The focus is on practicing data retrieval, parsing HTML tables, and basic data cleaning — all important skills for data analysis and automation tasks.

## Project Workflow
- Accessed Wikipedia using the `requests` library.
- Parsed HTML content with `BeautifulSoup`.
- Located and extracted relevant table data.
- Transformed the data into a pandas DataFrame.
- Saved the final cleaned dataset into a `companies.csv` file.

## Tools & Technologies
- **Python**  
- **Libraries**:
  - `requests`
  - `BeautifulSoup4`
  - `pandas`

## How to Run
1. Clone this repository.
2. Install the required libraries:
    ```bash
    pip install requests beautifulsoup4 pandas
    ```
3. Run the Jupyter notebook: `Scrapping data from Wikipedia.ipynb`

4. The output CSV (`companies.csv`) will be generated automatically.

