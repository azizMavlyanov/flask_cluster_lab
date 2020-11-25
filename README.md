# Docker with database, clustering (Visit counter with MongoDB database)

## Author

Aziz Mavlyanov

## Stack

Python, Flask, PyMongo, MongoDB, Docker

## Installation and usage of the project

**Please make sure that you have docker installed on your PC (Notebook)**

1\) Run containers from the root of the project:

```dotenv
sudo docker-compose up -d --build --force-recreate
```

2\) Visit http://localhost:8080/ and start using the visit counter app

**MongoDB database is persistent** since data located in volume.
