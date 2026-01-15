# Basketball 🏀

This is a sport I do not understand one bit. I do however enjoy watching it. I came accross a project online that involved calculating deficits for teams within the league, and ranking their recoveries (or otherwise) from said deficits.

The task was accomplished using the following functions: 
`per_game_stats`: retrieves list of all games for specified season.
`fetch_game_pbp_sync`: retrieves play by play for a game, given its box score link.
`down_category_val`: for categorizing deficit in points
`gather_deficit`: Selecting teams with the highest number of deficits as well as most wins or losses.
`get_subset`: Gathers the list of top 10 win/loss to deficit ratios, then returns sorted df based on Ratio Rank. Total number of wins is used as a tiebreaker if ratios match.

The script contains all the relevant information, but I thought it would be fun to display a plot that includes the Toronto Raptors's performance within its top 10 (I live in Toronto). 

<img width="556" height="591" alt="image" src="https://github.com/user-attachments/assets/eee8e322-da89-477a-a80b-f6c12b0bb6aa" />


They've got the 3rd most losses while posessing a point deficit of ten or more. If for some reason anyone associated with the team stumbles into this - apologies in advance :) 
