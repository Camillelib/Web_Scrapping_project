# Project: Web Scraping
Scraping data from a website using python


## Overview

The objective is to scrap data from https://www.carrefour.fr for all pages and start analysing products categories and promotions.


## Process followed

### Librairies used

- math
- requests
- json
- pandas
- bs4
- os
- time
- matplotlib.pyplot
- seaborn 

### Steps

- Deciding which type of page to scrap: products or promotions
- For products, choosing a category to scrap
- Counting the number of pages with BeautifulSoup
- Scraping all the pages with json (API) on a timer
- Cleaning the data obtained into a single dataframe with pandas
- Analysing the data obtained: 
  - For product categories: what subcategories are the most represented, what are the top 10 brands selling products on Carrefour.com?
  - For promotions: how many promotions, which category and subcategory, what has really been promoted?


## Results

- A complete dataframe saved as a CSV

- For products:
  - 2 graphs: the number of products per subcategory and the top 10 brands selling products on Carrefour.
 
- For promotions:
  - A dataframe analysing the number of promotions per category and subcategory
  - The number of products on the promotion page having the same price as before being promoted
  - 2 graphs: the number of promotions per subcategory and the top 10 brands promoting products on Carrefour.
 

![Graph_categories](https://github.com/Camillelib/Web_Scrapping_project/blob/master/Output/Promotions%20per%20subcategory.png?raw=true)
![Graph_brands](https://github.com/Camillelib/Web_Scrapping_project/blob/master/Output/Promotion%20per%20brands%20(Top%2010).png?raw=true)
