# World-Population-Data-Pipeline---Python-SQL-Power-BI

🌍 World Population Data Pipeline - Python, SQL & Power BI
This project automates the extraction, storage, and visualization of country-wise population data using Python and Power BI.

🔹 Project Overview
Data Source: Scrapes live population data from Worldometers.
Data Extraction: Python script (requests, BeautifulSoup) fetches population details.
Data Storage: Extracted data is stored in SQL Server via pyodbc.
Power BI Integration:
Directly connects to the Python script in Power BI.
Data transformation and visualization are performed using Power Query and DAX.
📊 Dashboard Insights
✅ Country-wise population with growth trends.
✅ Yearly changes, density, and migration trends.
✅ Urban population distribution & global share analysis.

📂 Project Structure
bash
Copy
Edit
📂 World-Population-Data-Pipeline
│-- 📜 population_scraper.py    # Python script to scrape and store data.
│-- 📜 WorldPopulation.pbix     # Power BI report with visualizations.
│-- 📜 README.md                # Documentation for setup and usage.
🚀 How to Use
1️⃣ Run population_scraper.py

Copy the code and paste it into Power BI Python Scripts or run it separately to update data in SQL.
2️⃣ Refresh Power BI

Connect Power BI to the SQL database or load the updated data from Python.
3️⃣ Explore Insights

Analyze population trends using interactive Power BI visualizations.
This project showcases how Python & Power BI can be combined to automate data pipelines, making real-time analytics seamless! 🚀
