# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- Install [Docker](https://docs.docker.com/get-docker/) for your OS.
- Run the docker app on your machine.
- Once docker is running, from this project's root directory, run `docker-compose up`
- Once the docker containers are humming check that you're able to access the front end by opening `http://localhost:3000/api/ping` in your browser
- Test your backend by opening `http://localhost:3001/register` in the browser and testing the registration process.
