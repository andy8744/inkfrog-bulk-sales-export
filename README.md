# inkfrog-bulk-sales-export

Scrapes the inkfrog orders page and exports all sales using python selenium.

## Motivation

Inkfrog is a website where you can sync your e-commerce websites. It is especially useful for eBay since it stores all previous orders whereas on eBay you can only view the past 90 days. 

Inkfrog only allows exporting 50 orders at a time - which is tedious and time consuming. I needed to export over 10k orders for bookeeping. I decided to make this to save a lot of time. 

## How to use

You will have to modify the jupyter notebooks to fit your needs (like some variables). 

scrape_inkfrog.ipynb does the web scraping using selenium. file_processing.ipynb checks for duplicates (incase there was an issue) and also combines all the downloaded csv files into one single file. 
