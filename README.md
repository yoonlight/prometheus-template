# monitoring

## Command

- start

```shell
docker-compose --env-file .env up -d
```

- update

```shell
docker-compose --env-file .env up -d --force-recreate
```

- start using docker swarm

```shell
docker-compose --env-file .env up -d -f docker-stack.yml
```
