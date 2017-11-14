# [dclong/scala](https://hub.docker.com/r/dclong/scala/)

Scala with Maven and SBT in Docker. 

## About the Author

[Personal Blog](http://www.legendu.net)   |   [GitHub](https://github.com/dclong)   |   [Bitbucket](https://bitbucket.org/dclong/)   |   [LinkedIn](http://www.linkedin.com/in/ben-chuanlong-du-1239b221/)

## Usage 

```
docker run -d \
    -e DOCKER_USER=`id -un` \
    -e DOCKER_USER_ID=`id -u` \
    -e DOCKER_PASSWORD=`id -un` \
    -v $HOME:/wwwroot \
    dclong/scala
```

```
docker run -d \
    -e DOCKER_USER=`id -un` \
    -e DOCKER_USER_ID=`id -u` \
    -v $HOME:/wwwroot \
    dclong/scala
```
