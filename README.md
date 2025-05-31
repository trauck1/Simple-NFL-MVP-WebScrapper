# Simple-NFL-MVP-WebScrapper

**NFL AP MVP Winner Scraper**
A simple Python web scraper that retrieves NFL Associated Press Most Valuable Player (AP MVP) winners by year from Pro Football Reference.

**Description**
This script allows you to look up NFL AP MVP winners from 1961 to 2024 by scraping data from pro-football-reference.com. Simply enter a year and the script will fetch and display the MVP winner for that season.

**Install the required dependencies:**

pip install requests
pip install beautifulsoup4

**Usage**
Run the script:
python mvp_scraper.py
Follow the prompts:

Enter a year between 1961-2024
The script will validate your input
If valid, it will scrape the data and display the MVP winner

**Example Output**
NFL AP MVP winner by year!
What year would you like(1961-2024): 2007
Scraping 2007 NFL AP MVP...
The 2007 AP MVP was Tom Brady

**Details**

Data Source: pro-football-reference.com awards pages
Parsing Method: BeautifulSoup HTML parser
Target Element: Table with ID voting_apmvp, first row contains the winner
Data Attribute: Uses data-stat="player" to locate player name cell


**Limitations**

Requires internet connection to fetch live data
Limited to years 1961-2024 (when AP MVP award existed)
