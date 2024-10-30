# Amazon_Price_Tracker(Web Scrape)
This project is a simple Amazon price tracker that uses Python, BeautifulSoup, and smtplib to notify users when the price of a specified product falls below a set threshold. The script scrapes product information from Amazon using BeautifulSoup, checks the current price, and sends an email alert if the price meets your desired threshold.

## Features
- Scrapes Amazon product information using BeautifulSoup.
- Extracts the current product price and compares it to a target threshold.
- Sends an email alert to the user when the price is below the specified threshold.

  ## Steps
  - Importing libraries
  - Connect to website and pull data using user-agent header to prevent being spotted and blocked.
  - Clean data little bit.
  - Create a Timestamp for your output to track when data was collected
  - Create CSV and write headers and data into the file
  - Appending Data to csv
  - Combining the code
  - Final step is to put down the email notification to recieve when the price falls below.
 
#### Disclaimer
Web scraping Amazon may violate their terms of service. This project is intended for educational purposes only, so we are using it responsibly. Frequent requests to amaon's site may result in getting blocked.
