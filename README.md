# Docker Playground

## Some examples

* Updating Dockerfile after changes, you need run:

```sh
[sudo] docker build -t user/project:tag .
```

Where `user/project:tag` is an alias to run your Docker container.

`user/project` can be your own Dockerhub user and project name, and `:tag` is an alias that can be the version of your project.

After that, you can run this with command:

```sh
[sudo] docker run -t user/project:tag
```

* Mounting directories

```
user@localhost:~$ docker run -v /home/user/host_dir:/docker/image/dir docker_image
```

## Links

- [GUI apps with docker :shipit:](http://fabiorehm.com/blog/2014/09/11/running-gui-apps-with-docker/)
- [Docker for DevOps: From development to production](https://www.kickstarter.com/projects/nickjj/docker-for-devops-from-development-to-production)
