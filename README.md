# Steps For Local StartUp

1. Clone The Repository
2. Run the following commands to build and run image-

```shell
docker build -t flask-server:latest .
```

```shell
docker image ls
```

```shell
docker run -p 5000:5000 flask-server:latest
```

3. Now to see the running containers-

```shell
docker ps
```

4. Now to get ip of the container-

```shell
docker inspect <container_id>
```
