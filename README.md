# Capstone_GameplayFeatures
Capstone Project Videogame Gameplay Features

The question for my Capstone is as followed: 

What combinations of activities in the game Palia leads to the Best Long Term retention?

`

To accomplish this goal I will be using the large amount of data that our game tracks through it's robust telemetry system which includes:

What activities a player participated in and how long it took them to complete the activity. 

When they login in or out.

What resources they collected while doing the activities. 

Whom they did the activities with.

Did they build any friendships with the in game Non Player Characters.

How long they played that session and day.

What they bought in the premium shop.

If they spoke to another player or not.

Are they in a community/guild or not.

Do they have any friends in the game.

Did they use the party feature and how many times and with how many people.

`

The techniques I will be applying are as followed. 

This data will be have to be fed into a ML pipeline which will feature numerous different types of feature enginering such as: 
OneHotEncoder, StandardScaler, Polynomial Features, Dimensionality Reduction,OrdinalEncoder,Normalizing and numerous different models. I will have to figure out what the best type of model to use is going to be. I plan on starting with Logistic Regression, Decision Trees, KNN and SVM running then through a training gym once I get all the features enginnered. 

The End Result

The end result will likely be a decision tree that will show the primary drivers of retention based on the fitted model and the data that is given to it. The tree will explicitly rank the activities telling us which ones actively keeps players coming back.

Why is this question important?

This question is important in Massively Multiplayer Online Video Games such as Palia because there are numerous activities available to the player at one time. It makes logical sense that some activities that retain players are better than others. Finding out what retains players can give us a much better understanding of what type of content to create in the future. We as a company should not continue to work on features that doesn't help retain players at a decent rate. A decision tree will be able to answer these questions and help us move forward.
