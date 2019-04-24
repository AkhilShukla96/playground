# Docker
## Introduction
* **Containers**: Containers are a way of providing the same consistency that dev and ops can rely on. 
* **Docker**: Docker uses containers as a way of isolating one or more processes.

* Docker provides virtualization and without the need for a VM. 
* By having a standardized image format, development sees all servers the same and operations sees all containers the same.

### Image 
* **Portable**: They can be pushed to a registry, or saved as a tar archive.

* **Layered**: The steps in producing an image, are added in layers. In this way, images that are mostly the same, except for the last few steps, can reduce disk usage by sharing parent layers.

* **Static**: The contents are not changeable, unless making a new image.

### Container
* **Runtime**: An environment for PIDs.

* **Writable**: It is essentially an ephemeral storage.

* **Layered**: It is on an image.

## Notes

* Every container is independent of the other containers
* It runs independent of the image, and does not affect the source image at all. 
* As soon as we exit from the container, all the changes are lost and we can run another fresh container from the source image.
* If we want to save the changes, we can export the container as an image and push it to [Docker Hub](https://hub.docker.com). (Similar to snapshot of a VM)
 
## Some resources to get started on Docker
* [What is Docker](https://opensource.com/resources/what-docker)
  A simple introduction about what is Docker and it's uses.
  
* [A begginners guide to Docker](https://opensource.com/business/14/7/guide-docker)
  This is a simple and quick read to get started with Docker. It introduces the basic terminology along with the common commands used.

* A short [video](https://www.youtube.com/watch?v=Q5POuMHxW-0) on introduction to docker

* Link to official [Docker documentation](https://docs.docker.com/engine/docker-overview/)
