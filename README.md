# Project Name: Daraz Web Scraper using Selenium

## 1. Project Overview

* **Target Website:** https://www.daraz.pk
* **Data Fields Extracted:** Product Title, Price, Discount, Reviews, Sold Count, Product URL, Image URL
* **Tools Used:** Python, Selenium, BeautifulSoup, webdriver-manager, CSV, Regular Expressions

This project is a web scraping tool designed to extract product information from Daraz search result pages. It uses Selenium to automate browser interaction and load dynamic content, while BeautifulSoup is used to parse HTML and extract structured product data.

The extracted data is stored in a CSV file for further analysis.

---

## 2. Features

- Automated browsing using Selenium  
- Handles dynamically loaded content (lazy loading + scrolling)  
- Extracts multiple product attributes  
- Robust parsing with fallback selectors  
- Saves structured data into CSV format  

---

## 3. Setup Instructions

1. Clone this repository:
   git clone https://github.com/AreeshaFaisal04/daraz-web-scraper.git
   
3. Install dependencies:
   pip install -r requirements.txt

4. Run the scraper:
   python scraping.ipynb

---

## 4. Output

After running the script, a CSV file is generated:

daraz_final_data.csv

It contains:
- Product Title
- Price
- Discount
- Reviews
- Sold Count
- Product URL
- Image URL

---

## 5. Challenges & Solutions

One major challenge was handling the dynamic structure of Daraz product pages, where HTML classes frequently change. This was solved by using multiple CSS selector fallbacks.

Another challenge was ensuring all products load properly, which was resolved by implementing page scrolling using Selenium before parsing HTML.

---

## 6. Ethical Considerations

- Used time delays (sleep) to avoid overwhelming the server  
- Limited page requests to avoid excessive scraping  
- Followed respectful scraping practices  

