# 📈 Analyzing Historical Stock Revenue Data and Building a Dashboard

An end-to-end Python data science project focused on extracting historical stock market data and quarterly revenues for major companies (**Tesla** and **GameStop**), cleaning the financial datasets, and building interactive multi-panel visualizations.

---

## 📌 About the Project
Extracting essential data from financial datasets and displaying it correctly is a crucial part of data science, enabling stakeholders and individuals to make informed, data-driven decisions. This project demonstrates web scraping, API data extraction, data manipulation, and financial visualization techniques using Python.

---

## 🌐 Data Sources & Web Scraping Links
The quarterly revenue data for this project is extracted via web scraping from the following Macrotrends pages:
* **Tesla Revenue Data:** [https://www.macrotrends.net/stocks/charts/TSLA/tesla/revenue](https://www.macrotrends.net/stocks/charts/TSLA/tesla/revenue)
* **GameStop Revenue Data:** [https://www.macrotrends.net/stocks/charts/GME/gamestop/revenue](https://www.macrotrends.net/stocks/charts/GME/gamestop/revenue)

---

## 🛠️ Technologies & Libraries Used
* **Python**
* **yfinance** (for extracting historical stock price data)
* **BeautifulSoup & Requests** (for web scraping quarterly revenue data from Macrotrends)
* **Pandas & NumPy** (for data cleaning and dataframe manipulation)
* **Plotly** (for creating interactive financial graphs and subplots)
* **Jupyter Notebook** (as the development environment)

---

## 🔍 Key Tasks & Workflow

1. **Graphing Function Definition:** Created a reusable function using Plotly (`make_graph`) to generate multi-row subplots displaying share prices and quarterly revenue trends side-by-side.
2. **Tesla Data Extraction (`TSLA`):**
   * Extracted max-period historical stock market data using `yfinance`.
   * Scraped quarterly revenue data using `requests` and `BeautifulSoup` from the [Tesla Revenue Page](https://www.macrotrends.net/stocks/charts/TSLA/tesla/revenue).
   * Cleaned strings by removing currency symbols (`$`) and commas (`,`), and handled missing values (`NaN`).
3. **GameStop Data Extraction (`GME`):**
   * Extracted historical stock data using `yfinance`.
   * Scraped quarterly revenue data from the [GameStop Revenue Page](https://www.macrotrends.net/stocks/charts/GME/gamestop/revenue).
   * Cleaned and preprocessed the revenue dataframe.
4. **Interactive Dashboards & Plotting:** Generated interactive financial graphs visualizing stock price evolution alongside quarterly revenue history for both companies.

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone [https://github.com/OsamaYassin/Peer-graded-Assignment-Analyzing-Historical-Stock-Revenue-Data-and-Building-a-Dashboard.git](https://github.com/OsamaYassin/Peer-graded-Assignment-Analyzing-Historical-Stock-Revenue-Data-and-Building-a-Dashboard.git)
