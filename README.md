# How to use scrapy to extract html files
A test of scrapy
## Installation
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install scrapy.
```bash
pip install Scrapy
```
Please check the following links to get more information
https://docs.scrapy.org/en/latest/intro/install.html#installing-scrapy
## Usage
1. Create a new project
```bash
scrapy startproject porject_name
```
It would automatic generate a basic framework.

2. Create a spider
```bash
scrapy genspider spider_name domain
```
for example
```bash
scrapy genspider jobs quotes.toscrape.com
```
3. Run an exist spider

  Go to the root directory which contains a cfg file (scrapy.cfg)
  Then type the following code
  ```bash
  scrapy crawl spider_name
  ```
  
