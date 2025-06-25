# 📘 Web Scraping 50 Book Pages using BeautifulSoup

This project demonstrates how to scrape data from **50 static HTML pages** representing an online bookstore using Python and **BeautifulSoup**.


## 🧪 Technologies Used

- Python 3.12
- BeautifulSoup4
- pandas
- Jupyter Notebook

## 📋 Data Scraped

From each book listed on every page, the following information is extracted:

- ✅ Title
- ✅ Price
- ✅ Availability (In stock or not)
- ✅ Rating (e.g., One, Two, Three Stars)

## 📌 How It Works

The notebook:

1. Iterates through 50 local HTML files using a loop.
2. Parses each file using `BeautifulSoup`.
3. Extracts structured data from the book cards.
4. Cleans the data (e.g., removes extra spaces).
5. Stores all the records in a `pandas.DataFrame`.

## 🚀 How to Run

1. Clone this repository.
2. Place the `html/` folder (with 50 HTML pages) in the root directory.
3. Open `websc_beautiful_soup.ipynb` in Jupyter Notebook.
4. Run all cells to scrape and display the full dataset.

```bash
pip install beautifulsoup4 pandas
