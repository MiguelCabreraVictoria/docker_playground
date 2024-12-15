# Docker commands

### Image management 

Docker images are self-contained software packages that contain all the necessary components to run an application.

  build an image: docker build -t <image_name>
  pulling an image: docker image pull nginx


### Container management

  starting containers: docker container start nginx
  stopping containers: docker container stop nginx
  restarting containers: docker container restart nginx 
  pausing containers: docker container pause nginx
  check the containers : docker ps
  see all running containers: docker container ls
  container logs: docker logs infinite

### Docker Network

  creating an Overlay Network: docker network create -d overlay MyOverlayNetwork
  creating a Bridge Network: docker network create -d bridge MyBridgeNetwork
  removing a network: docker network rm MyOverlayNetwork
  listing networks: docker network ls
