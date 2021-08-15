# Our Topic is about Web Scraping

![web scraping](https://roboticsandautomationnews.com/wp-content/uploads/2020/04/web-scraping-2.png)

> Web scraping is a technique to automatically access and extract large amounts of information from a website, which can save a huge amount of time and effort.

## Important Things to consider before web scraping:

 - Read through the website’s Terms and Conditions to understand how you can legally use the data. 
 - Make sure you are not downloading data at too rapid a rate because this may break the website. You may potentially be blocked from the site as well.

## So in order not to be blocked by the website follow the steps below

## Web Scraping best practices to follow to scrape without getting blocked

1- Respect Robots.txt

2- Make the crawling slower, do not slam the server, treat websites nicely

3- Do not follow the same crawling pattern

4- Make requests through Proxies and rotate them as needed

5- Rotate User Agents and corresponding HTTP Request Headers between requests

6- Use a headless browser like Puppeteer, Selenium or Playwright

7- Beware of Honey Pot Traps

8- Check if Website is Changing Layouts

9- Avoid scraping data behind a login

10-Use Captcha Solving Services

## Steps for web scraping

## Inspecting the website first

- On the website, right click and click on “Inspect”. 
- Notice that on the top left of the console, there is an arrow symbol
- If you click on this arrow and then click on an area of the site itself, the code for that particular item will be highlighted in the console
- Notice that all the .txt files are inside the < a > tag 

## Python Code

 - We start by importing the following libraries (import requests,import urllib.request import time , from bs4 import BeautifulSoup)

 - Next, we set the url to the website and access the site with our requests library.

 - Next we parse the html with BeautifulSoup so that we can work with a nicer, nested BeautifulSoup data structure
 
 - We use the method .findAll to locate all of our < a> tags.

 - We should include this line of code so that we can pause our code for a second so that we are not spamming the website with requests. 

 `time.sleep(1)`