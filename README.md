# dockerApacheSymfony7
Generate a docker image based on Php 8.3.2 and Debian Bullseye for Symfony 7

## Build for locally usage
> docker build -t apache-symfony7 .

## Run
> docker-compose up -d

## Publish on Docker hub
```bash
docker login -u "ityannred" docker.io
docker build -t ityannred/apache-symfony7 .
docker tag apache-symfony7:latest ityrannred/apache-symfony7:latest
docker push ityrannred/apache-symfony7:latest
```
