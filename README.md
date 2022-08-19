# Creation of a Mars Website

## Overview:
As an astronomy hobbyist, Robin wants to build a web app that pulls in Mars data from a variety of sources into a single location. By using web-scraping tools she can save herself time in the long-run and her hopefully one day attract the attention of NASA, her dream employer. Her initial work scraping the latest Mars news, featured photos, and facts has gone well. Now, a scrape of the red planet's hemisphere's needs to be completed, along with some aesthetic improvements to the web app.

## Process:
The scraping process started with using BeautifulSoup and Splinter in Python to scrape data and store it into a non-relational database, MongoDB. Then a Flask app was created to store the scraped results on a webpage.

### Challenges Encountered:
I was able to successfully complete the deliverable 1 scrape of hemisphere urls and titles. However, in deliverable 2, I ran into issues in my scraping.py file. I added in the new hemisphere function to the file, but kept receiving the error: ***selenium.common.exceptions.StaleElementReferenceException: Message: stale element reference: element is not attached to the page document*** when I ran the scraping.py file in VS code. This prevented the hemisphere images from making it to the webpage. I went ahead for deliverable 3 and made some cosmetic improvements to the web app like shrinking the button size to medium and making it 'btn-info' which changed it to a light blue color. I also changed the color of the Mars Facts heading to red to stand out more and centered it over the table. I used the toggle device toolbar to verify my webpage was mobile friendly. Since I never was able to add the hemisphere images, I never needed to adjust any classes/dimensions since everything already present fit.


![Flask_screenshot](https://github.com/bfox87/Mission-to-Mars/blob/main/Screenshots/Flask_screenshot.PNG)