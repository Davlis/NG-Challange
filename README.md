# WTH?

This repository contains lightest possibly implementation of https://github.com/Davlis/movie-db-rest-api application for `.js`, it was created for challenge. (yeah, I know that I could still optimalize things, but it will be improved in next iteration)

Please do not use this in production.

# Challenge Requirements

- Only internal dependencies
- Javascript implementation
- Max 13kB

# Stack

`http` - Server creation

`https` - Database & External Api interactions

`url` - For url parsing

`querystring` - For URL escaping

`crypto` - For ID generation

# Live version
API is hosted on [Heroku](https://ng-movie-challenge.herokuapp.com/), so you can play with it on the cloud

# Prerequisites
* Latest version of Node and NPM 
# Start

* ```npm start```

App is running by default on port `8080`.

# Documentation
API documentation was made by using Postman, you can find it in `/docs` directory

# Database

Database installation and configuration is already set, so you do not need to worry about having fully working application.

If you want to use your own database then you should provide proper entry for ```dbHost``` key in ```s``` file. 

# OMBDApi
Application uses OMBDBApi to fetch information about movies.

OMDBApi needs api key to work properly, by default api key is exposed in ```s```, so you don't need to bother about yours.

If you want to use your own ```API KEY``` then you should provide proper entry for ```apiKey``` key in ```s``` file.


# Testing
Testing is not yet supported 😢

# Environments
Environment variables are exposed on purpose - so you can play with application with minimal effort.
