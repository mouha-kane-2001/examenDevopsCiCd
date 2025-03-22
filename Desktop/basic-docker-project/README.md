# Projet : Serveur HTTP Minimaliste avec Docker

## Prérequis
- [Docker](https://www.docker.com/get-started) installé sur votre machine
- [Docker Compose](https://docs.docker.com/compose/) installé

## Installation et Exécution

### 1. Exécution avec Docker
```sh
docker build -t basic-http-server .
docker run -p 8000:8000 basic-http-server