# Music-Recommendation-System-Spotify

##Description
This project is a study on the music app,Spotify. Spotify is in the top spot because of Big Data Analytics. Due to its enormous playlist and its discovery weekly suggestion. This study creates a recommender system that will recommend new musical artists to a user based on their listening history.To build our recommendation system we will be using Spark and the collaborative filtering technique.

###Why Spark?
As industries evelop and the products and services becoming more creative and customer-based, the need for machine learning algorithms to help develop personalizations, recommendations, and predictive insights becomes much more essential. Apache Spark involves graph computation, streaming, and real-time interactive query processing to solve highly complex machine learning problems.
Furthermore, Apache Spark is a fast and general-purpose cluster computing system. It is also simple, highly scalable, and effectively integrable with other tools, like R, SQL, Python, Scala, and Java.

##Datasets
The dataset for this project is publicly available song data from audioscrobbler. However, we modified the original data files so that the code will run in a reasonable time on a single machine. The reduced data files can be found here and contains only the information relevant to the top 50 most prolific users (highest artist play counts).
The original data file user_artist_data.txt contained about 141,000 unique users, and 1.6 million unique artists. About 24.2 million users’ plays of artists are recorded, along with their count.
Also note that the data set includes artist_alias.txt, which maps artist IDs that are known misspellings or variants to the canonical ID of that artist.
The artist_data.txt file then provides a map from the canonical artist ID to the name of the artist.

Youtube: https://www.youtube.com/watch?v=ZuWnT0s9fSk
