# About this Repo

Quick reference
-	**Where to get help**:  
	[the Docker Community Forums](https://forums.docker.com/), [the Docker Community Slack](https://blog.docker.com/2016/11/introducing-docker-community-directory-docker-community-slack/), or [Stack Overflow](https://stackoverflow.com/search?tab=newest&q=docker)
-	**Where to file issues**:  
	[https://github.com/devmanorg/devman-python-sandbox/issues](https://github.com/devmanorg/devman-python-sandbox/issues)
-	**Supported architectures**: ([more info](https://github.com/docker-library/official-images#architectures-other-than-amd64))  
	[`amd64`](https://hub.docker.com/r/amd64/nginx/), [`arm32v6`](https://hub.docker.com/r/arm32v6/nginx/), [`arm32v7`](https://hub.docker.com/r/arm32v7/nginx/), [`arm64v8`](https://hub.docker.com/r/arm64v8/nginx/), [`i386`](https://hub.docker.com/r/i386/nginx/), [`ppc64le`](https://hub.docker.com/r/ppc64le/nginx/), [`s390x`](https://hub.docker.com/r/s390x/nginx/)
-	**Supported Docker versions**:  
	[the latest release](https://github.com/docker/docker-ce/releases/latest) (down to 1.6 on a best-effort basis)
# What is devman-python-sandbox
# How to generate this image
```bash
docker build -t devman-python-sandbox base-gotty-sandbox/.
```
# Also you can to download image from public Docker Hub repository
```bash
docker pull keinen87/devman-python-sandbox
```
# License

View [license information](https://github.com/devmanorg/devman-python-sandbox/blob/master/LICENSE) for the software contained in this image.