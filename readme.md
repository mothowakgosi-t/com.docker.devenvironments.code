# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Newbie first install

1. submit a pull request for the project
2. download docker and install it. make sure you're using the latest wsl 2 instance if you're on Windows.
3. run 'docker -v' to verify the install is good
4. go to the root directory of the project and run 'docker-compose up'
5. test the backend: copy and paste this url into your browser: http://localhost:3000/api/ping
6. test the frontend: copy and paste this url into your browser: http://localhost:3001/register, and create a user