

# Introduction

This repo is front-end sketch of a demonstration for a (react+redux frontend + golang API  backend) that demonstrates:
#For backend server please see this link:
https://github.com/Jogchat/jogchat_golang_backend
* Use of higher-level components to protect pages in the frontend that require authorization
* react-mdl for the design
* React router to route stuff
* Redux and redux-thunk for state management
* Multiple redux reducers using `combineReducers`
* UI handling for long running API calls
* [JWT](http://jwt.io/) signing for authenticating API calls
* Proper handling for CORS in Gorilla mux
* Setting headers with `fetch` API
* An npm `scripts` based build approach with support for watchify and gin

I set it up to server as a micro-lab for working with various authentication options.  It took me a lot of research to get all the tiny details right (especially the CORS, JWT, and react login stuff), so I thought I'd share it.

This video provides an overview of the app:

[![react+redux frontend / golang backend](video-poster.png)](https://youtu.be/yp7UqOfNTZ4)

If there is interest, I'll make another post / video with more detail on how things work.  *So, if you want to see that, star the repo!*

## To run it

First, you need a working Golang environment (1.5+)
* Clone the repo
* `npm install`
* `npm run frontend`

Open your browser to `localhost:8000/dist`

## What's Missing

I should also add this stuff

* Godeps support
* Encryption / HTTPS support for the API
* Encryption for the JWT token

Install on Ubuntu 16.04
apt-get npm
npm install
apt install nodejs-legacy

# Jogchat React+Golang server
This server will split to react and golang microservices later ip: 206.189.222.128



