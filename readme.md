# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

In orrder to setup your workstation please follow the steps below:

- Download Docker from [this link](https://docs.docker.com/get-docker/) and install it on your machine. 
- After installing go through the install guide giving to spin up the container by running `docker-compose up` 
- Ensure that any ports used on your system are free and you see the list of ports that will be occupied by the container in the yml file , currenlty ports 3000,3001 and 5432-5433 maybe needed. if they are used by your system already you will need to modify the yml file to some free ports. 
- check the api is working on port 3000 and the regiter link is working on port 3001 by navegating to :
  
  - http://localhost:3000/api/
  - http://localhost:3001/regiter

If all the above went well you should be setup and good to start working on the code base. 

