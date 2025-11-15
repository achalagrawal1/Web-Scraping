Project Title

Web Scraping Largest Companies by Revenue

Description

This project uses Python and BeautifulSoup to scrape the Wikipedia page of the largest companies by revenue. It collects data such as Rank, Name, Industry, Revenue, Profit, Employees, Headquarters, and State-owned status. The scraped data is then saved into a CSV file for easy use in Excel, Google Sheets, or data analysis tools.

Technologies Used

Python 3

BeautifulSoup (bs4)

Pandas

Requests

How It Works

The script sends a request to the Wikipedia page.

BeautifulSoup parses the HTML to find the table with company data.

Each row is read, cleaned, and saved into a Pandas DataFrame.

The DataFrame is exported to CSV.

