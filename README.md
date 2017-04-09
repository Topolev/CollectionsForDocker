
## Postgre SQL
The main idea is from following a next instruction [link](https://docs.docker.com/engine/examples/postgresql_service/).

* Build an image from the Dockerfile assign it a name.

```
docker build --tag local-pg .
```


* Run container and bind container port 5432  to host port 5432

```
docker run -p 5432:5432 local-pg
```
This image created user for DB with superadmin permissions with the following credentials:

```
username: docker
password: docker
```

