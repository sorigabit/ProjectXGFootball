# Expected goals: What are they and what do they tell us?

An xG model uses historical information from thousands of shots with similar characteristics to estimate the likelihood of a goal on a scale between 0 and 1.

# Motivation

The term "xG" was coined in 1993 and after 20 years the xG still confuses people. This project presents some basic informations about xG and studies its behaviour in different contexts.

## Getting Started

Built using Python, Tableau, Powerpoint and other graphics editors. The repository contains a media directory and the all the data files.
```bash
You can install Python by downloading the latest version of Anaconda (https://www.anaconda.com/download)
and run the following command in the root environment: conda install python=3.6

https://www.tableau.com/

https://www.microsoft.com/en-gb/microsoft-365/powerpoint


```
## Data

|      Header        |      Definition                                                               |
|--------------------|-------------------------------------------------------------------------------|
|     season         |     The   season during which the match was played                            |
|     date           |     The   date of the match (YYYY-MM-DD)                                      |
|     league_id      |     A   unique identifier for the league this match was played in             |
|     league         |     The   name of the league this match was played in                         |
|     team1          |     The home   team's name                                                    |
|     team2          |     The   away team's name                                                    |
|     spi1           |     The   home team's overall SPI rating before the match                     |
|     spi2           |     The   away team's overall SPI rating before the match                     |
|     prob1          |     The   probability of the home team winning the match                      |
|     prob2          |     The   probability of the away team winning the match                      |
|     probtie        |     The   probability of match ending in a draw (if applicable)               |
|     proj_score1    |     The   number of goals we expected the home team to score                  |
|     proj_score2    |     The   number of goals we expected the away team to score                  |
|     importance1    |     The importance   of the match for the home team (0-100)                   |
|     importance2    |     The   importance of the match for the away team (0-100)                   |
|     score1         |     The   number of goals scored by the home team                             |
|     score2         |     The   number of goals scored by the away team                             |
|     xg1            |     The   number of expected goals created by the home team                   |
|     xg2            |     The   number of expected goals created by the away team                   |
|     nsxg1          |     The   number of non-shot expected goals created by the home team          |
|     nsxg2          |     The   number of non-shot expected goals created by the away team          |
|     adj_score1     |     The   number of goals scored by the home team, adjusted for game state    |
|     adj_score2     |     The   number of goals scored by the home team, adjusted for game state    |






## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.


## Support

For any questions or suggestions, don't hesitate to contact:
```bash
sorigabit@yahoo.com
```

## Credits:
https://depositphotos.com

www.keyt.com   			

Championship Manager 2001/02

www.pngwing.com


