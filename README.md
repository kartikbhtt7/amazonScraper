# Amazon data scrapers
### This repo includes three scrapers(scrapy spiders) that can crawl over amazon's website and can fetch for information related to products, reviews and user search bar query responsers

## Using the scrapers:
- Fork and repo to your local directory
- If needed then create a virtual environment for this using the terminal
- In the terminal type
  > pip install -r requirements.txt
- Make changes in amazon/spiders/{amazon_reviews.py OR amazon_search_product.py OR amazon_search.py} in the product/category name to scrape for
- In the terminal use
  > scrapy list
  
  to list out all spiders present 
- Type
  > scrapy crawl {spider name}
  
  in terminal to make it crawl

#### * you need to have your's own scrapeops api key
#### * made only for learning purposes.
