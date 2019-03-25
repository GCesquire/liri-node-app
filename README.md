# LiriBot

## About

LIRI is a Language Interpretation and Recognition Interface. LIRI will be a Command Line Node App that takes in parameters and gives you back data.

## What it does

By typing the appropirate instructions into the Command Line, the user may retrieve data from a number of APIs which whill present the desired data onto the Command Line. 

### Bands In Town:

Command:

node liri.js concert-this <Insert Band OR Artist Name>

The above command will search the Bands in Town Artist Events API for an artist and render the following information about each event to the terminal:

Name of the venue
Venue location
Date of the Event (use moment to format this as "MM/DD/YYYY")


### Spotify:

node liri.js spotify-this-song <Insert Song Title>
This will show the following information about the song in your terminal/bash window
Artist(s)
The song's name
A preview link of the song from Spotify
The album that the song is from


### OMDB:

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


### Do What It Says

node liri.js do-what-it-says
Using the fs Node package, LIRI will take the text inside of random.txt and then use it to call one of LIRI's commands.
