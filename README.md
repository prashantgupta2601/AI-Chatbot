Price Comparison Bot -:
This is a Python project that helps you compare the prices of a product across Amazon, eBay, and Walmart using web scraping. It shows the prices in a table and highlights the options that are within your budget.

Features :
Search for any product by name

Fetch prices from Amazon, eBay, and Walmart

Show results in a neat table using the rich library

Filter out products that are over your budget

Requirements:To run this project, you need:Python 3

Internet connection

A free account and API key from ScraperAPI

Install Python libraries:
bash
Copy
Edit
pip install requests beautifulsoup4 rich
How to Use
Clone or download the project to your computer.

Open the file and replace this line:
python
Copy
Edit
SCRAPER_API_KEY = "eefa842c395497bc9a8dc046151d9d3b"
with your own ScraperAPI key (you can get one for free).

Run the program using:

bash
Copy
Edit
python price_comparator.py
Enter the product name and your budget when asked.

You’ll see a table of prices found on different websites.

Example
bash
Copy
Edit
💸 Welcome to the API-Powered Price Comparison Bot!

🛍️ Enter product name: headphones
💰 Enter your max budget ($): 100

🔎 Fetching prices... Please wait.

┏━━━━━━━━━━━┳━━━━━━━━━━━━━━━┓
┃ Platform  ┃ Price (USD)   ┃
┡━━━━━━━━━━━╇━━━━━━━━━━━━━━━┩
│ eBay      │ $59.99        │
│ Walmart   │ $62.49        │
└───────────┴───────────────┘
Notes:
This bot uses web scraping, which may stop working if the website structure changes.

Use it for personal or educational purposes.

Respect the websites' terms of service.

License :
This project is open-source and free to use under the MIT License.

# AI-Chatbot
