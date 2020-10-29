# Pokemon
Analysis of Pokemon battles born in the context of an assessment assignment.

Two datasets are used:
 1. 'pokemon.csv': a list of all Pokémon with the stats characterizing them (class, HP, attack etc.)
 2. 'combat.csv': a list containing 50k Pokémon battle pairings and their outcome

## Predicting Pokémon battles

This notebook uses the two datasets to predict a Pokémon battle based on the stats of the part-taking Pokémon:

A random forest model is trained on the combat dataset and fed with the features of the paired Pokémon.

Using the trained model it is possible to show which of a Pokémons stats are most important in combat.

## Ranking Pokémon

Pokémon are ranked by their performance in the battle outcomes available. Two methods are explored and compared.



