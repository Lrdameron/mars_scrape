# 🪐 Mars Web Scraper & Climate Analyzer

A web scraping and data analysis project that extracts the latest Mars news from a web page and analyzes historical Martian weather patterns.

---

## 🚀 Overview
This project consists of two components:

- **Deliverable 1**: Scrape the Mars News website to collect article titles and preview text using Splinter and BeautifulSoup.
- **Deliverable 2**: Scrape a Mars temperature dataset and analyze Martian weather, including temperature trends and atmospheric pressure over time.

This challenge reinforces HTML parsing, browser automation, data wrangling, visualization, and exploratory data analysis in Pandas.

---

## 🌐 Source Sites
- **Mars News Site**: [Mars News (Static Version)](https://static.bc-edx.com/data/web/mars_news/index.html)
- **Weather Data Site**: [Mars Facts Table](https://static.bc-edx.com/data/web/mars_facts/temperature.html)

---

## 📊 Datasets
- **Mars News**: Scraped article `title` and `preview` text from the NASA Mars News site.
- **Mars Weather**: Historical temperature and pressure readings, scraped from a static HTML table.

Fields in the weather dataset:
- `id`: Unique ID for a transmission from the Curiosity rover  
- `terrestrial_date`: Earth date of the reading  
- `sol`: Martian day since landing  
- `ls`: Solar longitude  
- `month`: Martian month  
- `min_temp`: Minimum temperature (°C)  
- `pressure`: Atmospheric pressure (Pa)  

---

## 🧪 Approach

### 🗞️ Deliverable 1: Mars News Scraper
- Browser automation with **Splinter**
- HTML parsing with **BeautifulSoup**
- Data stored in a list of dictionaries (`[{title, preview}, ...]`)
- Optional export to JSON for external use

### 🌡️ Deliverable 2: Mars Weather Analyzer
- Scraped HTML table using **BeautifulSoup**
- Assembled into a **Pandas DataFrame**
- Cleaned and converted data types for analysis
- Generated visualizations using **Matplotlib**:
  - Avg. monthly minimum temperature
  - Avg. monthly atmospheric pressure
  - Daily minimum temperature trend to estimate Martian year length

---

## 📈 Visual Analysis & Findings

### Temperature Trends
- Coldest month: **Month 3**
- Warmest month: **Month 8–9**

### Atmospheric Pressure
- Lowest pressure: **Month 6**
- Highest pressure: **Month 9**

### Martian Year Estimate
- Approx. **650–700 Earth days**, based on temperature cycle

---

## 🛠️ Technologies Used
- Python (Pandas, BeautifulSoup, Splinter)
- Jupyter Notebook
- Matplotlib for visualizations
- JSON/CSV for data export
- ChromeDriver for browser automation

---

## 📁 Folder Structure
```bash
📦 mars_scrape
 ┣ 📜 part_1_mars_news.ipynb
 ┣ 📜 part_2_mars_weather.ipynb
 ┣ 📜 mars_news.json         # (optional)
 ┣ 📜 mars_weather.csv
 ┣ 📜 README.md

---

## 👤 Author

- **Your Name Here** – Data Scientist in Training  
  _(Replace with your actual name if submitting individually, or list teammates if this was collaborative)_

---

## 📄 License

This project was created for educational purposes as part of the edX Data Science Bootcamp.  
All data and images used are publicly available or provided for instructional use.  
No commercial use is intended.
