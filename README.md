# Error and Solution

## Build Cross CPU Architecture Docker Image

https://blog.jaimyn.dev/how-to-build-multi-architecture-docker-images-on-an-m1-mac/

##  "Could not resolve 'archive.ubuntu.com'" in docker image build
ERROR from building docker image:Docker build "Could not resolve 'archive.ubuntu.com'" apt-get fails to install anything
FIX: docker build --network=host -t my-own-ubuntu-like-image .