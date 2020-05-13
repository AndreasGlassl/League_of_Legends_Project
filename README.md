Looking into League of Legends, database from kaggle:https://www.kaggle.com/gyejr95/league-of-legendslol-ranked-games-2020-ver1
For easy reading, champion names and item names: https://www.kaggle.com/gyejr95/league-of-legendslol-champion-and-item-2020


# 0. Overview:

The gaming industry is growing at a quick pace. Also, there is a lot of money involved, especially as the community is growing and E-Sports is getting bigger and bigger with professional players getting million dollar contracts. As there is a lot of money involved, it is also important to know whats going on. 

I will be looking into ranked games of the best players of Korea. The goal is to find out how more about the balance of the game. This is especially important to the many players playing the game as they want to have a good experience. And if they dont, they will stop playing and therefore stop spending money on the game.

The games which will be looked at are in the **Challenger/Grand Master/Master-Tier**. They are made up of approximately $0.05%$ (0.0091%/0.019%/0.028%) of all the players which are playing ranked games in Korea. (Further information: https://www.leagueofgraphs.com/rankings/rank-distribution/kr)

# 1. Read and preparing the DataFrames:


## 1.1 Champion and Item Descriptions

## 1.2 Flattening the DataFrames
There is nested lists of dictionaries in multiple columns. Therefore for easy reading, there was some functions applied to flatten those columns and then appending the meta-information of the games. (Notebook 04)

In this process, some of the columns were dropped as they did not contain valuable information for further inspections.

## 1.3 
