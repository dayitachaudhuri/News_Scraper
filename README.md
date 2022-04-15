# News_Scraper

This is a Python Web Scraping Project that uses the Scrapy Framework. 

Scrapy (/ˈskreɪpaɪ/) is an application framework for crawling web sites and extracting structured data which can be used for a wide range of useful applications, like data mining, information processing or historical archival. Even though Scrapy was originally designed for web scraping, it can also be used to extract data using APIs (such as Amazon Associates Web Services) or as a general purpose web crawler. For more information of scrapy, refer to https://docs.scrapy.org/en/latest/

## Getting Started with Scrapy
Clone the repository in you device

    git clone https://github.com/dayitachaudhuri/News_Scraper

Install the required packages.

    pip install -r requirements.txt
    
Navigate to the spiders directory and run the spider.

    cd News_Scraper/articlescraper/articlescraper/spiders
    scrapy runspider yahoo.py
    
You will find a new news_article.json file in your spiders directory with the scraped data.
