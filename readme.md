# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Install & run repo

 1. Download docker + verify docker is ready by running the following commands in your terminal: `docker -v` and `docker-compose -v`.
 2. Then, **run `docker-compose up` from the project root directory** to load Anythink's backend and frontend.
 3. Just make sure that you **run all scripts in the next quests on one of the containers** created by `docker-compose up`. Also, **you can use `docker exec` to run commands** on a running container.