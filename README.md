# java-mqtt-queue

## Requirements
[Docker](https://www.docker.com/)

## Technologies 
[Java 11 (openjdk)](https://openjdk.org/projects/jdk/11/), [Maven](https://maven.apache.org/), [RabbitMQ](https://www.rabbitmq.com/)

## Build project
```bash
sh build
```

## Start RabbitMQ server
```bash
sh broker
```

The service is deployed at http://localhost:5672

HTTP API / UI management is deployed at http://localhost:15672

## Run consumer
```bash
sh consumer
```

Run java class to listen messages from the broker 

## Run producer
```bash
sh producer
```

Run java class to send messages to the broker 
