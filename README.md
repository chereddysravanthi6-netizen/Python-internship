# Web Scraper for News Headlines

## Objective
Build a Python program that scrapes the latest news headlines from a public news website and saves them to a text file.

## Tools Used
- Python 3
- requests
- BeautifulSoup (bs4)

## Features
- Fetches HTML content from a news website.
- Extracts news headlines using BeautifulSoup.
- Removes duplicate headlines.
- Displays headlines in the terminal.
- Saves headlines to `headlines.txt`.

## Requirements

Install the required libraries:

```bash
pip install requests beautifulsoup4
```

## How to Run

1. Save the code as `news_scraper.py`.
2. Open a terminal in the project folder.
3. Run the program:

```bash
python news_scraper.py
```

## Output

- Displays the latest news headlines in the terminal.
- Creates a file named `headlines.txt` containing all extracted headlines.

## Project Structure

```
Web-Scraper/
│── news_scraper.py
│── headlines.txt
└── README.md
```

## Concepts Used
- HTTP GET Request
- HTML Parsing
- Web Scraping
- BeautifulSoup
- File Handling
- Exception Handling

## Author
**Sravanthi Chereddy**
