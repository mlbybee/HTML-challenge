Michelle Bybee-Moody

Module 11 - HTML Web-Scraping Analysis Project

Description:
This new assignment consists of two technical products:

Deliverable 1: Scrape titles and preview text from Mars news articles.

1. Use automated browsing to visit the "Mars news site" and inspect the page to identify which elements to scrape using Chrome DevTools.
2. Create a Beautiful Soup object and use it to extract text elements from the website.
3. Extract the titles and preview text of the news articles that you scraped.
4. Store all the dictionaries in a Python list.
5. Print the list in your notebook.
6. Optionally, store the scraped data in a file (to ease sharing the data with others). To do so, export the scraped data to a JSON file.

Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

1. Use automated browsing to visit the "Mars Temperature Data Site" and inspect the page to identify which elements to scrape using Chrome DevTools.
2. Create a Beautiful Soup object and use it to scrape the data in the HTML table.
3. Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website.
4. Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate 'datetime', 'int', or 'float' data types.
5. Analyze your dataset by using Pandas functions to answer the following questions:

* How many months exist on Mars?
* How many Martian (and not Earth) days worth of data exist in the scraped dataset?
* What are the coldest and the warmest months on Mars (at the location of Curiosity)? 

To answer this question:
- Find the average minimum daily temperature for all of the months.
- Plot the results as a bar chart.
 
* Which months have the lowest and the highest atmospheric pressure on Mars? 

To answer this question:
- Find the average daily atmospheric pressure of all the months.
- Plot the results as a bar chart.

* About how many terrestrial (Earth) days exist in a Martian year? 

To answer this question:
- Consider how many days elapse on Earth in the time that Mars circles the Sun once.
- Visually estimate the result by plotting the daily minimum temperature of each observation.

6. Export the DataFrame to a CSV file.

Support Received: Lectures, Xpert Learning Assistance, Ww3schools website, Stack Overflow. 
