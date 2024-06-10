# GeoGridSolver
[GeoGrid](https://www.geogridgame.com/) is a daily trivia game made to put your geography knowledge to the test!

### How to Play
Guess a country for each box in the board that matches the criteria specified by the box's row and column categories.

Each box on any given board has anywhere from 5 to 30 unique answers.

### Rules
Players have 10 guesses to fill out the grid, but can enable infinite mode for unlimited.

A country can only be guessed once per game board.

### Objective
Complete the board by filling all 9 boxes with a country that matches the criteria for the intersection of categories.

Finish with the lowest score possible.

### Scoring
The score is calculated by the sum of the rarities of each box on the board.

Empty cells are scored as 100.

The rarer the guess, the lower the score.

The lower the score, the better.

![GeoGrid Board](GeoGridBoard.png)
*GeoGrid Board in June 10th*

### How to use the solver

Clone this repository:

``git clone https://github.com/HladczukLe/GeoGridSolver.git/``

Verify if .csv path is correct. 

Open the game and change the categories into the code, then you choose a country to guess.

### Categories in database
All categories (columns) in world_data.csv[^1] in order of appearance:

-  Country
-  Region
-  Population Country
-  Capital
-  Population Capital
-  HDI
-  Area (km2)
-  Population Density
-  GDP per capita
-  Olympic Medals
-  Former USSR     
-  Flag with Coat of Arms     
-  Flag with Animal            
-  Coastline on the Mediterranean
-  Hosted Olympics
-  Hosted Men's FIFA World Cup
-  Played in Men's FIFA World Cup
-  Commonwealth Member
-  Never Won an Olympic Medal
-  Coastal Distance[^2].
-  Island Nation
-  Star in Flag 
-  Won Men's FIFA World Cup
-  EU Member
-  Flag with Only Red, White, and Blue 
-  Drives on the Left
-  50+ Skyscrapers
-  Top 20 Obesity Rate
-  Alcohol Prohibition
-  Top 20 Alcohol Consumption
-  Top 20 Chocolate Consumption
-  Nuclear Weapons
-  Top 20 Tourist Arrivals

### Result
That was my game board in June 10th:

![GeoGrid Board Solved](GeoGridBoardSolved.png)
*GeoGrid board solved*

This code does not choose the best country to guess, it just lists all countries in the chosen categories.

[^1]: There are some categories unavailable in database (example: Flag with color, Borders countries)

[^2]: Some countries "Landlocked" are wrong, pay attention.