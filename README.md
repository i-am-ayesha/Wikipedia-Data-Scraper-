# 🌐 Web Scraping Wikipedia with BeautifulSoup & Pandas
This project demonstrates how to scrape data from a real website (Wikipedia) using Python's BeautifulSoup library and then organize it into a structured format using Pandas. The scraped data is saved in a CSV file for further analysis.

## 🛠️ Tech Stack
* **Python:** Core language for web scraping and data processing.
* **BeautifulSoup:** Extracts data from HTML pages.
* **Requests:** Fetches the web page content.
* **Pandas:** Organizes and manipulates data into a DataFrame.
## 🚀 Features
1. Scrapes company data (Rank, Name, Industry, Revenue, Growth, Employees, Headquarters) from Wikipedia.
2. Creates a structured table using Pandas.
3. Exports the data to a CSV file.
## 📚 How It Works
* **Fetch the Web Page:** Use the requests library to retrieve the HTML content of the target Wikipedia page.
* **Parse the HTML:** BeautifulSoup is used to parse the HTML and extract the desired data (table rows and columns).
* **Store Data:** Extracted data is stored in a Pandas DataFrame.
* **Export to CSV:** The data is exported to a CSV file for further use.
