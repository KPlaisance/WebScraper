# Python Century21 WebScraper

Michael Plaisance

This project is a webscraper using Python. It is designed to scrape property listings from Century21's website and provide useful data to the user. The data is collected and presented in a Pandas dataframe as well as output to a .CSV file to the user's computer.

This project was used as part of a Python course on Udemy (https://www.udemy.com/the-python-mega-course). Currently Century21 has blocked scraping tools from visiting their live site and because the Century21 website changes constantly, a cached version of the site was used.

## How To Use The Program

Be sure to have Python3 installed and a program to open IPython (Jupyter) notebooks. In addition, you'll need these dependancies installed:

- requests
- pandas
- BeautifulSoup 4

Open the file "real_estate_scraper.ipynb"

Click "Run" at the top of the page. This will run the program and display the pandas DataFrame. It also outputs the DataFrame to a file called "Output.csv" to the same directory the file is in.