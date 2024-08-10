# n8n with SQLite

Starts n8n with SQLite as database.

## Start

To start n8n with SQLite simply start docker-compose by executing the following
command in the current folder.

Using docker-compose

```
docker-compose up -d
```

To stop it execute:

```
docker-compose stop
```

To Down container:

```
docker-compose down
```

Using Dockerfile

Create Image

```
docker build -t image_name .
```

Run container

```
docker run -p 5678:5678 --name container_name image_name
```
