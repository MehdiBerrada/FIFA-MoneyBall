# FIFA-MoneyBall
This Project is about implementing Machine Learning Algorithms to leverage some insights about Football Players.
Please look at the Jupyer Notebook for more understanding.

This Project uses the final database.
1) Building the database - 4 Steps:
- Collecting the EA Sports FIFA 19 Game Statistics of Football Players
- Web-Scraping the corresponding information on Transfermarkt website
- Web-Scraping the performances on ESPN FC website
- Web-Scraping the Instagram and Facebook followers for assessing the Marketing impact

2) Cleaning the dataset - 3 Steps:
- Completing the missing values with players of similar characteristics
- Correcting outliers for instagram followers (small players confounded with very famous influencer)
- Removing players with a small amount of data


There are 3 parts on this project:
- Understanding the factors explaining the Market Value of a Player
- Spotting the outstanding players (in terms of performances) over a season
- For a Club: decide the best replacement for a transfered player

---------------------------------------------------------------------------------------------------------------------------
More details on building the final DataSet

1- EA Sports FIFA 19 Game Data: the version of the database used is the one of the 1st October 2018. It contains:
 - Player Name
 - Club of the Player
 - League
 - Position
 - Pace
 - Shooting
 - Passing
 - Dribbling 
 - Defending
 - Physical
 
2- Transfermarkt: given the names of the player, the following information has been web-scraped:
  - Date of Birth
  - Nationality
  - Height
  - Foot
  - Day Joined the current club
  - The Day of Contract End
  
3- Instagram and Facebook: for each player, web-scraping of:
  - Number of followers on Instagram 
  - Number of likes on Facebook of the club in which the player has a contract
  
4- ESPN FC: the past 5 years performances of each player
  - GS: Games Started 
  - SB: Games Substituted
  - G: Goals Scored
  - A: Assists
  - SH: Shots
  - SG: Shots on Goal
  - FC: Fouls Committed
  - FS: Fouls Suffered
  - YC: Yellow Cards
  - RC: Red Cards
