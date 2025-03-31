# UCLA Tech Clubs Web Scraper
This is a Python web scraper for gathering information on tech clubs at UCLA from their official student association page. It uses Selenium to automate browser actions and extract relevant data such as club names, emails, Instagram handles, and signatories.

Features:
Scrapes data from UCLA’s tech clubs page.

Extracts club names, emails, Instagram handles, and signatories.

Uses Selenium for headless browser automation.

Handles dynamic content loading through scrolling and waits for elements to appear before extracting data.

Organizes club information into structured data for easy use.

Requirements:
selenium for web automation.

webdriver_manager to manage ChromeDriver.

time for handling waits and delays.

# Using the scraper: 
Install the required dependencies:

```bash
pip install selenium webdriver_manager
```

```bash
python ucla_tech_clubs_scraper.py
```

This script extracts tech club details from the UCLA student association website and outputs a list of clubs with relevant information such as their contact email, Instagram links, and signatory names.

```json
{
    "name": "Tech Club 1",
    "email": "techclub1@ucla.edu",
    "signatory": ["Signatory 1", "Signatory 2", "Signatory 3"]
}
```
