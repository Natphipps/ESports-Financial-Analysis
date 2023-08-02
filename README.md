# Project1_group4

E-Sports Financial Analysis Summary
Hypothesis and Research Questions
This project focused on the financial analysis of the esports industry. Specifically we wanted to know if a player's country of origin had any impact on their overall earnings. We started our investigation by establishing our null hypothesis (H0): Player Country of origin has no bearing, positive or negative, on the amount of money a player is capable of earning in e-sports. We gathered two csv files from kaggle, and merged them into one dataset that included PlayerId, Name, Handle, CountryCode, TotalUSDPrize, Game, Genre, Continent Name, and Country Name. We explored our dataset to uncover any patterns, and trends that may answer our primary research questions: 
-Is there visual variability in the earnings each country makes?
-Is there a relationship between the genre of game and how much a country earns?
-Do certain video games have an impact on total earning?
-Does the number of players in each country have an impact on total earning?
-What is the relationship between country and total earnings?

Data Cleaning
The first step in our analysis was to clean the dataset. We addressed missing values, removed duplicates, and ensured data consistency to maintain data integrity throughout the investigation.

-Do certain video games have an impact on total earning?
 Our team started by analyzing the total earnings of each game from our dataset. The data was sliced to compare all 10 games (Dota 2, CS:GO, Fortnite, League of Legends, Starcraft 2, Hearthstone, PUBG, Overwatch, Heroes of the Storm, and Arena of Valor). To aid in visualizing this data, we created a bar chart which shows that Dota2 generated the highest total earnings compared to the other 9 games. 

-Is there visual variability in the earnings each country makes?
 Our next step was to explore  the total esports earnings in each country. Our bar chart (Country Earnings by Total USD Prize) revealed that China, Korea, and the U.S had the highest total earnings compared to the other countries. This could mean that these countries have more esports players, or the players in these countries are dominant in the industry. However, more detailed investigation would be needed to uncover causation.


-Is there a relationship between the genre of game and how much a country earns?
 To understand the relationship between game genres and country earnings, we examined the total earnings for each genre (Multiplayer Online Battle Arena, First-Person Shooter, Strategy, and Collectible Card Games). The bar chart (Genre Earnings by Total USD Prize) displays the differences in total earnings. We also merged the data to see each country, and how much each genre made within that country. To see if there was a correlation between genre and earnings an ANOVA test was run. The p-Value = 0.002758 which tells us that the observed difference was not due to random chance. A stacked bar chart was also used for the top 5 highest earning countries so we could visualize the range of earnings each genres generated .

-Average Total Prize
 Next we wanted to look at the averages of each country's earnings. We calculated the average earnings for each country, and our output yielded a different outcome from the total earnings analysis. Our bar chart revealed that Lebanon had the highest average in earnings. This could indicate that while the total earnings for Lebanon were comparatively smaller than other countries, the average earnings each player makes is greater. We also created a scatter plot to showcase this data. For further analysis, we decided to calculate the quartiles of this data and find any outliers. The analysis displayed 4 potential outliers (Lebanon, Pakistan, Jordan, and Estonia) which were the countries with the 4 highest average earnings. 


-Does the number of players in each country have an impact on total earning?
 To determine if there was a relationship between the number of players in each country, and total earnings, we filtered the data to only show countries that had a player count between 10 and 100. The bar chart created from this data, displays the amount of players in each country. We also created a histogram to showcase the number of players in each country, and the TotalUSDPrize. Surprisingly, countries with smaller player counts generated the highest earnings. This could mean that those players are dominant in the industry, or they frequently compete in esports. Further analysis would have to be conducted to explore the details of this relationship.

-What is the relationship between country and total earnings?
 To test the null hypothesis we needed to explore the relationship between the country and the total earnings. We created a box plot to show the distribution of player earnings in each country. From this data we ran an ANOVA test to see if the player's country of origin had an impact on the Total USD Prize. Our p-value came out to 0.001506 which lets us reject our null hypothesis. The differences between country of origin and Total USD Prize was not due to chance.

-Conclusion
 Based on our analysis, it appears that a player's country of origin does indeed have an impact on their earnings in the esports industry. Additionally, variables such as game genre, and player count also play significant roles in determining total earnings. Further research should be conducted in the future to analyze what other variables contribute to such high earnings. 
