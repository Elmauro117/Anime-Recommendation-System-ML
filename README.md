# Anime-Recommendation-System-ML

A ML project for Anime Recommendation

In this project we go through all the process of Data Cleaning and Exploration to create multiple Anime Databases and see how the results vary one from the other. 

I create a ML model to Recommend Animes based on the Cosine Similarity Method.

As I said before, we pass different AnimeDB's to the model and experiment with the features.

### How it worked?
The Model does it fine, it is not impressive. But with the DB4 it does it fine. The important features were Genres and Themes, in fact features like Studios, Source and Synopsis actually ruined the recommendations. Rating, tho was useful only when recommending adult/mature stuff.

The data lacks of quality ("low quality dataset"). It does it fine by recommending based on Genres and Themes, but it could be better if we had more on those features or if the data were more specific on those features too.


### The databases
I cleaned the raw dataset to create each DB below.
AnimeDB1: This DB considers all the titles, all ratings, it has the UNKNOWN values and many UNKNOWN converted randomly as names from Genres, Themes.
AnimeDB2: Is the same as AnimeDB1 but this one changes UNKNOWN values by "" and Drops rows containing Theme, Genre & Genre2 with "" values.
AnimeDB3: Same as AnimeDB2 but dumps animes with less than 10 eps and Commercials/advertisements/musicVideos/stopMotion.
AnimeDB4: AnimeDB4 is a DB that doesnt consider < 10 episodes animes & Adult animes. In the code .py archive you can also consdier to drop Children animes.


###### Much more info inside the archives.
