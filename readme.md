# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

0. Clone this repo (if you haven't already).
1. Install Docker.
2. Run `docker compose up` to start the frontend, backend and database.
3. Visit http://localhost:3000/api/ping to verify backend is working.
4. Visit http://localhost:3001/register to register a user and verify the frontend is working.

