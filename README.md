# 📚 Ecommerce-Book-Price-Tracker

This project is a web scraping exercise using Python and BeautifulSoup to extract book data (title, price, availability, rating, and more) from the [Books to Scrape](http://books.toscrape.com/) website. The scraped data is used for further analysed using PowerBI dashboard.

---

## 🧾 Features

* 🔍 Scrapes book titles, prices, ratings, availability, and product page links
* 🔄 Navigates through multiple pages of the website automatically
* 🧼 Cleans and structures the scraped data into a DataFrame
* 💾 Saves the dataset to a CSV file for further use
* 📊 Suitable for use in data visualization and dashboarding

---

## 🛠️ Technologies Used

* Python 3.x
* `requests` – to send HTTP requests
* `BeautifulSoup (bs4)` – for parsing HTML
* `pandas` – for storing and manipulating data

---

## 📁 Project Structure

```
books_scraping_beautifulsoup.ipynb   # Jupyter Notebook with all code and outputs
README.md                            # Documentation
scrapped_book_prices.csv             # Scrapped data in excel
Ecommerce.pbix                       #PowerBI dashboard to analyze, visualize scrapped prices.


---

## 🚀 How to Run

1. Clone this repository:

```bash
git clone https://github.com/anushka-0907/books-scraping-project.git
cd books-scraping-project
```

2. Install the required packages:

```bash
pip install requests beautifulsoup4 pandas
```

3. Open the notebook:

```bash
jupyter notebook books_scraping_beautifulsoup.ipynb
```

4. Run all cells to:

   * Fetch data from the website
   * Extract relevant fields from HTML
   * Store results into a structured DataFrame
   * Export to `books_data.csv`

---

## 📊 Data Columns Extracted

* `Title`
* `Price`
* `Availability`
* `Rating`
* `Product URL`

---

## 🧠 Use Cases

* Practice web scraping techniques
* Build an e-commerce book analyzer
* Create data visualizations of:

  * Price distribution
  * Availability per category
  * Average rating per category
  * Top-rated or most expensive books

---
