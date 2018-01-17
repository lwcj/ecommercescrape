# ecommercescrape
sample of web scraping code for contract client

the client wanted me to scrape beauty and cosmetics websites to create a csv file consisting of the full product catalog of the website. this client was interested in obtaining the product name, product price, product url, image url, SKU (stock keeping unit).

this particular website used innerHTML, so while information is visible on the website and looks loaded in the HTML page source, when we use BeautifulSoup we see a lot of empty HTML tags. To do this we extract the innerHTML and we can proceed as normal.
