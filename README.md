
## Instructions
Run `docker-compose up -d`

## Force create
Run `docker-compose rm --all &&  docker-compose pull &&  docker-compose build --no-cache &&  docker-compose up -d --force-recreate`

web=localhost:8089
phpmyadmin=localhost:8080