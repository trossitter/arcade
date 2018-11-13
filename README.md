## arcade
Projects for Data Analytics, and Predictive AI deployed in Games, ideally to scale to larger matrices and deep nets

# **Project Title**: **Predictive AI Rock Paper Scissors**

The project is intended to implement basic strategy of \"playing the player, not the game" as a machine uses past performance to inform decisions after being fed the rules of Rock Paper Scissors

## **How to use**

Make sure you are running Python 3. I have found inconsistent and disappointing results from tries to compile online with temporary editors.

The current code is configurable. The history that decides preference is hard-coded to 3. If the user decides that a mercurial player will have made up their preference by just two consecutive choices, change the max. If more nuanced strategies of rock paper scissors are desired, the framework is also flexible to more information

## **Pseudo code for example implementation**
Biological Learner | Machine Learner
------------ | -------------
throw is a winner |  Calculate strategic or random throw from player preference
throw is a loser | -1 from the losing choice, artificially boosting the other choicesfrom the player's history, *then* calculate strategic or random throw from player preference


A person who loses is more likely to throw a different choice the next time, thus ignoring (score of 0) or weighting down (score of -1) the last choice if and only if the throw was defeated.


__*Thalia Rossitter*__
