# Laravel Docker Environment

## Setup Docker Environment

1. Copy .env_docker to .env
2. Set up Docker .env environment.

## Create Laravel Application

1. Create 'src' directory
2. `cd src` and in directory `composer create-project laravel/laravel .`

## Docker

### Start Docker Compose
In root directory where docker-compose.yaml is:

`$ docker compose up -d [--build]`

Optional:

`--build` to build/rebuild once

### Shutdown Docker Compose

`$ docker compose down`

### Enter Docker container

`$ docker exec -it {container-name} [sh|bash]`
