# erh2722_assignment7
## Repository for Assignment 7: Data Curation and Analysis
### Goal:
The goal of this project was to find trends or influencing factors of NBA scoring leaders by extracting and analyzing data.
### Source Data:
https://en.wikipedia.org/wiki/List_of_National_Basketball_Association_annual_scoring_leaders
### License:
MIT License
### API Documentation:
BeautifulSoup: https://www.crummy.com/software/BeautifulSoup/bs4/doc/

InteractiveShell: https://www.php.net/docs.php

matplotlib: https://matplotlib.org/stable/index.html

NumPy: https://numpy.org/ 

pandas: https://pandas.pydata.org/docs/

Requests: https://requests.readthedocs.io/en/latest/

SciPy: https://docs.scipy.org/doc/
### Data Type and Description:
Season:
  
  -string
  
  -The NBA season, comprised of two years
   ex. 2001-02

Player:
  
  -string
  
  -The name of the player that was the scoring leader in that season
  
  -Asterisks indicate multiple scoring titles
  
  -Numbers in parenthesis indicated the player's title number of scoring titles

Age:
  
  -integer
  
  -How old the player was when they were the scoring leader

Position:
  
  -string
  
  -The basketball position played by the scoring leader

Team:
  
  -string
  
  -All teams that the scoring leader has played for

Games Played:
  
  -integer
  
  -The number of games played by the scoring leader in that season.

Field Goals Made:
  
  -integer
  
  -The number of shots made by the scoring leader in that season

3-Point Field Goals Made:
  
  -integer
  
  -The number of 3 point shots made by the scoring leader in that          season

Free Throws Made:
  
  -integer
  
  -The number of free throw shots made by the scoring leader in that season

Total Points:
  
  -integer
  
  -The total points scored by the scoring leader in that season

Points Per Game:
  
  -decimal
  
  -The points per game averaged by the scoring leader in that season
### Issues and Notes:
-3-Point field goals did not exist, and therefore were not recorded, before the 1979-80 season

-Some noise remains in the "Player" column

-no tangible biases
### data.world link:
https://data.world/ethanhowat/nba-scoring-leaders
