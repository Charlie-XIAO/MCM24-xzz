# The Mathematical Contest in Modeling (MCM'24)

Team 2410132 | Problem C

## Problem 1

### Statement

Develop a model that captures the flow of play as points occur and apply it to one or more of the matches. Your model should identify which player is performing better at a given time in the match, as well as how much better they are performing. Provide a visualization based on your model to depict the match flow. *Note: in tennis, the player serving has a much higher probability of winning the point/game. You may wish to factor this into your model in some way.*

### Solutions

See [`q1.ipynb`](./q1.ipynb).

## Problem 2

### Statement

A tennis coach is skeptical that "momentum" plays any role in the match. Instead, he postulates that swings in play and runs of success by one player are random. Use your model/metric to assess this claim.

### Solutions

See [`q2.ipynb`](./q2.ipynb).

## Problem 3

### Statement

Coaches would love to know if there are indicators that can help determine when the flow of play is about to change from favoring one player to the other.

- Using the data provided for at least one match, develop a model that predicts 
these swings in the match. What factors seem most related (if any)?

- Given the differential in past match “momentum” swings how do you advise a 
player going into a new match against a different player? 

### Solutions

See [`q3-1.ipynb`](./q3-1.ipynb) mainly for definition of momentum and comparison plots. See [`q3-2.ipynb`](./q3-2.ipynb) for the prediction model on the whole dataset. See [`q3-3.ipynb`](./q3-3.ipynb) for the prediction model for a particular player.

## Problem 4

### Statement

Test the model you developed on one or more of the other matches. How well do you predict the swings in the match? If the model performs poorly at times, can you identify any factors that might need to be included in future models? How generalizable is your model to other matches (such as Women’s matches), tournaments, court surfaces, and other sports such as table tennis.

### Solutions

See [`q4-1.ipynb`](./q4-1.ipynb) for predicting [`wimbledon_ladies.csv`](./wimbledon_ladies.csv). See [`q4-2.ipynb`](./q4-2.ipynb) for predicting [`hard_surface_court.csv`](./hard_surface_court.csv).
