# Postgres Docker

## Pull Postgres image

```bash
sudo docker pull postgres:15-alpine

```

## run

```bash
sudo docker run --name postgres15 -p 5432:5432 -e POSTGRES_USER=root -e POSTGRES_PASSWORD=mysecretpassword -d postgres:15-alpine
```

## Exec

Enter psql console
```bash
docker exec -it postgres15 psql -U root
```

exit psql console with `\q`