# Steampowered_Data

## Exploratory Data Analysis of Steam Data (Top 100 Games)

## Overview
This Data is from the most popular pc gaming website called 'https://store.steampowered.com' you can purchase copy of a game, trade in-game items, review a game, play miltiplayer-games with friends and many other things.

## Aim of this EDA
In this Exploratory Data Analysis is to find few question about the taste, likings of consumer aobut games thoughout the years. 
Following questions has been answered in this analysis :

### Top 10 games according to current players and peak players today.
- Counter-strike: Global offensive is the most poplular game.
![1](https://user-images.githubusercontent.com/90683408/145413443-a73adc4f-9f80-45c1-9930-65ce978ee786.png)
### Top 10 games according to the day data got acquired.
- Here also, 'Counter-strike: Global offensive' is the most poplular game.
![2](https://user-images.githubusercontent.com/90683408/145413830-b9530d79-c64b-4405-a86b-ad9803731a05.png)
### Which game is the oldest in this data.
-'Counter-Strke' turn out to be the oldest game with release date of 2000-11-01
### Which game is the newest in this data.
- 'Football Manager 2022' is the latest release in this dataset with release date of 2021-11-09
### Most Reviewed games.
- These are the top 10 reviewed games.
- ![3](https://user-images.githubusercontent.com/90683408/145415117-50d5523a-993b-4e63-9150-7da8fb16076f.png)
![4](https://user-images.githubusercontent.com/90683408/145415215-4746ee3d-9ac9-46e1-9ff1-150041297dc2.png)
### Least Reviewed games.
- These are the least 10 reviewed games.
- ![5](https://user-images.githubusercontent.com/90683408/145423532-d6c218c3-9f5a-4201-9a54-b6decb34c1a9.png)
![6](https://user-images.githubusercontent.com/90683408/145423563-82bf8ed9-97cd-4957-b692-132936fccce6.png)
 ### Average players.
 - ![7](https://user-images.githubusercontent.com/90683408/145426476-694da869-8686-4656-9528-8554d56ed62c.png)
- By looking at the above image we can see there is a lot of difference between mean(39954) and the median(18012).
- Lets checkout boxplot and historam.
- ![8](https://user-images.githubusercontent.com/90683408/145426596-bcd73ad9-012d-4fc7-a358-2981dd327438.png)
![9](https://user-images.githubusercontent.com/90683408/145426604-62d310ff-dd8c-4008-b718-2065156c3ffb.png)
- From the above images you can see data is highly skewed towards right side. Therefore **the Average player more likely to be around median which is 18012.**
### Average number of players on the day data is acquired.
- ![10](https://user-images.githubusercontent.com/90683408/145427847-022fe0da-9513-4a3e-8b74-47702b54fec3.png)
- ![11](https://user-images.githubusercontent.com/90683408/145427878-4142e3ee-436c-4b1a-81ea-e4efe026fb80.png)
![12](https://user-images.githubusercontent.com/90683408/145427889-175ac8d2-1294-412f-ac97-424fa52f4037.png)
- like average palyers same result with average players on which the data got acquired, graph is highly skewed towards right therefore **the Average number of player is mode which is 24493.**
### Proportion of reviews by the players.
![13](https://user-images.githubusercontent.com/90683408/145428802-4b445e32-781d-4f8c-9471-3e4d7178da53.png)
- Exactly 59% of people choose 'Very positive'

### In which year highest number of game released?
-![15](https://user-images.githubusercontent.com/90683408/145429834-beb6b151-7e3b-4ccc-9432-cd7792ddd1f2.png)
![14](https://user-images.githubusercontent.com/90683408/145429592-966d8ff7-b026-45cf-b24e-ece3e93c6626.png)
- 18 games were released in year of 2020 which is the highest.

### As the time passes doest the current players increased?
![16](https://user-images.githubusercontent.com/90683408/145430700-c2483187-7cd7-4cd6-839f-ded2e4306366.png)
- After analysing the data, there is no evidance that there is increase in the current players as the time goes, Though we can see there is sudden huge rise of current players in '2012-08-21' for the game 'Counter-Strike: Global Offensive' with the maximum current player of 736875, another surge of player after this is for the game called 'Dota 2' with the maximum current players of '649690' on the date of '2013-07-09'.

### Those games got more Current players playing also tends to get more reviews?
![17](https://user-images.githubusercontent.com/90683408/145431031-03009ca4-e480-4b13-81d1-ae2b075d0e45.png)
![18](https://user-images.githubusercontent.com/90683408/145431052-adaa6660-da47-407d-b4e9-1740e1fa7335.png)
- We got 0.8479386124540209 of positive corelation also in the scatter plot there is a high positive corelation between between 'Total reviews' and 'Current players'.Therefore, the answer of the question is **Yes games who got more Current players playing also tends to get more reviews.**

### Those game got more total reviews also tends to get better review?
![19](https://user-images.githubusercontent.com/90683408/145431680-5cf7f93b-68dc-4cf1-babf-fb0918b66fbe.png)
![20](https://user-images.githubusercontent.com/90683408/145431690-92354cca-6168-4c6e-a3d9-6e71eea2c922.png)
- By looking at the above box plot and histograms it seems all reviews almost same therefore the total reviews and review summary are not associated.

### Data Source
[Kaggle](https://www.kaggle.com/angadchau/steam-top-100-gamesnov-2021)
