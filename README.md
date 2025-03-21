# 🪐 Mars Web Scraper & Climate Analyzer

A web scraping and data analysis project that extracts the latest Mars news from a web page and analyzes historical Martian weather patterns. 

**For educational uses only.**

---

## 👤 Author
**Logan Dameron**

---

## 🚀 Overview
This project consists of two parts:

- **Deliverable 1**: Scrape the Mars News site to collect article titles and preview text using Splinter and BeautifulSoup.
- **Deliverable 2**: Scrape Mars temperature data from a static HTML table and analyze climate patterns, including temperature trends and atmospheric pressure.

---

## 🌐 Source Sites
- [Mars News Site](https://static.bc-edx.com/data/web/mars_news/index.html)  
- [Mars Temperature Data](https://static.bc-edx.com/data/web/mars_facts/temperature.html)

---

## 🧪 Approach

### 🗞️ Mars News Scraper
- Used **Splinter** for browser automation
- Parsed article content with **BeautifulSoup**
- Stored data as list of dictionaries
- (Optional) Exported to `mars_news.json`

### 🌡️ Mars Weather Analyzer
- Parsed HTML table with BeautifulSoup
- Loaded into a **Pandas DataFrame**
- Cleaned and converted data types
- Created visualizations using **Matplotlib**

---

## 🛠️ Tools Used
- Python (Pandas, Splinter, BeautifulSoup)
- Jupyter Notebook
- Matplotlib
- ChromeDriver

---

## 📁 Folder Structure
```bash
📦 mars_scrape
 ┣ 📜 part_1_mars_news.ipynb
 ┣ 📜 part_2_mars_weather.ipynb
 ┣ 📜 mars_news.json         # (optional)
 ┣ 📜 mars_weather.csv
 ┣ 📜 README.md

