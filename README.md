# Amazon Product Web Scraper with Automated Rating Monitoring

This project demonstrates a web scraping script that extracts product details from an Amazon listing, including the product title and rating, and logs them into a CSV file. It also includes an automated process to periodically check for updates to the product rating and append the results to the CSV file daily.

**Key Features:**

Web Scraping: Uses BeautifulSoup and requests to scrape the product title and rating from an Amazon product page.

CSV Logging: Extracted data (title, rating, date) is saved into a CSV file for tracking changes over time.

Automated Monitoring: The script runs every 24 hours (86400 seconds) to check for updates in the product rating and logs new data to the CSV.

Pandas Integration: Data from the CSV can be easily read into a pandas DataFrame for further analysis and visualization.

**Tools & Libraries:**

Web Scraping: BeautifulSoup, Requests

Data Handling: Pandas, CSV

Automation: Time module for periodic execution

**How It Works:**

1. The script scrapes the product title and rating from the given Amazon URL.

2. The data is cleaned and stored in a CSV file.

3. The automated function re-scrapes the data every day, appending any changes to the CSV file for tracking purposes.

You can explore the project to see how web scraping and automation are implemented and use it as a template for your own projects
