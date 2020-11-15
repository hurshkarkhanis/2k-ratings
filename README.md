# Predicting NBA 2K21 Ratings

Every year, the basketball world waits at the ready for the latest installment of the NBA 2K video game series to release. NBA 2K video games simulate the action on the court with impeccable detail. The two main things basketball fanatics look for in the latest 2K video game are the cover athletes, and the **2K ratings, a numerical representation of a player's skill level on the court**.

My project focuses on these 2K ratings, predicts them based on player stats, and finds which statistical categoies most influence a players rating.

## Rating Calculation

As written in [this Complex article](https://www.complex.com/sports/2017/10/how-nba-2k-determines-player-rankings), "every year, these ratings are held up to scrutiny—sometimes by the fans and critics, but most often by the players themselves." Every player believes he is worth higher than the number 2K assigns them.

Caltulating ratings is a long, complicated, and exhausting process, but generally speaking, a player's overall 2K rating is an aggregation of their ratings in certain cetagories like defending, rebounding, inside/outside scoring (among others), in addition to their archetype. For example [versatile point guard Chris Paul's](https://www.2kratings.com/chris-paul) archetype is 'All-Around 2-Way', while the [highly specialized J.J. Redick's](https://www.2kratings.com/jj-redick) archetype is "Sharpshooter".

## Gathering Data

I got my data from two sources.

I got total player statistics for the most recent 2019-2020 NBA season from [this page on basketball-reference.com](https://www.basketball-reference.com/leagues/NBA_2020_totals.html).

I webscraped 2K ratings data from HoopsHype.com. Below is a sample page that I webscraped from. 

[Kevin Love HoopsHype 2k Ratings Page](https://github.com/hurshkarkhanis/2k-ratings/blob/main/k_love_screenshot.png)

