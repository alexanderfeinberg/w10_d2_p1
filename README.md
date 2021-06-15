# Predict the order of Express middleware

In this practice, you will predict the order that Express middleware will be
invoked when making a variety of requests.

## Set up

`cd` into the __server__ folder.

`npm install` the dependencies.

Run `npm start` to start the server on `localhost` port `5000`.

## Background

Take a look at the __server/app.js__ file. This file contains the Express
application and the middlewares connected to the application.

In each of the following scenarios, predict what will be logged in the server
logs when a request is made.

## Scenario #1 `GET /`

If a client makes a request to `GET /`, what will be logged in the server logs
and in what order?

## Scenario #2 `GET /other-resource`

If a client makes a request to `GET /other-resource`, what will be logged in
the server logs and in what order?

## Scenario #3 `GET /not-found`

If a client makes a request to `GET /not-found`, what will be logged in the
server logs and in what order?