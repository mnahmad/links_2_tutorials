### Containers and Virtual machines

##### Docker

- [How to Create a Docker Image From a Container | Scalyr](https://www.scalyr.com/blog/create-docker-image/)
- [Export docker image]( https://stackoverflow.com/questions/24482822/how-to-share-my-docker-image-without-using-the-docker-hub)
- [Compass app](https://www.youtube.com/watch?v=RcqXFxqIAW4)

__Images__
RShiny
- [Shiny docker image](https://dev.to/bettyes/my-first-shiny-docker-image-1jp7)
- [Shiny rocker image Docker file (github) ](https://github.com/rocker-org/shiny)

Linux
- [Base image (minidocks/base)](https://hub.docker.com/r/minidocks/base) small base image based on alpine linux.
  - [Python docker image (minidocks/python)](https://hub.docker.com/r/minidocks/python) small image based on the image above

Documentation Engines

mkdocs
- [squidfunk/mkdocs-material](https://hub.docker.com/r/squidfunk/mkdocs-material),
    - Start dev server `docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material`
    - Build `docker run --rm -it -v ${PWD}:/docs squidfunk/mkdocs-material build`
- [minidocks/mkdocs](https://hub.docker.com/r/minidocks/mkdocs)



##### KVM
