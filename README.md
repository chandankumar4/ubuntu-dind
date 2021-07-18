# Ubuntu DinD(Docker in Docker) Image

# Concepts
## DinD with a daemon of docker running in the container

This is a isolated way. You can have a clean environment with docker every time you want, and the network and volumes problems dissapears.

# Why another DinD?

1. Want to have ubuntu as the main OS of the image.
2. Want to extend it to create my own dev environments with docker available, getting ride of the common problems sharing sockets.

# How to use it

```bash
kubectl apply -f kubernetes/ubuntu-deploy.yml
```