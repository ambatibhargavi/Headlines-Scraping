# News Scraper Application

This is a simple Flask-based web application that scrapes and displays headlines from any given news website or URL. The application leverages `BeautifulSoup` for web scraping and is designed to extract text from common headline tags like `<h1>`, `<h2>`, `<h3>`, etc.

## Features

- Input a URL to scrape for headlines.
- Extracts text from common HTML heading tags (`h1`, `h2`, `h3`, `h4`, `h5`, `h6`).
- Displays the scraped headlines in a clean and readable format.
- Handles errors gracefully by displaying an appropriate error message if scraping fails.

## Prerequisites

Before running the application, ensure you have the following installed:

- Python 3.x
- Flask
- Requests
- BeautifulSoup

How It Works
The application sends a GET request to the provided URL and retrieves the HTML content of the page.
It then parses the HTML using BeautifulSoup to find and extract text from heading tags (h1 to h6).
The extracted headlines are displayed on the web page.
Example Usage
To scrape headlines from a news website:

Run the application and enter a news website URL (e.g., https://www.bbc.com/).
Click the "Scrape" button.
The page will display the scraped headlines in a list format.
Error Handling
If an invalid URL is provided or if there are issues with accessing the website, the application will display an error message like "Error: [error description]".


Acknowledgements
Flask - A lightweight WSGI web application framework in Python.
BeautifulSoup - A Python library for pulling data out of HTML and XML files.
Requests - A simple, yet elegant HTTP library for Python.
Contact
For any inquiries or issues, please feel free to reach out.

