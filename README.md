# Requirements

Make sure that you have the following installed:

- [node](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-18-04)
- npm
- [MongoDB](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/) and start the mongodb service with `sudo service mongod start`

## Navigate to the Client Folder

 `cd client`

## Run the folllowing command to install the dependencies

 `npm install`

## Run the folllowing to start the app

 `npm start`

## Open a new terminal and run the same commands in the backend folder

 `cd ../backend`

 `npm install`

 `npm start`

### Go ahead and add a product (note that the price field only takes a numeric input)

## Docker images

- The docker images generated from this project can be found here: [Docker](https://hub.docker.com/repositories/mvictorn)

## How to run the docker images

- Clone the repo
- Navigate to the root folder
- Run `docker-compose up --build`
- Open a new terminal and run `docker ps` to see the running containers
- Open your browser and navigate to `localhost:3000` to view the frontend
