# Stack

0 depedencies

# WTH?

This repository contains lightest possibly implementation of https://github.com/Davlis/movie-db-rest-api application.

Please do not use this in production.

# Live version
API is hosted on [Heroku](https://movie-db-rest-api.herokuapp.com/), so you can play with it on the cloud

# Prerequisites
* Latest version of Node and NPM 
# Start

* ```npm start```

App is running by default on port `8080`.

# Documentation
API documentation was made by using Postman, you can find it in `/docs` directory

# Database

You don't need to have any database installed on your device if you are environments from ```s``` file

If you want to use your own database then you should provide proper entry for ```dbHost``` key in ```s``` file. 

# OMBDApi
Application uses OMBDBApi to fetch information about movies.

OMDBApi needs api key to work properly, by default api key is exposed in ```s```, so you don't need to bother about yours.

If you want to use your own ```API KEY``` then you should provide proper entry for ```apiKey``` key in ```s``` file.


# Testing
Testing is not yet supported 😢

# Environments
Eenviroment variables are exposed on purpose - so you can play with application with minimal effort.
