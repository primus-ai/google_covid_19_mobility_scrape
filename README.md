# Google COVID-19 Mobility Reports Scraper

This dataset has been scraped from Google's Covid-19 Community Mobility Reports website. Core libraries include the tidyverse for data manipulation, rvest for web-scraping, and tabulizer for PDF-scraping.

Use countries.R and states.R scripts to procure new data when the website is updated. The scripts automatically add the current date to the filename of the saved CSVs.

Important Note: the data does not include county-level information.

Data Source: https://www.google.com/covid19/mobility/
