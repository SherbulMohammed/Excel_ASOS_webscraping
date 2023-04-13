# Project Overview
**The data set used in this project is from ASOS : https://www.asos.com/men/**

This aim of this project was to gather information about latest men's trainers from the ASOS website through data scraping which could then be utilised for data analysis. 

Tools used in this project:
- **Webscraper.ao** - to scrape the data off the ASOS website and convert it to .xlsx file
- **Excel** - used power query to clean the data before it could be analysed 

Webscraper was utilised to extract relevant information such as product names, brands, colours etc from the ASOS websites mens latest trainers category 

Excel was used to identify insights related to ASOS mens latest trainers category

*Raw data* 

![raw data](https://user-images.githubusercontent.com/129470579/231616356-1a158714-5764-4b42-80f0-8b94710c0b4e.png)

- column headings were added during webscraping process

- columns were removed: web-scraper-order, web-scraper, Links-href, pages, Pages-href

(insert links column pic)

(insert links column split price)
- Links column was split in order to create a new column - 'Price'
- 'Split Column by Delimiter - £'
- Column's name was changed to 'Name'

- Price column data type was changed to decimal number

(insert replace values for colour)
- Colour column - 'replace values' was used to change all the text to lowercase eg: (WHITE, white, STONE) - (white, white, stone)

*Cleaned data*

![clean data](https://user-images.githubusercontent.com/129470579/231644172-8f699f7e-7bbe-4d3b-a5e1-cda79df3cbaa.png)


*Statistics*

(insert statistics image)

Some exploratory data analysis was carried out on the data:
- average price of a trainer was £79.95
- lowest priced trainer was £20 which was an ASOS DESIGN brand
- highest priced trainer was £209.00 which was a Dr.Martens brand
- the total number of trainers in the data was 144
- the total number of brands was 36

*Brand*

(insert brand graph picture)







