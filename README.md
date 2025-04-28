## Dealership Inventory Scraper & Cleaner
This project scrapes inventory data from a collection of dealership websites, cleans the scraped data, and prepares it for use in a dashboard or other data analytics workflows.

# Features
Scrapes multiple dealership websites and collects inventory details depending on what the dealer posts on their website such as:
 - Vehicle make/model
 - Year
 - Price
 - Mileage
 - VIN
 - Location

Cleans and standardizes raw data:
 - Fixes formatting issues
 - Normalizes field names
 - Handles missing or duplicate entries

Output is dashboard-ready for visualizations or reporting.

# Usage
- Building an inventory dashboard in PowerBI, Tableau, or a custom web app.
- Monitoring pricing trends across multiple dealerships.
- Analyzing vehicle turnover rates, regional price differences, etc


# Prerequisites
For Scraper
```
pip install selenium
pip install webdriver-manager
pip install undetected-chromedriver
```

# Getting Started
Clone the repo
```
git clone https://github.com/Sodiumexcevator/charlotte-dealer-dashboard.git
cd charlotte-dealer-dashboard
```

# Run the Notebooks
 - DealerInventoryCompScraper.ipynb first to pull fresh data from the sites
 - dealerInventoryComparison.ipynb next to clean the new data
 
# Notes
- The CSV files in /data/ are examples from previous scrapes — you can overwrite or replace them.
- The scraper assumes a relatively consistent site structure; if dealership websites change, small code tweaks might be needed.