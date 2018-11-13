# arcade
Projects for Data Analytics, and Predictive AI deployed in Games, ideally to scale to larger matrices and deep nets

**Project Title: **PredictiveAI Rock Paper Scissors**

The project is intended to implement basic strategy of \"playing the player, not the game"\ as a machine uses past performance to inform decisions after being fed the rules of ROCHAMBO/Rock Paper Scissors

**How to use**

Make sure you are running Python 3. I have found inconsistent and disappointing results from tries to compile online with temporary editors.

The currentcodet is configurable if the user decides that a mercurial player will have made up their preference by just two consecutive choices.

**Pseudo code for exmaple implementation**
Biological Learner | Machine Learner
------------ | -------------
throw is a winner |  calculate strategic or random throw from preference
throw is a loser | -1 from the losing choice, artificially boosting the other choicesfrom the player's history, *then* calculate strategic or random throw from preference


A person who loses is more likely to throw a different choice the next time, thus and weighting down the last choice if and only if it was defeated could alter the prediction results.



__*Thalia Rossitter*__
