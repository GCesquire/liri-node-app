Liri

About

LIRI is a Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.

What it does

Bands In Town:
node liri.js spotify-this-song <Insert Band OR Artist Name>


Spotify:
node liri.js spotify-this-song <Insert Song Title>
This will show the following information about the song in your terminal/bash window
Artist(s)
The song's name
A preview link of the song from Spotify
The album that the song is from


OMDB:
node liri.js movie-this <Insert Movie Title>
This will output the following information to your terminal/bash window:
Title of the movie.
Year the movie came out.
IMDB Rating of the movie.
Country where the movie was produced.
Language of the movie.
Plot of the movie.
Actors in the movie.
Rotten Tomatoes Rating.
Rotten Tomatoes URL.


Do What It Says
node liri.js do-what-it-says
Using the fs Node package, LIRI will take the text inside of random.txt and then use it to call one of LIRI's commands.
