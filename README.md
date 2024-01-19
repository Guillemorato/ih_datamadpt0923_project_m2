<p align="left"><img src="https://cdn-images-1.medium.com/max/184/1*2GDcaeYIx_bQAZLxWM4PsQ@2x.png"></p>

# __ih_datamadpt0923_project_m2__

This repository contains CSV files containing tennis statistics collected from various sources. These data are provided for the purpose of analysis and exploration in the field of tennis.




---



## **Dataset Files:**


* Many of the columns in the 'matches' files are self-explanatory, or are very similar to previous columns.

tourney_id
- a unique identifier for each tournament, such as 2020-888. The exact formats are borrowed from several different sources, so while the first four characters are always the year, the rest of the ID doesn't follow a predictable structure.

tourney_name
surface
draw_size
- number of players in the draw, often rounded up to the nearest power of 2. (For instance, a tournament with 28 players may be shown as 32.)

tourney_level
- For men: 'G' = Grand Slams, 'M' = Masters 1000s, 'A' = other tour-level events, 'C' = Challengers, 'S' = Satellites/ITFs, 'F' = Tour finals and other season-ending events, and 'D' = Davis Cup 

tourney_date
- eight digits, YYYYMMDD, usually the Monday of the tournament week.

match_num
- a match-specific identifier. Often starting from 1, sometimes counting down from 300, and sometimes arbitrary. 

winner_id
- the player_id used in this repo for the winner of the match

winner_seed
winner_entry
- 'WC' = wild card, 'Q' = qualifier, 'LL' = lucky loser, 'PR' = protected ranking, 'ITF' = ITF entry, and there are a few others that are occasionally used.

winner_name
winner_hand
- R = right, L = left, U = unknown. For ambidextrous players, this is their serving hand.
winner_ht
- height in centimeters, where available

winner_ioc
- three-character country code

winner_age
- age, in years, as of the tourney_date

loser_id
loser_seed
loser_entry
loser_name
loser_hand
loser_ht
loser_ioc
loser_age
score
best_of
- '3' or '5', indicating the the number of sets for this match

round
minutes
- match length, where available
w_ace
- winner's number of aces
w_df
- winner's number of doubles faults
w_svpt
- winner's number of serve points
w_1stIn
- winner's number of first serves made
w_1stWon
- winner's number of first-serve points won
w_2ndWon
- winner's number of second-serve points won
w_SvGms
- winner's number of serve games
w_bpSaved
- winner's number of break points saved
w_bpFaced
- winner's number of break points faced
``````
l_ace 
l_df
l_svpt
l_1stIn
l_1stWon
l_2ndWon
l_SvGms
l_bpSaved
l_bpFaced
``````
winner_rank
- winner's ATP or WTA rank, as of the tourney_date, or the most recent ranking date before the tourney_date
winner_rank_points
- number of ranking points, where available
loser_rank
loser_rank_points



---



## Usage

These CSV files are intended for use in tennis-related data analysis. You can import them into tools like pandas in Python or use them in data analysis environments like Excel or Power BI.


---


## **References:**

- [Visual Analysis Best Practices](https://github.com/ih-datapt-mad/ih_datamadpt0923_project_m2/blob/main/images/visual-analysis-guidebook.pdf)

- [Financial Times Visual Vocabulary](https://github.com/ft-interactive/chart-doctor/tree/master/visual-vocabulary)

- [Tableau](https://github.com/ih-datapt-mad/dataptmad0923_lessons/blob/main/m2/20240110_bi_tableau.md)

- [Power BI](https://github.com/ih-datapt-mad/dataptmad0923_lessons/blob/main/m2/20240113_bi_pbi.md)