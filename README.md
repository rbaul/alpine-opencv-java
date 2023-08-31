# [OpenCV](https://github.com/opencv/opencv/releases) with Java (JRE) on [Alpine Linux](https://alpinelinux.org/releases/)
> Main idea create minimal image of OpenCV (Build core modules) with Java on Alpine Linux
 
> Use minimal configuration (without Video)

## Reference
[Installation OpenCV on Linux](https://docs.opencv.org/4.x/d7/d9f/tutorial_linux_install.html)

## Usage
### Dockerfile
```
FROM rbaul/alpine-opencv-java:latest
ENTRYPOINT /bin/bash
```

### Pull Image
```
docker pull rbaul/alpine-opencv-java:latest
```
