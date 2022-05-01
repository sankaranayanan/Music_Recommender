# Music_Recommender
The music recommender system recommends music of similar type using content based filtering to the user.

**what is content based filtering and why should we use it?**
Content-based filtering is a type of recommender system that attempts to guess what a user may like based on that user’s activity.Content-based filtering makes recommendations by using keywords and attributes assigned to objects in a database (e.g., items in an online marketplace) and matching them to a user profile. The user profile is created based on data derived from a user’s actions, such as purchases, ratings (likes and dislikes), downloads, items searched for on a website and/or placed in a cart, and clicks on product links.

**Data Extraction Phase**
The sample dataset was created from spotipy.The Data_Extraction.ipynb file contains the steps to extract the sample data for performing filtering.

**Data Analysis Phase**
After exploratory data analysis, correlations were made on danceability,energy,key,loudness,mode,speechiness,acousticness,instrumentalness,liveness,valence and tempo to decide the best matching similar tracks.The top 5 tracks were taken from this and recommeded to the user.
