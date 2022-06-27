# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install docker desktop into your local machine. To verify if its installed correctly run `docker -v` and `docker-compose -v`.
2. Clone this repo into your local machine.
3. Go inside this repo and run `docker-compose up` in the project root directory from your terminal.
4. If docker is working correctly, the backend should be running and able to connect to your local database. Lets test this by clicking [http://localhost:3000/api/ping](http://localhost:3000/api/ping).
5. Now, it’s time to check the frontend and make sure it’s connected to the backend. If everything is working properly, you’ll be able to create a new user on [http://localhost:3001/register](http://localhost:3001/register).
