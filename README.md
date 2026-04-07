# Foosball Docker Project

This project uses Docker and GitHub Actions to automatically build and push a Docker image.

## Docker
A Dockerfile is used to create a container using the nginx:alpine image. The index.html file is copied into the container so it can be served as a webpage.

## GitHub Actions
The workflow file in .github/workflows/docker.yml automatically runs when code is pushed to the main branch. It logs into Docker Hub, builds the Docker image, and pushes it to Docker Hub with a tag.

## Result
The Docker container runs successfully and displays the updated webpage through localhost.
