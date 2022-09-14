# Web_Scraping_Taiyo

In this code, libraries like Pandas, BeautifulSoup and requests are imported. After that, url which has to be scrapped, called through requests.get() function.
After that, BeautifulSoup object is created with content from web page to be scrapped. Next find function is invoked which takes id name or class name of the html entity, we wish to scrape. Next, we enter a loop which takes row by row starting from first row and also the table data in the particular row which is printed and strip by the help of .text and .strip functions. 
Next this data is stored in the list, one by one according to the table row in the web page. 
After that this list is unzipped in Pandas dataframe and then converted to csv and exported out.
All this is done in Python class and gets executed on creating an instance of class.  
