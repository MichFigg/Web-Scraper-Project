#  Web Scraper Project

A simple Python script that scrapes book title and price from an online bookstore and saves the data to a CSV file daily.

##  Features
- Scrapes book title and current price from [taniaksiazka.pl](https://www.taniaksiazka.pl)
- Saves data to `BookStoreScraperDataSet.csv` with date stamps
- Automatically creates the CSV file if it doesn’t exist
- Appends new data each day
- Jupyter Notebook format

##  Technologies Used
- Python
- Jupyter Notebook
- BeautifulSoup
- Requests
- Pandas
- CSV

##  File Overview
| File                          | Description                              |
|-------------------------------|------------------------------------------|
| `web_scraper_project.ipynb`   | Main notebook with scraping logic        |
| `BookStoreScraperDataSet.csv` | Output file with scraped data            |

##  Sample Output
| Title                         | Price | Date       |
|------------------------------|-------|------------|
| Python. Instrukcje dla prog. | 82,90 | 2025-05-26 |

---

###  Author
Michał Figwer
