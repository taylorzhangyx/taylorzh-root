# taylorzh-root

## Overview
This project is a wrapper of the services of taylorzh website servers. This project will include the following parts to make the taylorzh website aviliable.

1. Nginx
1. Docker
1. Flask frontend server
1. Gin Backend server
1. MongoDb
1. Travis

## Flask Server
This server is playing the role of frontend renderer.
It'll accept the request to render the html web pages and return back the page with assets.

The page will have the ability to request and render data to the Gin backend.

## Gin Server
This is the backend server for taylorzh website. It holds all the business logic and web APIs to serve the users.

With the ability to run redis and MongoDb, this server is capable to handle reqeust from the web app.

## Travis
This project uses Travis to run CI/CD pipelines to run tests and auto deployments to AWS.
