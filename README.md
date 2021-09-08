
# URL Shortening Service

## Description
This is a URL shortening service (like [bit.ly](https://bit.ly)).

This project consists of:
1. A back-end (REST / HTTP API) server which:
    * returns a short URL when given a specified URL
    * looks up or redirects to the specified URL when given a short URL
2. Develop a simple front-end (website / application) which allows users to easily create new shortened URLs.

### Live Site
* Frontend: https://url-shortening-service.netlify.app/
* Backend: https://url-shorterning-service.herokuapp.com/

## Quick Start

1. Clone this repository and its submodules: `git clone --recursive git@github.com:huishun98/url-shortening-service.git`
<!-- To update submodules, run `git submodule update` -->
2. In the project root, run `sudo docker-compose up`.

## Features Included

- **I've got style** -- The front-end has a responsive layout and is accessible to mobile users.

- **Elephants never forget** -- Shortened URLs and data is stored in a database.

- **Push to production** -- Solution is deployed using Netlify (frontend), Heroku (backend) and AWS through MongoDB Atlas (database).

- **I ship containers** -- Application is dockerized for easy deployment and testing.

<!-- - **Tried and tested** -- Write a few unit / functional tests, or even an API canary. -->

## Tech stack and Considerations
1. Backend — Flask
2. Frontend — Vue.js
3. Database — MongoDB
    * Easy to run and test locally, compared to cloud-based databases like Firebase
    * Unlimited free cloud hosting is available for non-relational databases, unlike relational databases
