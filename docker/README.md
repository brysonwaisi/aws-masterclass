# Pull from docker hub

## Verify Docker version and also login to Docker Hub

```
docker version
docker login
```

## Pull Image from Docker Hub

```
docker pull <image id>
```

## Run the downloaded Docker Image & Access the Application

```
docker run --name app1 -p 80:8080 -d <image id>
http://localhost/hello
```

## List Running Containers

```
docker ps
docker ps -a
docker ps -a -q
```

## Connect to Container Terminal

```
docker exec -it <container-name> /bin/sh
```

## Container Stop, Start

```
docker stop <container-name>
docker start  <container-name>
```

## Remove Container

```
docker stop <container-name>
docker rm <container-name>
```

## Remove Image

```
docker images
docker rmi  <image-id>
```
