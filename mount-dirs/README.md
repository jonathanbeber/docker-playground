# Mount host dirs

[![asciicast](https://asciinema.org/a/d55scjm4yuoo918wwo7697ej7.png)](https://asciinema.org/a/d55scjm4yuoo918wwo7697ej7)

```
[sudo] docker run -v /home/user/host_dir:/docker/image/dir docker_image
```
Where `/home/user/host_dir` is the directory's path (must be full path) that gonna be mounted into the docker's image in `/docker/image/dir`.
