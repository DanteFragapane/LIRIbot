# LIRI Bot

A **L**anguage-**I**nterpretation and **R**ecognition **I**nterface command line bot made for class.

## Purpose of the App

This app was made to demonstrate my knowledge of interpretting and using command line arguments.

## Overview

This simple command line bot was made to demonstrate how command line arguments are used in code.

## Instructions

How to run the app:

1. Open command prompt in the root directory and install all node modules using the command ``npm i``
1. Create a file named ``.env`` and inside, paste and modify: ```SPOTIFY_ID= {spotify_ID}
SPOTIFY_SECRET= {spotify_secret}```
1. Type in ``node liri.js {command name}``
   * Working commands are: 
      * ``concert-this {artist/band name}``: gets the artist/band venues
      * ``spotify-this-song {song name}``: searches spotify for the given song
      * ``movie-this {movie name}``: gets data about the given movie
      
      * ``do-what-it-says``: takes information from the file ``random.txt`` in the format ``{command},"{parameter}"``

## Screenshots


## Technologies

* Builtin command line parser
* ``dotenv`` used for handling the environment variables defined in the ``.env`` file

## My role in the app development

Unforunately, my role was limited, as was everyone else's in the class. My role was to comment out the code, and add in error handling for the ``fs.readFile`` function
