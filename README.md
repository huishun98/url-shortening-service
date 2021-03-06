
# URL Shortening Service

## Description
This is a URL shortening service (like [bit.ly](https://bit.ly)).

This project consists of:
1. A back-end (REST / HTTP API) server which:
    * returns a short URL when given a specified URL
    * looks up or redirects to the specified URL when given a short URL
2. A simple front-end (website / application) which allows users to easily create new shortened URLs.

### Live Site
* Frontend: https://url-shortening-service.netlify.app/
* Backend: https://url-shorterning-service.herokuapp.com/

## Quick Start (using Docker)

1. Clone this repository and its submodules: `git clone --recursive git@github.com:huishun98/url-shortening-service.git`
<!-- To update submodules, run `git submodule update --remote --merge` -->
2. In the project root, run `sudo docker-compose up`

## Features Included

- **I've got style** -- The front-end has a responsive layout and is accessible to mobile users.

- **Elephants never forget** -- Shortened URLs and data is stored in a database.

- **Push to production** -- Solution is deployed using Netlify (frontend), Heroku (backend) and AWS through MongoDB Atlas (database).

- **I ship containers** -- Application is dockerized for easy deployment and testing.

## Tech stack and Considerations
1. Backend — Flask
2. Frontend — Vue.js
3. Database — MongoDB
    * Easy to run and test locally, compared to cloud-based databases like Firebase
    * Unlimited free cloud hosting is available for non-relational databases but not relational databases
