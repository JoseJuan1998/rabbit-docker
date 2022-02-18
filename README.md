# RabbitMQ Docker

## 1. System setup

Install **Docker Desktop** on your system. If is it already installed, skip this step.

* This can be done following the documentation in this link: [`https://docs.docker.com/engine/install/`](https://docs.docker.com/engine/install/)

    *note:* If you install Docker on an Unix like system, you must also install Docker Compose.

## 2. Start the development server

* Navigate to the project directory and run:

```sh
docker-compose up --build
```

* To stop it, simply press `Ctrl + C`.

## Usage

RabbitMQ console: [`http://localhost:15672/`](http://localhost:15672/) (user: `guest`, password: `guest`).
