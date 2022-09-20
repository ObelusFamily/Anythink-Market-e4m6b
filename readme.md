# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

To get started with the project you must first set up your local environment. You can do so by following the steps below:
- Clone the repository into your local machine. Copy the git repository link and run the `git clone <repo_link>` in your terminal.
- Download and install [Docker](https://docs.docker.com/get-docker/).
- Once installed check the installation by entering `docker -v` or `docker-compose -v` in your terminal.
- Then, **run `docker-compose up` from the project root directory** to load Anythink's backend and frontend.
- If Docker is working correctly, the backend should be running and able to connect to your local database. You can test this by **pointing your browser** to [http://localhost:3000/api/ping](http://localhost:3000/api/ping).
- Now, it’s time to check the frontend and make sure it’s connected to the backend. If everything is working properly, you’ll be able to create a new user on [http://localhost:3001/register](http://localhost:3001/register).

That is all! You are all setup and ready to code! Happy Hacking!