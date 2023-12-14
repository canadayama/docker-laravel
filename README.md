# Laravel Docker Environment

1. Create 'src' directory
2. `cd src` and in directory 'composer create-project laravel/laravel .'

## Docker

In root directory where docker-compose.yaml is:

`$ docker compose up -d [--build]`

Optional:

`--build` to build/rebuild once

`$ docker exec -it {container-name} sh`