Project 2: Amazon Product Web Scraper

Understanding the Task:
A Python script to scrape product details (e.g., title and price) from an Amazon product page.

Steps Performed:

1.Importing Libraries:
Used BeautifulSoup for HTML parsing and requests to fetch webpage content.

2.Fetching the Webpage:
Specified the target product URL and sent a GET request with appropriate headers (e.g., User-Agent) to mimic a real browser and avoid blocking.

3.HTML Parsing:
Parsed the page content using BeautifulSoup and prettified the HTML for better readability.

4.Extracting Product Details:
Identified and extracted the product title using its HTML id (productTitle).
Extracted the price using its HTML id (priceblock_ourprice).

5.Output:
Printed the extracted details (title and price) to the console for verification.

6.Next Steps (Optional):
Set up email notifications or save the data to a file for tracking price changes.

7.Outcome:
A lightweight script to fetch and display real-time product information from Amazon.
