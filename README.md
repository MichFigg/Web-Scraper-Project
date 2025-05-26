# 📘 Web Scraper Project

A simple Python script that scrapes book title and price from an online bookstore and saves the data to a CSV file daily.

## 🚀 Features
- Scrapes book title and current price from [taniaksiazka.pl](https://www.taniaksiazka.pl)
- Saves data to `BookStoreScraperDataSet.csv` with date stamps
- Automatically creates the CSV file if it doesn’t exist
- Appends new data each day
- Jupyter Notebook format

## 🧰 Technologies Used
- Python
- Jupyter Notebook
- BeautifulSoup
- Requests
- Pandas
- CSV

## 🗂 File Overview
| File                          | Description                              |
|-------------------------------|------------------------------------------|
| `web_scraper_project.ipynb`   | Main notebook with scraping logic        |
| `BookStoreScraperDataSet.csv` | Output file with scraped data            |

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/MichFigg/Web-Scraper-Project.git
   ```
2. Navigate to the project folder and run Jupyter Notebook:
   ```bash
   cd Web-Scraper-Project
   jupyter notebook
   ```
3. Open `web_scraper_project.ipynb` and run the cells.

## 📦 Sample Output

| Title                         | Price | Date       |
|------------------------------|-------|------------|
| Python. Instrukcje dla prog. | 82,90 | 2025-05-26 |

## 📌 Notes
- Make sure you have all required libraries installed:
  ```bash
  pip install requests beautifulsoup4 pandas
  ```
- Script uses a custom User-Agent header to avoid blocking.
- Can be extended to scrape more books or run as a scheduled task.

---

### 🧠 Author
Michał Figwer
