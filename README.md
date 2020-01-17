# Welcome to demo application of dockerized stack with Express and ReactJS

This repository is an umbrella repo that has 2 submodules: api and web.

It contains code to set up a full stack denvironment with:

- Express API application
- ReactJS web application
- MongoDB database
- Redis cache
- RabbitMQ queue
- Nginx reverse proxy

# Getting started

Add 2 names into /etc/hosts:

```
127.0.0.1 api.core.local #for the API
127.0.0.1 app.core.local #for the web APP
```

Clone this repo and run:

```
git submodule init
git submodule update
docker-compose up
```

Open http://app.core.local in the browser ;)
