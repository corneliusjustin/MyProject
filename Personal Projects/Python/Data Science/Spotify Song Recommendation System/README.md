# Spotify Song Recommendation System

Hello world! In this project I've made a Spotify song recommendation system using Random Forest Classifier. First, I list 150 songs that I like on spotify, and made them into two playlists (one consist of 100 songs and the other 50 songs). Then, I search three playlists which I don't like the genre of the songs on those playlists, it is dangdut, punk rock, and k-pop genre. So now I got 3 playlists, 2 of them consist songs that I like and the other one, I don't.

I scrape those playlist using "spotipy" package, then make a class for the songs that I like with 1 and the songs that I dislike with 0, and make it into pandas dataframe. Spotipy is a pretty nice package because it will extract each of the songs features, such as danceability, energy, key, etc. So, I can do an exploratory data analysis based on the songs that I like and dislike.

Before bulding a model, I scrape a random playlist so I can make the songs on that playlist as a test set. Then lastly, I make a model as a song recommendation system on the test set.
