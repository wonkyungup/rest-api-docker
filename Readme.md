# The express + maria + docker Rest Api Test

## Environment Introduction
- node-express (https://expressjs.com)
- mariadb (https://mariadb.com)
> Tool
- docker (https://www.docker.com)
- docker-compose (https://docs.docker.com/compose)
- wait-for-it (https://github.com/vishnubob/wait-for-it)
## How to use
1. You need to docker install
```
https://docs.docker.com/engine/install/
```

2. run docker-compose
```
1. cd rest-api-docker
2. docker-compose up
```

## API Url

    GET /v1/user
    DELETE /v1/user
    POST /v1/user/register
    POST /v1/auth
    GET /v1/auth

## Clean Docker Conatainer
1. clean shell script start
```
1. cd rest-api-docker
2. sh docker-clean.sh
```
