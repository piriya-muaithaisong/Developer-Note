# Docker

## Pull
> Pull an image or a repository from a registry
```bash
docker pull [OPTIONS] NAME[:TAG|@DIGEST]
```

example:
```bash
sudo docker pull postgres:15-alpine
```

ToDo
- ps
- image
- run
- logs
- exec

## run

```bash
sudo docker run --name postgres15 -p 5432:5432 -e POSTGRES_USER=root -e POSTGRES_PASSWORD=mysecretpassword -d postgres:15-alpine
```