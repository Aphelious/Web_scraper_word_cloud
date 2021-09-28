# Webscraper Word Cloud

This is a simple script that scrapes popular job posting sites for search results containing the word 'Python'. The script will parse the requested hmtl 
file and strip away everything but the job description. Some simple descriptive statistics will then be calculated to identify what other terms are
most-associated with the term 'Python', ie. 'Numpy' or 'Pandas'. The script will then generate a .png or .svg file containing the top 25 or so terms with 
the font size proportional to the relative frequency of the term, a 'word cloud'. the html requests will have to be spaced out in 30-second increments to avoid
anti-scraping protective measures of various platforms. 
