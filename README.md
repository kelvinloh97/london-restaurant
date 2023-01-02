# london-restaurant
This study is an analysis of data scraped from the top 90 restaurants on Tripadvisor. 

The data from Tripadvisor is obtained by scraping Tripadvisor using selenium by finding web elements related to relevant features by locating the elements' xpath. 

A data analysis and data visualisation is done on Tableau to demonstrate the results obtained from this study. 

## How to read the files?
tripadvisor_restaurant_features.ipynb and tripadvisor_review.ipynb are the codes used to scrape the tripadvisor data using selenium

EDA on tripadvisor data.ipynb is the code used to conduct a high-level EDA analysis on the scraped tripadvisor data

## Key takeaways
From the data analysis, I would like yo ask this main question:
1. What makes a specific restaurant top the tables in London

a. Location
We can see that North London (Islington and Hampstead Heath) has the most number of restaurants in the dataset, followed by individual locations in Central London. 

![restaurant_location_count](https://user-images.githubusercontent.com/32938429/210211964-f6c6a8b9-01e2-425e-8636-bd8e52d4edf6.PNG)

In terms of cuisine, London's No.1 goes to Indian with Italian coming in second. 

![restaurant_cuisine_type](https://user-images.githubusercontent.com/32938429/210211933-1a637204-b759-4dc0-86d9-acc5f91f3ffd.PNG)

76% of tripadvisor's top 90 restaurants in London have mid-range prices. 

![restaurant_pricerange](https://user-images.githubusercontent.com/32938429/210211927-d5041330-1614-4183-8fba-1b4a835fee05.PNG)

When conducting a term frequency analysis on the reviews, we can output a word cloud. This indicates the best features for a good restaurant from the customer's perspective. The top 3 standout words for good reviews are food, staff and service (unsurprisingly the top features of a good restaurant).

![what_makes_restaurant_great](https://user-images.githubusercontent.com/32938429/210211920-97b76fb0-c1d5-4779-acd5-5e4006fffb0a.PNG)

This small study gives London restaurant owners some food for thought when it comes to features to focus on when running their restaurant and what appeals most to the London customers. 
