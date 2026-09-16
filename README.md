U.S. LARGEST COMPANIES WEBSITE SCRAPING PROJECT

PROJECT OVERVIEW

This project demonstrates the use of Python to extract structured data from a Wikipedia webpage containing a list of the largest companies in the United States by revenue.
The webpage was scraped using Requests and BeautifulSoup, while Pandas was used to organize the extracted information into a structured DataFrame and export the results as a CSV file.
URL USED FOR THE PROJECT : 'https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue'


OBJECTIVE

The objective of this project was to:
* Retrieve data from a live webpage
* Identify and extract an HTML table
* Convert the extracted information into a structured dataset
* Store the resulting data in CSV format for further use and analysis


TOOLS & LIBRARIES

* Python
* Requests
* BeautifulSoup
* Pandas
* Jupyter Notebook


PROJECT WORKFLOW

1. Identified the target Wikipedia webpage.
2. Sent an HTTP request to retrieve the webpage.
3. Parsed the webpage using BeautifulSoup.
4. Located the relevant company table.
5. Extracted the table headers and company records.
6. Created a Pandas DataFrame from the extracted data.
7. Exported the resulting dataset to CSV.


LIMITATIONS

* The project relies on information available on the source Wikipedia page.
* Wikipedia content can change over time.
* The project focuses primarily on data extraction and structuring rather than advanced data analysis.

