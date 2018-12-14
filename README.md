# glassdoor-salary-scraper

Current Version: 1.0

Glassdoor web crawler and scraper providing salary data. Forked and modified from [williamxie11](https://github.com/williamxie11/glassdoor-interview-scraper).

## Installation

* Python 2.7.*

* Beautiful Soup 4 (4.4.1)
```sh
$ pip install bs4
```
* Selenium Webdriver
```sh
$ pip install selenium
```

## Usage

1) Open the scraper Python script with a text editor of your choice.

2) Add your Glassdoor account username and password.

![](http://imgur.com/TVBtyr7.png)

3) Specify the number of pages, the city name, and the URL of the salaries page for the city on Glassdoor with your specified filters selected.

![](http://imgur.com/xcgzm1S.png)

4) Run the scraper
```sh
$ python scraper.py
```

NOTE: Glassdoor will require you to insert CAPTCHA on login or during the scraping process. The script will poll until CAPTCHA is entered during scraping.

## Results

![response](http://imgur.com/RlDhpbi.png)

The web scraper will output a JSON with the name "[city name].json" in the same directory. Each data point in the JSON corresponds to one salary on Glassdoor with attributes (company name, job title).

### Support:

If you want the good work to continue please support us on

* [PAYPAL](https://www.paypal.me/ishandutta2007)
* [BITCOIN ADDRESS: 3LZazKXG18Hxa3LLNAeKYZNtLzCxpv1LyD](https://www.coinbase.com/join/5a8e4a045b02c403bc3a9c0c)
