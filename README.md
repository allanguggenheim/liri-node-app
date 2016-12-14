# liri-node-app

Week 10 homework - UCLA Software Development Bootcamp

Description: This is a search tool that allows you to access twitter, spotify and imdb using a single command line application that utilizes the simplicity of node.js


Pre-requisites: 

- First install nodejs from nodejs.org, unless you already have nodejs installed. 
- Optional: Copy keys.js.template to keys.js and fill out keys.js using your Twitter app information from apps.twitter.com
	- Note: All non-twitter commands will work without this


To use this application:

- Open a terminal or command prompt and cd into this directory
- Type in: node liri.js command title
	- command: use one of the commands avaliable below
	- title: the title of the song or movie you are searching for when using "spotify-this-song" or "movie-this"

Commands avaliable:

- my-tweets
- spotify-this-song
- movie-this
- do-what-it-says

Examples:

- node liri.js my-tweets
- node liri.js spotify-this-song "Taylor Swift - Love Story"
- node liri.js movie-this "The Matrix"
- node liri.js do-what-it-says
