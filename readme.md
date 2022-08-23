# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Docker

- [Install Docker](https://docs.docker.com/get-docker/).

- Verify the installation was successful by executing `docker -v` and `docker-compose -v` in the terminal.

### Run the containers

From the root directory run:

```sh
docker-compose up
```

### Test the connections

- Go to http://localhost:3000/api/ping to check if the backend can connect to your local DB.

- If it errors out saying that migrations are pending click the "Run Pending Migrations" button.

- Go to http://localhost:3001/register and create a new user.

If everything was successful you are good to go!
