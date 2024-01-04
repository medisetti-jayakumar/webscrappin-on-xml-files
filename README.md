# WEBSCRAPPING THE XML FILES USING BEAUTIFUL SOUP

### Extracting the text from the XML files  (single or multiple files)

[Click for Entire Project Code](https://github.com/medisetti-jayakumar/webscrappin-on-xml-files)

## About Webscrapping
 Web scraping is a powerful tool for extracting valuable data from websites, HTML Files, XML files etc...

    1. HTML Structure:

    Web scraping involves extracting data from websites by analyzing the HTML structure.

     2. HTTP Requests:

    Initial data retrieval is achieved through HTTP requests to the website's server, often using tools like Python's requests library.

    3. HTML Parsing:

    Parsers, such as BeautifulSoup, navigate the HTML tree structure to extract desired information.

    4. CSS Selectors and XPath:

    Selectors like CSS and XPath are used to pinpoint HTML elements for data extraction based on tags, classes, or IDs.

    5. Robots.txt and Terms of Service:

    Adherence to a website's robots.txt and terms of service is crucial to maintain ethical and legal standards in web scraping.
    
    6. Dynamic Content and AJAX:

    For websites with dynamic content loaded by JavaScript, tools like Selenium may be necessary for interacting with the page.

    7. Headers and User Agents:

    Setting headers and user agents in HTTP requests mimics human-like browsing behavior, helping to avoid anti-scraping mechanisms.

    8. Data Cleaning and Preprocessing:

    Extracted data often requires cleaning and preprocessing to address formatting issues and ensure usability.

    9. Ethical Considerations:

    Ethical scraping practices involve respecting website guidelines, avoiding server overloading, and conducting activities within legal bounds.

    10. APIs vs. Web Scraping:

    When available, using APIs for structured data access is preferable to scraping due to reliability and stability.

    11. CAPTCHA Handling:

    Websites may use CAPTCHAs to deter automated scraping, requiring solutions that raise ethical considerations.

[click here for more](https://www.geeksforgeeks.org/what-is-web-scraping-and-how-to-use-it/)

## Toolos & Libraries used:
    - PYTHON
    - NLP
    - BEAUTIFUL SOUP
    - REQUESTS

## Input Data
[Download XML_file](https://github.com/medisetti-jayakumar/webscrappin-on-xml-files/blob/main/162914.xml)
## Installation
- Install the NLTK

        pip install nltk

- Install the Beautiful Soup

        pip install beautifulsoup

## Steps:
    1. Import all the required libraries
    2. call the xml files
    3. request all those XML files in one url"S
    4. Using beautifulsoup , extract the required text by mentioning the id_ or class_
    5. Now, remove the unwanted text, numbers and symbols
    6. Again remove the stopwords and length of words less than the 3
    6. Visual the Extracted text
    7. Find the high sxcoring sentences and the high scoring words
    8. Visual all the highscoring words by using the WordCloud

## Code for Webscrapping
[click here for code](https://github.com/medisetti-jayakumar/webscrappin-on-xml-files/blob/main/webscraping_for_xml_files.ipynb)

## Result
The Extracted Text was visual in this format
![Alt text](<image_folder/Screenshot 2023-12-26 214924.png>)

## Applications

    - Price Monitoring
    - Marjet Research
    - E-Mail Marketing
    - News MOnitoring
    - Sentiment Analysis
