# Mission-to-Mars
#### *HTML Web scraping on Mars data to create a Flask web application using Python and MongoDB*

## Overview
This project consisted on a Python script to scrape text and images from various websites that talked about Mission to Mars. Then, I created a Flask web application with a rendered HTML template designed using Bootstrap to display all the data in a central location without having to gather it manually. The data scraped and displayed was stored in a non-relational Mongo database. Additionally, I was able to connect the scraping script so that each time a button was clicked, the scraping occured once again, the database got updated, and new data was displayed. This button only works under the condition that these webpages don't change their HTML components I used for scraping. And lastly, by using Bootstrap's grid system I was able to create a responsive web app that could accomodate to any device people view it from. 

## Resources 
- Software: Python, Jupyter Notebook, Pandas, BeautifulSoup, Splinter, ChromeDriverManager, Flask, PyMongo, MongoDB, HTML5, Bootstrap 3

## Results
The final product was a fully-functional web application creted with Flask that included images, a table with information about Mars in comparison to Earth, and the latest article title and short description scraped from the NASA's webpage. Each time we click on the "Scrape New Data" button new information will be updated on both the website and the MongoDB. The database will be updated and each time new data is scraped it will be saved with a "last_modified" date to know when was the last time, as you can see in the bottom of the query results.
