this code is for scraping amazon products to be analyzed by SQL BigQuery 
-First the user is asked to paste products links 
-these products details will be scrapped using BeautifulSoup (name, price, reviews...etc)
-the scrapped data will be saved into a csv,file name contains the date of **today** 
-the raw data will be cleaned and saved into a new csv 
-the new csv will be pushed into BigQuery to be analyzed 
