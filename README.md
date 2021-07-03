# Mission-to-Mars
Module 10


## Overview of Analysis
After creating Robin's web app she wanted to add some more polish.  She would like to add the four Mars Hemisphere images off of a web scraping friendly site.  We are going to do this using BeautifulSoup and Splinter to scrape the images and titles of the Mars Hempisphere's to store the data on a Mongo database.  We will use a web application to display the data and alter the design of the web app to acomodate the images.

## Resources:

Software: Software: Jupyter Notebook, Anaconda 4.10.1, Python 3.7.6, Visual Studio Code 1.56.0, MongoDB 4.4.6
 
Code: 	[Mission_to_Mars_Challenge.ipynb](Challenge/Mission_to_Mars_Challenge.ipynb) <b/r>
		[scraping.py](scraping.py) <b/r>
		[app.py](app.py) <b/r>
		[index.html](templates/index.html) <b/r>
		[style.css](static/css/style.css) <b/r>

## Results: 

![mars.png](Challenge/mars.png)




## Summary:

- The web app shows the latest Mars News, the Featured Mars Image, Mars Facts and the Mars Hemispheres.
- The background colour has been changed to a grey.
- The font colour of "h4", "h2", and "p" has been changed to white.
- The Mars Hemispheres section has been changed to allow 4 images on one row if viewed on a computer, while still being displayed 1 by 1 on a mobile device.
- The "jumbotron" has had the background colour changed as well as the font colour.
- For Mars Facts, the "tr", "td", and "th" have had the background and font changed. 

