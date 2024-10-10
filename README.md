# Estudo de Caso: Dockerized React App

Este repositório é um estudo de caso de Docker.

## Como Rodar

Para rodar a aplicação, execute os seguintes comandos:

```sh
docker build -t docker-react-image:1.0 .
docker run -d -p 4000:80 --name docker-react-container docker-react-image:1.0
```

Após isso, o app React estará disponível na porta `4000`.