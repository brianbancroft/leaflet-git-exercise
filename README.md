# GIT Collaboration Exercise - With Mapping!

This is an exercise to help geography-wizards-in-training learn how to use Git in the context of mapping. 

[GeoJSON](http://geojson.org/) is a flavour of JSON (Javascript Object Notation) that is used for denoting geography on the web. 

## Setup

### Download

In your command line, type in `git clone https://github.com/brianbancroft/leaflet-git-exercise.git` and you'll be able load and edit the GeoJSON. 

### Running

Bear with me. Generally, the best practice when running a web page is to do it on a virtual server. 

This doesn't mean you have to purchase any special equipment, but there is some downloading to do. There are two really easy ways to pull this off:

- Download [Python](https://www.python.org/downloads/) and run `python -m SimpleHTTPServer 3000` in the command line while you're in the right directory, then  type in `localhost:3000` in your web browser address bar
  * (if you already have python, then you can skip the download)
*OR*
- Download [NodeJS](https://nodejs.org/en/download/),
- Download [Node Package Manager (NPM)](https://docs.npmjs.com/getting-started/installing-node),
- In the command line, type in `npm install -g http-server`; then,
- Then type in `serve` in the command line (in the proper directory) and `localhost:3000` in the address bar

You don't have to reset either server when you've modified the files in the directory. Just refresh the browser!
