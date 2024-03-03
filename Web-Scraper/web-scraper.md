# Python Web Scraper for News Aggregation

This Python web scraper fetches news data from various news websites and stores it in a MongoDB database.

## Prerequisites

- Python
- MongoDB

## Installation

1. #### Clone the repository:
Clone the repository to your local machine using the following command:
```
git clone https://github.com/H-R-S/MAD-Project
```

2. #### Project:
Navigate to the project directory:
```
cd Web-Scraper
```

3. #### Install the required packages 
Installs the pymongo package, which is a Python driver for MongoDB.
```
pip install pymongo
```
Installs the scrapy package, which is a web crawling and web scraping framework for Python
```
pip install scrapy
```

4. #### Install the requirements.txt
Installs packages listed in the requirements.txt file, if present. This is a common practice for managing project dependencies
```
pip install -r requirements.txt
```

5. #### Run the web scraper:
Runs the Scrapy spider named news-crawler, which is responsible for crawling news websites and extracting data.
```
scrapy crawl news-crawler
```

These commands are essential for setting up and running your Python web scraper project.

6. #### Output
```
2024-03-03 15:18:20 [scrapy.core.scraper] DEBUG: Scraped from <200 https://www.bolnews.com/business/2024/03/united-bikes-new-price-in-pakistan-march-2024/>
{'title': 'United Bikes new price in Pakistan- March 2024', 'feature_img': 'https://www.bolnews.com/wp-content/uploads/2024/03/FotoJet-2024-03-02T204724.763-635x430.jpg', 'description': ', a brand known for its budget-friendly motorcycles, competes directly with Japanese counterparts, especially when bike prices are high due to currency devaluation and import restrictions.While Honda, Yamaha, and Suzuki dominate the market for high-end bikes, United stands out for offering affordable entry-level bikes. The company has a variety of motorcycles in its lineup, including commuter bikes, sports bikes, and high-performance models. As of 2024, the most recent price for the United US 70 is Rs109,500. Additionally, the United US 125 is currently priced at Rs164,500 in Pakistan.Atlas Honda, a significant contributor to the country’s motorcycle industry, has brought... “We encourage you to verify all rates and specifications with the respective service providers or vendors before making any purchases or taking any action based on the information presented on this website.”', 'Category': '', 'time': '02nd Mar, 2024.'}
2024-03-03 15:18:20 [scrapy.core.engine] INFO: Closing spider (finished)
```

