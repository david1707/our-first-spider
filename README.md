# Our first spider
Created for my Scrapy tutorial, a Scrapy bot that scrapes quotes from quotes.toscrape.com

## Getting Started
Before anything, I have several branches to select for. Each branch has a different use. You can select from:

master - Original and baseline branch

basic_spider - Scrapes the initial page from quotes.toscrape.com

next_page_spider - From the 'basic_spider', no paginates over all the pages

details_spider - Paginates quotes.toscrape.com, getting the details of every quote navigating to the author's page


### Installing

```
https://github.com/david1707/our-first-spider
```

If you don't have Scrapy, create an enviroment (better pipenv than virtualenv) and install it.


### Usage

Navigate to the main folder, then run it with:
```
scrapy crawl main_spider
```

If you want to save the yield result, do it like this:

```
scrapy crawl main_spider -o my_quotes.json
```

You have available the following extensions: .json, .xml, .csv


## Built With

* [Python](https://www.python.org/) - Python is an interpreted high-level programming language for general-purpose programming.
* [Scrapy](https://scrapy.org/) - An open source and collaborative framework for extracting the data you need from websites.

## Author

* **David Membrives** - *Initial work* - [david1707](https://github.com/david1707)

## About this project
This github project was created for my Scrapy tutorial. You can check it here: https://letslearnabout.net/tutorials-py/scrapy-our-first-spider-tutorial/

## Contact me:
If you have any suggestion, idea or want to tell me something, reach me at davidmm1707@gmail.com

## License

This project is licensed under the ISC License
