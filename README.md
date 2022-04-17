# Special_project_recommendation_system

This is a demo version of a recommendation system that predicts the best game for the user.

In my approach, I used the KNN Algorithm because I believed that it was the most capable of predicting the right results in the current dataset where each user have rated very few games (the pivoted dataframe used was mostly empty before imputing the data). I also changed the typical similarity metric 'minkowski' to the 'cosine' metric which is the best fit for recommendation systems as it can find other users who have the same preferences with the same priority (not only similar tastes, but also similar preferences among these tastes), the code in this repo required input of the ID number for the target user and outputs the ideal recommendation for this user, the code cells are also closely related and need to be ran in order (I couldn't fix a better version on such short notice).
