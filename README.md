
# Automatic Valorant Observer using Machine Learning


Created by [Bailey Barber-Scargill](https://www.github.com/baileybarberscargill)

# About the Project

Observing has always been one of the most important jobs in the esports industry. However, I believe this could be improved by the use of Machine Learning to automatically decide which player the audience should be viewing.

The program would be developed using Python, and a Developer Key (provided by Riot Games). The program will check each player's location in the live match, and using an model, will determine which player is most likely to encounter activity with another.

Initiating the program would simply require the user to input the username of the POV observer account being used in-game. From there, the program handles the rest, until the program is stopped.

To test the program, a private match will be played, in a custom game with participants who have agreed to it. Only the players in-game locations will be used for processing. All other information is not required.

Testing the success of the project will be done by comparing the satisfaction levels of viewers and current professional Valorant observers.

# Developer Key - Riot Games

Riot Games provide two types of API keys:

* Development Key
* Production Key

By default, each developer account is granted a development key, but a production key must be applied for by registering a project with Riot Games. There are different rate limits and access levels for each:

**API Keys:**

* Expires after 24 hours
* 20 requests per second
* Limited to *content* and *status* endpoints

**Production Key:**

* 3000 requests every 10 seconds (300 requests per second)
* Access to *match* endpoint

Due to the nature of this project, a development key is required for match data to access the in-game locations of each player.

