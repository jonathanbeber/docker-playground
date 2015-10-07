# Docker Playground

## Some examples

* Mounting directories

```
user@localhost:~$ docker run -v /home/user/host_dir:/docker/image/dir docker_image
```

* Updating Dockerfile after changes, you need run: 

```sh
[sudo] docker build .
```

## Links

- [GUI apps with docker :shipit:](http://fabiorehm.com/blog/2014/09/11/running-gui-apps-with-docker/)
- [Docker for DevOps: From development to production](https://www.kickstarter.com/projects/nickjj/docker-for-devops-from-development-to-production)
