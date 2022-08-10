# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- Install Docker from [here](https://docs.docker.com/get-docker)
- After installation is completed, check if Docker is running the following commands in the terminal: `docker -v` and `docker-compose -v` .
- Then run `docker-compose up` from the root of the project to start the application.
- To test if the application is working accordingly, open the given URL [http://localhost:3000/api/ping](http://localhost:3000/api/ping) in the browser.
- Finally, create a new user on [http://localhost:3001/register](http://localhost:3001/register) and you are good to go.