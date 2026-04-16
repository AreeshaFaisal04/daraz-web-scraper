# Project Name: Daraz Web Scraper

### 1. Project Overview

* **Target Website:** https://www.daraz.pk
* **Data Fields Extracted:** Title, Price, Original Price, Discount, Rating, Reviews, Sold Count, URL, Image URL
* **Tools Used:** Python, Requests, BeautifulSoup, Selenium, WebDriver Manager

This project demonstrates web scraping of Daraz search results using both static and dynamic techniques.

---

### 2. Setup Instructions

1. Clone this repo:

   ```
   git clone https://github.com/YOUR_USERNAME/daraz-scraper.git
   ```
2. Install dependencies:

   ```
   pip install -r requirements.txt
   ```
3. Run script:

   ```
   python scraper.py
   ```

---

### 3. Challenges & Solutions

* **Challenge:** Daraz content is dynamically loaded using JavaScript.

* **Solution:** Used Selenium to render full page and combined it with BeautifulSoup for parsing.

* **Challenge:** Lazy-loaded images were not appearing.

* **Solution:** Implemented scrolling logic to trigger loading.

---

