# EECS 731 Project 1: Jimmy Wrangler, Data Explorer

## Data Sets
- **Players.csv**: NBA Player Information
- **shot_logs.csv**: Statistics of each shot in the 2014-2015 NBA season

## Merge to Add Value
shot_logs.csv has lots of information about the shot (made/missed, distance, etc.), but only states the shooter and the closest defender. I will merge in information from Players.csv to provide more information on the shooter.

## Discoveries (seen in Jupyter Notebook)
1. A heavier shooter tends to have the ball for less time, dribble less before shooting, and shoot from slightly closer in.
2. A taller shooter also seems to have the ball for less time and take fewer dribbles, but the shot distance does not seem to be correlated.
3. Height/weight does not correlate with shot clock.

## Conclusions
Coaches could use this data to predict when players of certain height will shoot the ball, how willing they are to shoot from long range, and how many dribbles the player will likely take before shooting. This could be used to create baseline defensive strategies for coaches who do not have scouting information on particular players.

Here are some possible strategies:
- Have defenders double-team other players if they know that the person they are guarding is unlikely to shoot a long range shot
- Force taller players into situations where they have to dribble the ball, since they do not do it as often
- Quickly bring in extra defenders on taller players, since they are more likely to shoot quickly
