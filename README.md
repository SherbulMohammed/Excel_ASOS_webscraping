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

![column link and price](https://user-images.githubusercontent.com/129470579/231832540-6d1e6f53-641d-423d-a515-bc2ef92019e9.png)

![split column pic name and price](https://user-images.githubusercontent.com/129470579/231832761-b7adcda6-a198-4dfe-83e5-32cbb95c26ef.png)

- Links column was split in order to create a new column - 'Price'
- 'Split Column by Delimiter - £'
- Column's name was changed to 'Name'

- Price column data type was changed to decimal number

![replaced values colour](https://user-images.githubusercontent.com/129470579/231832891-efd35d98-a044-482b-a981-52f8438d867c.png)
- Colour column - 'replace values' was used to change all the text to lowercase eg: (WHITE, white, STONE) - (white, white, stone)

*Cleaned data*

![clean data](https://user-images.githubusercontent.com/129470579/231644172-8f699f7e-7bbe-4d3b-a5e1-cda79df3cbaa.png)


*Statistics*

Some exploratory data analysis was carried out on the data:
- average price of a trainer was £79.95
- lowest priced trainer was £20 which was an ASOS DESIGN brand
- highest priced trainer was £209.00 which was a Dr.Martens brand
- the total number of trainers in the data was 144
- the total number of brands was 36

*Brand*

![brand stock count](https://user-images.githubusercontent.com/129470579/231833600-73c3c439-9909-4c9f-9504-79bd6f5680a5.png)

- ASOS DESIGN brand has the highest stock count at 16 followed by by Crocs with 12 trainers,  and Vans with 11.
- This chart analysis indicates that ASOS DESIGN is the brand with the highest stock availabilty in the mens latest trainers category
- Simple explanation for this could be ASOS want to push their own brand forward so will ensure it has a high market share in the category
- Market share: ASOS DESIGN - 11%, Crocs - 8.3% and Vans - 7.6%

*Price*

![avg trainer price graph](https://user-images.githubusercontent.com/129470579/231833665-e841dbd1-03e7-4959-b6a3-782412cc4188.png)

- Dr. Martens has an average trainer price of £135.99 with 6 trainers in stock
- Timberland has an average trainer price of £131.88 with 8 trainers in stock


![avg trainer price scatter graph](https://user-images.githubusercontent.com/129470579/231833750-a0f6981a-860f-4247-9170-ee3e669b1164.png)

**Correlation between average trainer price and stock count:**
- slight negative correlation which could indicate that brands with higher average trainer prices tend to have lower stock availability
- There are few outliers in this data as many brands only have 1 trainer in stock: 'The North Face' brand has only one trainer at stock which costs £110.

*Colour*

![black price graph](https://user-images.githubusercontent.com/129470579/231833836-7aa9fbc3-8e73-4a62-9289-cf531fea74b6.png)

Black is seen to be the most popular colour in terms of sales at £2895, followed by White at £1383 and Beige at £889.

![Top 5 colours total price](https://user-images.githubusercontent.com/129470579/231834098-39a58a7f-94df-4982-a84e-4c446587693c.png)

Factors why 'Black' is the highest selling colour in the ASOS mens latest trainer category:
- Black is a neutral colour that can easily match with a wide range of clothing
- Black is often considered as a classic colour known for its versatility - could be highest selling colour due to its high demand in fashion trends
- Certain brands like 'Nike' are known for their black-coloured trainers - Air Force Ones which have a reputation of being popular and stylish in Men's trainers

![no of trainers each colour](https://user-images.githubusercontent.com/129470579/231834182-cb1026ac-0452-4679-9833-4b12633a1639.png)

Black tends to be the most popular colour in terms of stock at 36, followed by white at 16 and grey at 9.

![colour brand](https://user-images.githubusercontent.com/129470579/231834602-ce81a859-da08-4a6e-90ec-2a894510de19.png)

For the brand Dr. Martens, the colour 'black' has a higher price point - (sum of all black trainers)




