# Optimized 3 Point Shooting Project

## Project Overview
This NBA data science project was inspired by wanting to optimize court spacing. The NBA today is heavily reliant on 3 point shooters with 5 man units often deploying 5 players who can shoot well. We believe that the next step may be to find where players take shots from in order to maximize each players shooting strengths and minimized their weaknesses. All data is downloaded from the NBA API. Player data downloaded from the NBA API is used to generate court area specific data of players shooting abilities. In specific, the 3NG (3 net gain) metric was used in order to assess 3 point shooting. 3NG is a comprehensive 3 point shooting metric that takes into account a players shooting percentages as well as the volume at which they shoot. We believed it was important to assess the fundamental problem if a 40% shooter who shoots 2 3s a game is better or worse than a 38% shooter who shoots 8 times a game. 3NG calculated values for players are used in order to generate an optimized court spacing for any given 5 man unit.

## Project Scripts
The main script for the project is Optimal_3_Point_Spacing.ipynb. All Testing was done in files located under the Testing_Files folder.
