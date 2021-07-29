# Master thesis using IMF publications
One of my Master thesis involved the analysis of thousands of technical publications by the International Monetary Fund (IMF) from 1998 to 2013. The objective was to find changes in technical messages and policy recommendations to member countries since the international financial crisis of 2008-2009.

At the IMF webpage there is information on all IMF publications since 1980, almost 20 thousand, as well as the path to the electronic version for most of them. However, this information is not available on a database format, simply available through a list of web elements after a search action is performed, thus making it difficult and very time consuming to process and analyse.

In this respository you will find the Python code to scrape the site and create an SQL database with the data, making it easily available for my analysis once all necessary searches are performed.

The tool is used in a specific example to create an SQL database with all Article IV reports by the IMF during the years 2007 and 2013. Data can then be used for analysis and building visualizations.

## Repository contains:
- "IMF get all data.py" - Python code to create a SQL database of IMF publications, scraping the IMF web.

- "download_files.py" - Python code to download all relevant documents to folder.

- "Search_pdf.py" - Python code to perform text searches in selected pdf documents and store relevant data to database.

- "IMF pub database.ipynb" - Copy of colab project where all code is shown and with link to colab to run. Includes link to a Power BI report that uses the newly created database.
