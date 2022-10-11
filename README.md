# Changing Room Coding Challenge
#### Author: Lindsey Ching

This repository contains a notebook with my answer to the Changing Room Data Engineer Intern Coding Challenge. It crawls through The RealReal designer sweaters webpage and pulls the first six items. 

*How to crawl through the entire website*: Extracting all information from all webpages on the website would require updating the script to search through each webpage. I would first obtain a list of all URLs from The RealReal website by extracting the href (URL) of each category in the top-level menu (all categories for all genders). I would then modify my script to recursively access the relevant fields (product name, brand name, etc.) from each URL. I would rewrite my script as a function, add a progress bar, and capture a screnshot using webdriver to maximize efficiency and make debugging easier. 

*How to update the database*: Selenium is an appropriate tool for scraping dynamic web pages, like retail websites. Running the script will automatically update the database with new items and discard old items. 
