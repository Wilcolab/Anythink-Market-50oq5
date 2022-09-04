# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Step 1: Clone the repository in to your local machine.

Step 2: Install the docker using this link https://docs.docker.com/get-docker/ on you local machine

Step 3: Then, run "docker-compose up" on termial or cmd up from the project root directory to load Anythink's backend and frontend.

Step 4: If Docker is working correctly, the backend should be running and able to connect to your local database. Let's test this by pointing your browser to
http://localhost:3000/api/ping

Step 5: To check the frontend and make sure it’s connected to the backend use this link --> you’ll be able to create a new user on http://localhost:3001/register

That's it you are ready with local setup and working on code
