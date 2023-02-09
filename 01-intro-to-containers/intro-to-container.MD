
## What is a conatiner ?

- https://www.docker.com/resources/what-container/

- https://developers.redhat.com/blog/2018/02/22/container-terminology-practical-introduction#

## The true benefits of moving to containers ?

- https://developer.ibm.com/articles/true-benefits-of-moving-to-containers-1/

## More about Container

- https://docker-curriculum.com/

- https://www.freecodecamp.org/news/the-docker-handbook/

## Architecting Containers

1. https://www.redhat.com/en/blog/architecting-containers-part-1-why-understanding-user-space-vs-kernel-space-matters
2. https://www.redhat.com/en/blog/architecting-containers-part-2-why-user-space-matters
3. https://www.redhat.com/en/blog/architecting-containers-part-3-how-user-space-affects-your-application

## What is a Docker Engine ? (IMP: components of a docker engine like docker cli, docker server/daemon and the REST api that glues both)

https://docs.docker.com/engine/

## Doing Smoke Test if docker has correctly installed ?

docker --version

docker run hello-world (to verify docker is working)

docker run -d -p 8080:80 nginx
