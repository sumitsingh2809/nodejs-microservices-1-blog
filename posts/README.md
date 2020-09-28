`BUILD`
docker build .
OR
docker build -t sumitsingh2809/posts:latest .

`RUN`
docker run -p 8080:8080 <imageId/imageName>

`SHELL`
docker run -it sumitsingh2809/posts sh
OR
docker run sumitsingh2809/posts
docker ps
docker exec -it <containerId> sh
