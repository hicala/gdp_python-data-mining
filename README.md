# GDP Data Mining. 

    _Tools: Python, Jupyter Notebook, BeautifullSoup, Pandas_

		
## Summary

This App is a result of my personal efforts to master the web scraping process using Python and BeatifuSoup. The document contains all the step by steps about how to scrape a Wikipedia page using Python3 and Beautiful Soup and finally exporting it to a CSV file. 

## Situation

<em>Why do many economists expect income convergence between developed and developing countries?</em>

In this process we decided to put together all the information related to the GDP and see it relationship per capita. Per capita GDP is a metric that breaks down a country's GDP per person and is calculated by dividing the GDP of a country by its population.

Gross domestic product (GDP) is the market value of all final goods and services from a nation in a given year. Countries are sorted by nominal GDP estimates from financial and statistical institutions, which are calculated at market or government official exchange rates. 

## Tasks

We got the information for the analysis from https://en.wikipedia.org/wiki/List_of_countries_by_GDP_(nominal)

Extract the GDp per Country for further comparison and data visualization from this [Data Source](https://github.com/hicala/hilca_gdp/blob/main/images/input.PNG)

## Actions
1. Sending an HTTP GET request to the URL of the webpage that you want to scrape, which will respond with HTML content. We can do this by using the Request library of Python.

2. [Data Input](https://github.com/hicala/hilca_gdp/blob/main/images/data.PNG?raw=true)

3. Fetching and parsing the data using Beautifulsoup and maintain the data in some data structure such as Dict or List.

4. Analyzing the HTML tags and their attributes, such as class, id, and other HTML tag attributes. Also, identifying your HTML tags where your content lives.

5. Outputting the data in any file format such as CSV, XLSX, JSON, etc.


## Results

+ [3 different files corresponing to each years of analysis.](https://github.com/hicala/hilca_gdp/blob/main/images/output.PNG?raw=true)

+ [Python App](https://github.com/hicala/hilca_gdp/blob/main/gdp_picker.py)

+ Jupyter Notebook instructional step by step Guide


## Take-aways

1. Legality is a MOST. It is important to know the Legality of web scraping before starting scraping a website.
2. Using scraped data for research and personal use.
3. Do not plan to republish that data.
4. Read the Terms of Use, Conditions of Use, and also the robots.txt before scraping the website.
5. You must follow the robots.txt rules before scraping, otherwise, the website owner has every right to take legal action against you.


## Acknowledgement

Special thanks to Gaurav Singhal for all the training info and assistances provided in the process


