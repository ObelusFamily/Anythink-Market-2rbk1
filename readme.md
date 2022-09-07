# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including
all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file
([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull
request against `main` from a feature/bug branch and add `@vanessa-cooper` as
reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a
fresh copy of this repo. I think it's worth documenting the steps needed to
install and run the repo on a new machine?_ Run the following from the project
root directory to run all services:

```sh
docker compose up
```

You should then be able to ping the backend api by visiting
http://localhost:3000/api/ping. Next, test that the frontend and backend are
working together by creating a new user at http://localhost:3001/register.