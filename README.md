# Clash Royale Mining
Project for Data Mining 2019/2020 classes.

## Task description
Records in this data set describe decks of cards used in a popular collectible card video game Clash Royale. These decks were obtained using RoyaleAPI.com service, from games which took place in January 2019.

Each record consists of five values:
* a timestamp of the game (column timestamp),
* arena ID (column arena_id – higher the arena, more skilled/experienced a player is)
* outcome of a game (column has_won, 1 – the player won, 0 the player lost)
* a player ID (column tag)
* a list of exactly eight cards in the player’s deck separated by “_” signs (column player_deck)

Your task is to analyze this data and search for interesting card usage patterns, and interactions/dependencies between cards. For example:

* please find card combos that were particularly popular in January 2019 (e.g., top 100 card sets with regard to their support, top 100 card sets of size 2, size 3, etc.),
* identify those card combos which have high win-rates (e.g., top 100 card sets with regard to win-rate and with support > 1%),
* does the card usage/popularity/effectiveness changes in time?
* does the arena level have any influence on card usage/popularity/effectiveness?
* find interesting associations between cards.

Report your discoveries in the form of R notebook (with code and all computation outcomes).

## Solution
Solution written as R Notebook is in `clash-royale.Rmd` and rendered to `clash-royale.nb.html`.
