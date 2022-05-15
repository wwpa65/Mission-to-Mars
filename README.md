# Mission-to-Mars

## Overview

A web application was developed for web scraping and displaying data to include latest news and images of Mars using scraping tools and a [NASA news site](https:/redplanetscience.com), a website for[a featured image](https://spaceimages-mars.com), and another mars image site for extracting Mars's four hemisphere images and their titles ([Mars hemispheres](https://marshemispheres.com)). The webscraping process was performed autamically and Mars news and the URL and title of Mars four hespheres were saved was in a Mongo DB database (mars_app), and retrieved for displaying on the HTML page. In addition, a table of facts about Mars (and the Earth) was extracted from the [Galaxy Facts website](https://galaxyfacts-mars.com). The Chrome Webdriver and Splinter was used during this automated Webscraping process. Initially all the codes were written in Python using Jupyter notebook and the code was transferred into a Python script (Scraping.py). The Flask application was written using VS Code (app.py).

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
- Python 3.7 and dependencies
- Jupyter Notebook
- Web driver
- Splinter
- Beautiful Soup
- Mongo DB
- Flask
- Git

## Summary 
In summary, the web app enabled displaying latest Mars news, a featured image, Mars facts in a table, and images of the four Mars hemespheres. 

Files included: 
- Mission_to_Mars_Challenge.ipynb file with all the code used for scraping
- An updated scraping.py file
- app.py file
- index.html file in the template folder and any CSS stylesheets
- README.md
