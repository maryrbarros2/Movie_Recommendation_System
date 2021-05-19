Movie recommendation System

Recommend items to users based on information taken from the user.
Content-Based Filtering and Collaborative Filtering.

@author: Mariana R.Barros

==========================================================
MovieLens Dataset. 

It consists of 105339 ratings applied over 10329 movies.
Files: movies.csv and ratings.csv.
https://drive.google.com/file/d/1Dn1BZD3YxgBQJSIjbfNnmCFlDW2jdQGD/view

==========================================================

Content-Based or Item-Item recommendation systems. 
Attempts to figure out what a user's favorite aspects of an item is, and then recommends items that present those aspects. In our case, we're going to try to figure out the input's favorite genres from the movies and ratings given.



Collaborative Filtering ( or  User-User Filtering) 
Uses other users to recommend items to the input user. 
It attempts to find users that have similar preferences and opinions as the input and then recommends items that they have liked to the input. 
There are several methods of finding similar users . Here is going to be based on the Pearson Correlation Function.


The process for creating a User Based recommendation system is as follows:
	•	Select a user with the movies the user has watched
	•	Based on his rating to movies, find the top X neighbors
	•	Get the watched movie record of the user for each neighbor.
	•	Calculate a similarity score using some formula
	•	Recommend the items with the highest score
