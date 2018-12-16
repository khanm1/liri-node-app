# liri-node-app

The challenge was to use Node JS to create a LIRI bot, like iPhone's SIRI, but takes in command through Language vs Speech. LIRI is a command line node app that takes in parameters and returns data based on one of four commands:

concert-this

spotify-this-song

movie-this

do-what-it-says

Getting Started
Clone down repo.
Run command 'npm install' in Terminal or GitBash
Run command 'node liri.js' or one of the commands below.
What Each Command Does
node liri.js concert-this
    * Name of the venue
     * Venue location
     * Date of the Event (use moment to format this as "MM/DD/YYYY")

node liri.js spotify-this-song <song name>
Shows the following information about the song in terminal/bash window.

Artist(s)
The song's name
A preview link of the song from Spotify
The album that the song is from


node liri.js movie-this <movie name>
Shows the following information in terminal/bash.

       * Title of the movie.
       * Year the movie came out.
       * IMDB Rating of the movie.
       * Rotten Tomatoes Rating of the movie.
       * Country where the movie was produced.
       * Language of the movie.
       * Plot of the movie.
       * Actors in the movie.

node liri.js do-what-it-says
Takes the text from random.txt and runs the song through spotify-this-song command

Tech used
Node.js
axios NPM Package 
dotenv NPM Package 
inquirer NPM Package 
moment NPM Package 
node-spotify-api NPM Package 

Author
Mohammad Khan
