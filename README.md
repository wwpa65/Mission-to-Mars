# Mission-to-Mars

Robin's web app is looking good and functioning well, but she wants to add more polish to it. She had been admiring images of Mars’s hemispheres online and realized that the site is scraping-friendly. She would like to adjust the current web app to include all four of the hemisphere images. To do this, you’ll use BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of those images, store the scraped data on a Mongo database, use a web application to display the data, and alter the design of the web app to accommodate these images.

The Mission_to_Mars_Challenge.ipynb file with all the code used for scraping.
An updated scraping.py file.
The app.py file.
The index.html file in the template folder and any CSS stylesheets.
A README.md that describes the purpose of the repository. Although there is no graded written analysis for this challenge, it is encouraged and good practice to add a brief description of your project.


## Overview

## Methods

A web application was developed for web scraping on news and images of Mars using scraping tools and a [NASA news site](https:/redplanetscience.com) and a website for[a featured image](https://spaceimages-mars.com), and another mars image site for Mars hemispheres. [Mars hemispheres](https://marshemispheres.com). The latest news (title and paragraph) was scraped autamically and was saved in Mongo DB database, and retrieved for displaying on the HTML page. In addition, a table of facts about Mars (and the Earth) was extracted from the [Galaxy Facts website](https://galaxyfacts-mars.com). The Chrome Webdriver and Splint was used during this process. Initially all the codes were written in Python using Jupyter notebook and the code was transferred into a Python script (Scraping.py). The Flask application was written using VS Code. 

The web application was further improved as follows:
  - mobile responsive
  - included a better background image
  - the Mars facts table has striped rows
  - Mars hemispheres appear as thumb nails

Links to websites:
- [NASA Mars News](https:/redplanetscience.com) 
- [Featured Mars Image](https://spaceimages-mars.com)
- [Mars hemispheres](https://marshemispheres.com)
- [Galaxy Facts website](https://galaxyfacts-mars.com).

**Software tools and database:**
Python 3.7 and dependencies
Jupyter Notebook
Web driver
Splint
Beautiful Soup 4.0
Mongo DB

## Summary
