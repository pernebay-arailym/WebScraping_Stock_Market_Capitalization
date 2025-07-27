# 📊 Stock Market Capitalization by Country – Web Scraping Project

## 🛠 Project Overview
This project demonstrates a real-world data extraction pipeline using Python and BeautifulSoup. We scrape and process global stock market capitalization data from Wikipedia, structure it into a clean tabular format, and export it to a CSV file for downstream use.

As a data engineer, this workflow illustrates how to:
- Handle HTML tables with multi-row and multi-column headers
- Clean and normalize data scraped from semi-structured web sources
- Transform web data into a usable CSV dataset


## 🔗 Data Source
- [Wikipedia: List of countries by stock market capitalization](https://en.wikipedia.org/wiki/List_of_countries_by_stock_market_capitalization)


## 🧰 Tech Stack
- Python 3
- Jupyter Notebook (VS Code)
- BeautifulSoup for web scraping
- Pandas for data manipulation
- CSV for data export


## 📁 Output
The final dataset is exported as `stock_market_data.csv` and includes the following columns:
- `Country / Territory`
- `Total market cap (in millions of US$)`
- `Total market cap (as a % of GDP)`
- `Number of domestic companies listed`
- `Year`


## ✅ Use Cases
This kind of scraping and transformation pipeline is useful in:
- Building market intelligence datasets
- Automating periodic financial data collection
- Feeding real-time dashboards or ETL pipelines


## 📌 Notes
- Handles complex table structures with `colspan` and `rowspan`
- UTF-8 encoding ensures compatibility with international characters
- Easily extendable for similar structured datasets


## 📄 License
MIT License
