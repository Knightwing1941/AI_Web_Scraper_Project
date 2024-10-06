AI Web Scraper

This project is an AI-powered web scraper built with Python. This scraper uses artificial intelligence to extract data from web pages, making it more versatile compared to traditional scrapers.

Features
- AI-Based Content Extraction: Use AI models to understand the structure of a webpage and extract relevant data.
- Flexible Scraping: Capable of scraping data from various websites without the need for detailed custom configurations.
- Customization: Allows customization for specifying data types to extract, like titles, articles, prices, etc.

Prerequisites
- Python 3.8 or higher
- PyCharm (optional, but recommended for development)

Installation

1. Clone the Repository:
   
   git clone https://github.com/Knightwing1941/AI_Web_Scraper_Project
   cd AI_Web_Scraper_Project

3. Create a Virtual Environment:
   
   python -m venv venv
  
5. Activate the Virtual Environment:

   - On Windows:
     
     venv\Scripts\activate
     
   - On MacOS/Linux:
     
     source venv/bin/activate
     

6. Install Dependencies:
   
   pip install -r requirements.txt
   

 Usage
1. Configure the Scraper: Modify the `config.json` file to specify the target website and the types of data you want to extract.
   I would recommend https://toscrape.com/ as it is perfect to scrape from

3. Run the Scraper:
   
   python scraper.py

4. View the Results: Extracted data will be saved in a file (`output.json`) or printed to the console, depending on your configuration.

 Configuration
- Target URL: Specify the URL of the website you wish to scrape.
- Data Types: Define what kind of data you want to scrape (e.g., headers, paragraphs, prices).

 Important Notes
- Respect Website Policies: Make sure to comply with the website’s `robots.txt` and scraping policies.
- Usage Limitations: Excessive scraping can result in IP bans or legal issues. Use responsibly.

 Dependencies
- `beautifulsoup4`
- `requests`
- `openai` (or another AI model provider, as shown in the tutorial)
- Other dependencies as listed in `requirements.txt`

