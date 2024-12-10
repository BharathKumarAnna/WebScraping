# WebScraping
Cantelever labs projects.
reference: https://docs.scrapy.org/en/2.11/intro/tutorial.html

1. create a new virtual environment using-> 
    conda activate scrapytutorial_env
2. To start spider->  scrapy crawl quotes
3. use this to extract data.                                    -> scrapy shell 'https://quotes.toscrape.com/page/1/'
4. The simplest way to store the scraped data is by using Feed exports, with the following command:

-> scrapy crawl quotes -O quotes.json
That will generate a quotes.json file containing all scraped items, serialized in JSON.
