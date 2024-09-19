# default-docker-wordpress-setup

## Initialize
```sh
docker compose up -d
```

## Turn Off / Destroy Container
```sh
docker compose down
```

This __docker-compose.yml__ setup saves the Wordpress Core same as the DB as a volume and therefore changes are persistent.


## Update wordpress-core volume after adding files to plugins & uploads in the project folder
```sh
docker-compose down
```

```sh
docker build -t busybox .
```

```sh
docker-compose run helper
```

```sh
docker-compose up -d
```