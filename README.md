# EDA_Nepali_Job_Market

This project is related to exploratory data analysis on the job available in the nepali job market.
In order to analyze the data first I have collect the data from Merojob and JobaAxle job search websites.
The BeautifulSoup library is used for web scraping.
The data collected is then cleaned up with different techniques. 
Explore data using pandas library.
Plot graph with seaborn library.


Web Scraping from MeroJob
The python code to scrap data from merojob is names as web_scraping_merojob. The scrapped data is saved to merojob.csv file.

Web Scraping from JobAxle
The python to scrap data from JobAxle is named as web_scraping_jobaxle. Then the scrapped data from jobaxle is appended to the merojob.csv file. The merged csv file is then renamed to Merojob_jobaxle.csv and perform analysis on this csv file.
