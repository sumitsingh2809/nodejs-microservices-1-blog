`BUILD`
docker build .
OR
docker build -t sumitsingh2809/event-bus:latest .

`RUN`
docker run -p 8080:8080 <imageId/imageName>

`SHELL`
docker run -it sumitsingh2809/event-bus sh
OR
docker run sumitsingh2809/event-bus
docker ps
docker exec -it <containerId> sh
