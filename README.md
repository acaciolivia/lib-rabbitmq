# lib-rabbitmq

Este projeto é uma biblioteca(lib) para o projeto microsservic-estoque-preco, contendo tudo aquilo que é reutilizado no projeto e nos consumidores.

## Arquitetura

Produtor: Um microserviço desenvolvido em Java com Spring Boot que publica mensagens em uma fila do RabbitMQ.

Consumidor Java: Microserviço desenvolvido em Java com Spring Boot que consome mensagens da fila.

Consumidor Node.js: Um segundo microserviço, desenvolvido em Node.js, também responsável por consumir mensagens da mesma fila.

## Diagrama de arquitetura

![diagramaRabbitmq](https://github.com/user-attachments/assets/0ea28ae0-e961-45d2-bac3-059eadffc22d)
