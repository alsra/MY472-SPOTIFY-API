# MY472-Final
"This repository hosts .Rmd, .html and data files for the final project of MY472.

Analysis of Rolling Stone's 100 Greatest Artists: A Spotify Data Study:
- final_assignment.html: Analysis are mainly presented in this file. It consists of four sections:
    Introduction, Data, Analysis , Code Appendix
- final_assignment.rmd: Hosts all the code used in this assignment.
API retrival for song features are done in sequence to not to exceed API rate limit. Artists are split into two based on their apperance in Billboard Artist 100 Charts 
- features_vs_popularity.csv: The data on average of song features for artists featured in Billboard Charts. It is saved as csv as API retrival takes a considerable time.
- not_in_billboard_features.csv: The data on average of song features for artists did not featured in Billboard Charts. It is saved as csv as API retrival takes a considerable time.
  
As API does not provide information on decades, it was gathered from All Music website by web-scrapping.
- artist_decades.csv: The csv file includes artist names and the decade they debuted. 
"
