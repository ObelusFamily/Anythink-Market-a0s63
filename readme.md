# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

* Install Docker following the directions [here](https://docs.docker.com/desktop/install)

* Verify that Docker & Docker-Compose work properly by running the commands listed below. Both should return a version number.
  * `docker -v`
  * `docker-compose -v`

* Spin up the front and backend by running `docker-compose up`. No need for the `-d` flag to detach the output, as you want to be able to see if the next step works properly.

* Once your containers are up and running, you are ready to test your backend and frontend.

* For the backend, navigate to the following link in your browser: `http://localhost:3000/api/ping`
  * This should take you to an API response with "Pong" in the output. Your backend is all set!

* For the frontend, navigate the following link in your browser: `http://localhost:3001/register`
  * Try registering a new user. If this works, you're all set!