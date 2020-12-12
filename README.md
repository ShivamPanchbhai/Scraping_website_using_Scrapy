# Scraping_website_using_Scrapy

 I have used python and scrapy interpreter.I have coded this project using Pycharm IDE.

The website that I am scraping is -> https://quotes.toscrape.com/

 I have used sqliteonline database and I am scraping 3 things 1) Quote 2) Author 3) Tags


The major steps are as follows

1) Create the project folder with a name of your choice.

2) Install Scrapy.

3) Go to terminal and start project by writing 'scrapy project_name'.

4) Follow the instruction in the terminal of creating the spider. 

5) Copy the URL that you want to scrape in start URL.

6) Decide on the number of items that you want to scrape from the webiste and write the script for it under class in the items.py file.

7) The next step is to import the items.py file into project_name_spider.py file and that can be done by writing 'from ..items import class_name from items.py'
   in the project_name_spider.py file.

8) Now inside the parse method create items that will store the instance of the class which is declared in the items.py

9) Now declare the number of variables according to the number of items that you are planning to scrape

10) Use the css selector to select the title name and use extract() 

11) Repeat 10th step with all the items that you want to fetch.

12) add the paramter of extracting the text only by .css('::text')

13) after the extraction store them in items and yield them.

14) The next step is to create a table and store the information.

15) The next step is to load the database file into onlinesqlite.
