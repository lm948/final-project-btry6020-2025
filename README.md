# final-project-btry6020-2025
Final project for BTRY6020
## README file for Lyle Massoia's BTRY6020 final project 


**THIS REPOSITORY CONTAINS** data and analysis from a study exploring how the average number of 3-point shot attempts per game in the NBA has changed over the last 10 seasons and what factors have influenced the variation.

Author: Sumitro Datta, can be found at <https://www.kaggle.com/datasets/sumitrodatta/nba-aba-baa-stats>\

### File: 

'Team Stats Per Game2.csv' - raw dataset modified from dataset above by Datta

'BTRY6020_final_project_Massoia6.Rmd' - R Markdown file containing data cleaning, exploratory analysis, & modeling

'BTRY6020_final_project_Massoia6.html' - Same as above but an HTML file

'requirements.txt' - a text file containing packages and versions used for the analysis

'README.md' - this file 

### How to use: 

  * Open `BTRY6020_final_project_Massoia6.Rmd` in R Studio 
  * Run the R Markdown file to reproduce the analysis and figures 
  * You may need to install packages found in `requirements.txt` file using `install.packages(c())`

#### Variable list: 

  * `x3pa_per_game`: the average number of 3-point shots a team attempts per game 
  * `season`: since NBA seasons span between 2 years (fall to spring), the year indicated for season is the year the season ended. For example, 2024        indicates the 2023-2024 season. 
  * `x2p_percent`: the percent of successful 2-point field goals a team makes in a game, calculated by: $\frac{\text{2-point shots made}}{\text{total 2-point shots attempted}}$
  * `x3p_percent`: the percent of successful 3-point shots a team makes in a game, calculated by: $\frac{\text{3-point shots made}}{\text{total 3-point shots attempted}}$
  * `opp_x3pa_per_game`: the average number of 3-point shots a team's opponent attempts per game 
  * `opp_blk_per_game`: the average number of shots a team's opponent blocks per game
  * `opp_drb_per_game`: the average number of defensive rebounds by a team's opponent per game
  
### License 

This project is licensed under the MIT License. See `LICENSE` file for details.
