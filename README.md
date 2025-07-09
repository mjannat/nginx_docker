# Static Website with Nginx in Docker

This project demonstrates how to serve a static website using **Nginx** inside a Docker container.

---

## Pull and Run from Docker Hub

If you just want to run the image directly:
docker pull mjannat/static-site:latest
docker run -d -p 8080:80 mjannat/static-site


If you want to build a new image from this repo, then run:

docker build -t static-site .
docker run -d -p 8080:80 static-site:latest

