# Surreal Estate API

A simple Real Estate Marketplace API to showcase how to build post and fetch data with React.

## Run locally

- To run locally, clone this repo and install all dependencies `npm i`
- Create a `.env` file in the project root.
- Paste a MongoDb connection string in there, you can create an instance on Mlab/Atlas for free.
- E.g: `DATABASE_CONN=mongodb://username:password@ds117960.mlab.com:17960/surreal-estate`

## Run in container

- You can run a pre-configured version of the app and the required database with docker-compose. You can read how to install docker-compose [here](https://docs.docker.com/compose/install/)
- Once docker-comopse is installed, you can start the app and database by running `docker-compose up` from the root of this project
- Alternately, you can run the app in detached mode by runninng 'docker-compose up -d' from the root of this project
- You will not see any output from the containers in detached mode. You can check their logs with `docker-compose logs SERVICE_NAME`
- You can stop the containers with `docker-compose stop` in the root of this project
- You can start them again with `docker-compose start`
- You can tear down all the containers with `docker-compose down`, or `ctrl c` in ther terminal window, if not running in detached mode