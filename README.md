# Udacity Frontend Developer Nanodegree - Project 5 - Restaurant Review !!
---

## Project Overview: 

This project is about converting an existing static web app that lacks accessibility into fully responsive, mobile ready, offline first and accessible app.

It uses MapBox API for rendering maps, service workers for offline caching and accessibility tags for screen readers.



### How to run it locally

1. First add the file called `mapboxtoken.js` inside your `js` folder. put this line in the file.
`let mapBoxToken = "<Your MapBox API Key>";`
2. Make sure that this file is included in both index.html and restaurant.html

3. Now, go to the project folder from command prmpt.
In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.

    * In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.
   * Note -  For Windows systems, Python 3.x is installed as `python` by default. To start a Python 3.x server, you can simply enter `python -m http.server 8000`.
2. With your server running, visit the site: `http://localhost:8000`

## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information.

### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future-proofing JavaScript code. 
