# Reddit webscraper
This scraper uses the popular scraping library Scrapy. For more information: https://github.com/scrapy/scrapy

# Setup
All commands are executed in the
<code>/reddit_scraper/reddit/reddit/spiders  </code> directory

# See the results of Reddit's front page in your command line
Run <code>scrapy crawl reddit</code>

# To crawl a specific subreddit
scrapy crawl reddit -a subr=SUBREDDIT_NAME

ex: <code>scrapy crawl reddit -a subr=programming</code>

# Store the results of any call in a file
scrapy crawl reddit -o FILE.EXT

ex: <code>scrapy crawl reddit -a subr=programming -o program.json </code>


Supported file extensions: 'xml', 'jsonlines', 'jl', 'json', 'csv', 'pickle', 'marshal'

File is stored in the "spiders" directory


# Other notes
This scraper only scrapes the "hot" section





