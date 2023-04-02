![spotify_logo](https://storage.googleapis.com/pr-newsroom-wp/1/2018/11/Spotify_Logo_RGB_Green.png)

# Song Recommender
## Description

In this project, I build a music recommender.


## Project approach

### 1. Web Scraping: Create a list of top_100_songs and make a simple recommender

From [Popvortex](www.popvortex.com), I scraped top 100 playlist and builded simple recommender. If the input song exists in top 100 playlist, it recommends a random song from the playlist.

### 2. API wrappers: Create a spotify playlist with appx 5000 songs

I found random playlists from different genre-time. Then I pulled the artist names from those lists. Then I choose 10 song from each artist and built my playlist.

### 3. Unsupervised Learning: K-means clustering

I clustered my playlist using silhouette score and elbow method.

### 4. Song recommender: 
If the input song is in top_100_songs list, it will recommend random song from the list. If it is not, it will recommend a song from the same cluster from spotify playlist


## Requirements

Please install the following libraries:\
*pandas*\
*numpy*\
*BeautifulSoup*\
*spotipy*\
*json*\
*sklearn*\
*matplotlib*


## Instructions to run the code

### Spotify for Developers:

You need to sign up to [Spotify for Developers](https://developer.spotify.com/) and get your user credentials 

### secrets.txt:

Paste your cliendid and clientsecret to this file. (you will use this at 17th cell, remove the # and run the cell)


Asli Veenstra- [@aslivns](https://github.com/aslivns/)
