# Data-Extraction
Data Extraction of Ministry of Health and Family Welfare
Data extraction or Web scrapping, is the process of retrieving or “scraping” data from a website.
this data can be saved into file or database for furthure processing.
>if web data is structured or contains some amount of structured information as
<table> tag then we should use pandas library.
	>if web data is unstructured or we want to parse information based on specific 
html tags then we should use BeautifulSoup or other similar libraries.

>requests library of python is frequently used for getting data from a given url.

	resp=requests.get('url')

>resp.content:	it returns html data as bytes

>resp.text:	it returns html data as string.
>initially we get data of a webpage in the form of html and we need to parse it to extract required information.

>BeautifulSoup object of bs4 library is frequently used to parse html data or xml data.
