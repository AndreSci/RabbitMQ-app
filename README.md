# RabbitMQ-app
test producer/consumer for rabbitmq

![Build Status](https://img.shields.io/badge/Docker-2025-blue)
In order to run RabbitMQ you can use docker:

`docker run -it --rm --name rabbitmq -p 5672:5672 rabbitmq`

![Build Status](https://img.shields.io/badge/Go-1.23.5-blue)
Start server (producer):

`go run cmd/server/server.go`

Start client (consumer): 

`go run cmd/client/client.go`

