# Predicting Game Reviews
## Using scikit-learn and linear regression to find trends in board games

### Read my full write-up on [Medium.](https://medium.com/@galen.ballew/board-games-meet-machine-learning-34026870f8d5#.nkv6s5tyh)


**The Challenge:**  
Wouldn’t it be nice to know if a board game is good *before* you buy it? Let alone before you spend several hours with your friends plodding through the rule book, stumbling through the metaphorical dark. For games that already exist, [BoardGameGeek](https://boardgamegeek.com/) (BGG) serves as the light. BGG is an only forum, marketplace, and wiki for all things board game related. With a large active community and a database of over 80,000 board games, it is the best place to find a new game to play. The goal of this project was to create a model that can accurately predict game ratings.

 **The Toolkit:**
 * scikit-learn
 * AWS
 * seaborn
 * pandas
 * Web scrapers written by [Sean Beck](https://github.com/ThaWeatherman/scrapers)


**The Results:**  
Games were predicted within 0.67 "stars" out of 10, which is less than the standard deviation. However, this isn't very useful and the data is lacking meaningful features. There is an opportunity to go back and add much more insightful features in the scraping process.  
