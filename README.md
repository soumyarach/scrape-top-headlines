# scrape-top-headlines
# What It Does? (in a few words)
The code is a Python web scraper that:

->Goes to the BBC News website.

->Extracts the top 5 latest headlines using HTML parsing.

->Prints them to the screen.

->Saves them to a .txt file on the computer.

# How It Works? (step by step)
requests.get()

Download the webpage content from BBC.

BeautifulSoup()

Parses the raw HTML so we can extract specific elements (like headlines).

Find tags

Looks for headlines inside tags with class 'gs-c-promo-heading__title'.

Store Top 5 Headlines

Extracts the text of the first 5 headlines using a list.

Print Static + Live Headlines

The printed 5 hardcoded headlines and then printed 5 actual headlines from the page.

Save to .txt File

Opens a file and writes both the static headlines and scraped ones to it.

# Why It Is Built?
To automate news collection from BBC.

Helps users quickly see top news without opening a browser.

Useful for learning Python, web scraping, and data automation.
