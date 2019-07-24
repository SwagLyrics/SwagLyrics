<h1 align="center">
	<img src="https://github.com/SwagLyrics/SwagLyrics/blob/master/assets/swaglyrics_transparent.png?raw=true" alt="SwagLyrics" height=200 width=200 align="middle">
	SwagLyrics
</h1>

SwagLyrics contains a set of packages and libraries written in Python to dramatically enhance the music listening 
experience on desktop. The support libraries and utilities have also been made open source to allow for an extensible 
framework.

This repository is meant for centralized issues as well as enhancement proposals and to house the [media assets](/assets/) associated with the Project.

# Repositories

## SwagLyrics for Spotify
[SwagLyrics for Spotify](https://github.com/SwagLyrics/SwagLyrics-For-Spotify) fetches the currently playing song from 
Spotify on Windows, Linux and macOS and displays the lyrics in the command-line or in a browser tab. Refreshes 
automatically when song changes. **Very** fast.
## SwSpotify
[SwSpotify](https://github.com/SwagLyrics/SwSpotify) is a python library that returns the currently playing song and 
artist from Spotify pan OS (Windows, Linux, macOS) without using the Spotify API. That allows it to be very fast and can
 be used 
independently from SwagLyrics.
## swaglyrics-backend
The [swaglyrics-backend](https://github.com/SwagLyrics/swaglyrics-backend) is a Flask application that manages and 
sanitizes issues on the SwagLyrics for Spotify repo as well as handles the error mitigation of unsupported songs.
