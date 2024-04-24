# Men�s 2023 MLS Season ReadMe

## Git Hub
      Link: https://github.com/aarong9613


## Questions

* Which variables are highly correlated with goals scored?
* Which variables are highly correlated with goals conceded?
## Motivation

	Soccer is close to my heart as I have played ever since I was old enough to kick a ball. 
      The framework for this project was created from the perspective of a Team Manager approaching an analyst and asking, where do we need to improve to win more games?
       I believe my background and experience with soccer combined with my analytical abilities allow me a unique opportunity to answer such a question.

## Data Dictionary and Data Source

* Progressive Passing - Completed passes that move the ball towards the opponent's goal line at least 10 yards from its furthest point in the last six passes, or any completed pass into the penalty area. Excludes passes from the defending 40% of the pitch.
* Shot Creating Actions - The two offensive actions directly leading to a shot, such as passes, take-ons and drawing fouls. Note: A single player can receive credit for multiple actions and the shot-taker can also receive credit.
* Touches - Number of times a player touched the ball. Note: Receiving a pass, then dribbling, then sending a pass counts as one touch

Link to Data Source: https://fbref.com/en/comps/22/2023/2023-Major-League-Soccer-Stats

## Obstacles
* Multi-level indicies
* Columns that share the same name but refer to different statistics.

## Conclusion
In terms of the offense, if there are deficiencies in Touches and Progressive Passing it will have a trickle down effect Shot Creating Actions which will impact Shots on Target and ultimately Goals Scored.
Defensively, the results were less conclusive. There are non-significant correlations between defensive stats and Goals Conceded. The exceptions being Errors and Number of Players Used





