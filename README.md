# What is web scraping?
---------------------------------------------------------------------------------------------------------------------------
[(attachment:Screenshot%20%2823%29.png)](https://github.com/srjrahul/web_scraping_flipkart/blob/e4b1789e87335fdf981ed70ae896635d430404c4/Screenshot%20(23).png)

- Web scraping, web harvesting, or web data extraction is data scraping used for extracting data from websites. Web scraping software may directly access the World Wide Web using the Hypertext Transfer Protocol or a web browser. While web scraping can be done manually by a software user, the term typically refers to automated processes implemented using a bot or web crawler. It is a form of copying in which specific data is gathered and copied from the web, typically into a central local database or spreadsheet, for later retrieval or analysis.

## Library used for Web Scraping

   - **Pandas:** Pandas is a library used for data manipulation and analysis. It is used to store the data in the desired format.
   - **BeautifulSoup:** BeautifulSoup is the python web scraping library used for parsing HTML documents. It creates parse trees that are helpful in extracting tags from the HTML string.
   - **Selenium:** Selenium is a tool designed to help you run automated tests in web applications. Although it's not its main purpose, Selenium is also used in Python for web scraping, because it can access JavaScript-rendered content (which regular scraping tools like BeautifulSoup can't do). We'll use Selenium to download the HTML content from Flipkart and see in an interactive way what's happening.

## 1.Scraping agenda

- Today we are going to scrap the smartphone data from the e-commerce site www.flipkart.com 
- Steps are following as-
    - Import necessary libraries.
    - Find th URL that we want to scrap.
    - Inspect the tags and html.
    - The data we want to extract.
    - Store the data into csv file.
