![IronHack Logo](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_d5c5793015fec3be28a63c4fa3dd4d55.png)


# Project: Web Scrapping
Scrapping data from a website using python


## Overview

The objective is to scrap data from https://www.carrefour.fr/promotions for all promotion pages and start analysing the promotions of the brand.


## Process followed

### Librairies used

- requests
- json
- pandas
- bs4
- os
- time

### Steps

- Counting the number of promotion pages with BeautifulSoup
- Scrapping all the pages with json (API) on a timer
- Cleaning the data obtained into a single dataframe with pandas
- Analysing the data obtained: how many promotions, which category and subcategory, what has really been promoted?


## Results

- A complete dataframe saved as a CSV
- A dataframe analysing the number of promotions per category and subcategory
- The number of products on the promotion page having the same price as before being promoted
- 2 graphs: the promotions per subcategory and the top 10 brands promoting products on Carrefour.
