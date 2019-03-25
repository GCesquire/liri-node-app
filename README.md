# LiriBot

## About

LIRI is a Language Interpretation and Recognition Interface. LIRI will be a Command Line Node App that takes in parameters and gives you back data.

## What it does

By typing the appropirate instructions into the Command Line, the user may retrieve data from a number of APIs which whill present the desired data onto the Command Line. 

### Bands In Town:

Command: node liri.js concert-this (Insert Band OR Artist Name)

![](Bands.gif)

The above command will search the Bands in Town Artist Events API for an artist and render the following information about each event to the terminal:

Name Of The Venue:

Venue Location:

Date Of The Event:


### Spotify:

Command: node liri.js spotify-this-song (Insert Song Title)

![](Spotify.gif)

The above command will search the Spotify API and will output the following information about the song in your terminal:

Artist:

Song Name:

A Preview Link Of The Song From Spotify:

The Album That The Song Is From:


### OMDB:

Command: node liri.js movie-this (Insert Movie Title)

![](OMDB.gif)

The above command will search the OMDB API will and will output the following information to your terminal:

Title Of The Movie:

Year The Movie Came Out:

IMDB Rating Of The Movie:

Rotten Tomatoes Rating Of The Movie:

Country Where The Movie Was Produced:

Language Of The Movie:

Plot Of The Movie:

Actors In The Movie:

### Do What It Says

Command: node liri.js do-what-it-says (Enter Your Desired Text)

![](Random.gif)

Using the fs Node package, LIRI will take the text inside of random.txt and then use it to call one of LIRI's commands.
