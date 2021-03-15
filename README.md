# Heroes of Pymoli Project

![Fantasy.png](HeroesofPymoli/Images/Fantasy.png)

## Background

The Heroes of Pymoli project was designed to provide real world data analytics experience using a mock environment.  Heroes of Pymoli is a fictious video game company which requires player analysis to increase their market share. 

The mock-company models many other video game structures in that the game is free-to-play, but players are encouraged to purchase optional items that enhance their playing experience. 

My responsibility was to generate a report that breaks down the game's purchasing data into meaningful insights using Pandas.


### Player and Purchasing Analysis

The first queries I constructed established the total number of players, unique items, average purchase price, total number of purchases, and total revenue for Heroes of Pymoli. 

I accomplished this by importing the video game's data from a CSV file then constructed grouped data frames and applied nunique(), count(), and sum() functions as well as creating mathematical equations.  


### Gender Demographics

Once this was completed, I broke down the player userbase by the gender categores Male, Female, and Other / Non-Disclosed. 

After completing the user gender categorization, I performed a similar purchasing anaysis assessment on purchase count, average purchase price, total purchase value, and average purchase total per person by gender.  

For this section, I used Pandas loc.[] functionality, groupby(), value_counts(), mathematical equations, as well as applying formatting code to improve the analysis visually. 


### Age Demographics

Following the gender demographics, the same analysis was performed on users by age.  Bins were established for age groups and then the existing players were categorized using the age bins.


### Top Spenders

I then identified the top 5 spenders in the video game by total purchase value.  These players were then displayed in a table list. 


### Most Popular Items

The 5 most popular item add-ons by purchase count were then identified and listed in a table. 
 

### Most Profitable Items

Finally, the 5 most profitable items by total purchase value were identified and listed in a table.  

## [HereosOfPymoli.ipynb](HeroesOfPymoli/HeroesOfPymoli/HeroesOfPymoli.ipynb)


### Conclusion
Once completed, I then created a list of three observable trends based on the Heroes of Pymoli data. 

## [HereosOfPymoli_TrendAnalysis.doc](HeroesOfPymoli/HereosOfPymoli_TrendAnalysis.doc)

### Contact
Lauren Parrish
ljeanparrish@gmail.com