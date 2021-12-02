# Environment for local Javascript development 
This repo contains files for setting up a local development environment using docker.
The environment contains the following tech stack:
- MongoDB
- Mongo Express (interface for MongoDB Database)
- Node environment
#### Pre-installed packages
- Body-parser (^1.19.0)
- Connect-redis (6.0.)
- Express (^4.17.1)
- Express-validator (^6.13.0)
- Mongodb (^4.1.4)
- Mongoose (^6.0.13)
- Nodemon (^2.0.15)
- Path (^0.12.7)

## Install docker desktop
To use this repo you need docker engine with docker compose installed.

Refrence the docker website to install docker engine on you machine.
https://www.docker.com/products/docker-desktop

## Get started

1. Navigate to the repo and open a terminal then execute this command:


```shell script
 $ mkdir data/
       cd data/
       mkdir mongodb/
       cd ..
```
### Running the environment
2. Next to start the environment run:
```
    $ docker-compose up --build
```

3. Place your projects and files in the "project folders"


4. In the browser navigate to: http://localhost/

### Stopping the environment

You can easily stop the environment by opening docker desktop interface and stopping the network, or you can execute the following command:
```
    $ docker-compose down
```  

## Mongo Express

Mongo express is available on http://localhost:8081

* The Host is 'mongo' wich will resolve to the correct ip adress in the docker network *

When you are using Node.JS to connect to your local database use the following credentials

| Credentials        | values        |
| ------------------ |:-------------:|
| Host               | mongo       |
| User               | root          |
| Password           | my-secret-pw  |

## Contact

This development environment meant for JavaScript development.
Let me know if you have any feedback! 

Goodluck! 🍀
